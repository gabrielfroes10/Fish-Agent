# Fish-Agent
# **Fish Agent V0.1 3B**

## **Descrição**
O **Fish Agent V0.1 3B** é um modelo avançado de inteligência artificial, especializado em **Voz para Voz** (Voice-to-Voice) e **Texto para Fala** (Text-to-Speech). Sua arquitetura inovadora elimina a necessidade de tokens semânticos, proporcionando um desempenho superior em aplicações de áudio.

### **Principais Funcionalidades**
- **Clonagem de Voz Zero-shot/Few-shot**: Gera TTS de alta qualidade a partir de amostras vocais curtas (10-30 segundos).
- **Multilíngue**: Suporta inglês, chinês, japonês, coreano, francês, alemão, árabe e espanhol.
- **Alta Precisão**: CER (Taxa de Erro de Caracteres) e WER (Taxa de Erro de Palavras) abaixo de 2%.
- **Aceleração fish-tech**: Processamento rápido em GPUs.
- **Interfaces de Fácil Uso**:
  - WebUI (Gradio).
  - GUI local (PyQt6).
- **Implantação Simplificada**: Suporte nativo para Docker, Linux e Windows (incluindo WSL2).

---

## **Requisitos**
### **Hardware**
- **GPU**:
  - 4 GB VRAM para inferência.
  - 8 GB VRAM para ajuste fino.

### **Sistemas Operacionais Suportados**
- Linux
- Windows (com WSL2 ou Docker para uso avançado)

---

## **Configuração**
### **Windows**
#### **Passo 1: Criar Ambiente Virtual**
```bash
conda create -n fish-speech python=3.10
conda activate fish-speech
