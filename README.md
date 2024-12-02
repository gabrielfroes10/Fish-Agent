# **Fish Agent V0.1 3B**

## **Descrição**
O **Fish Agent V0.1 3B** é um modelo de inteligência artificial avançado projetado para tarefas de **Voz para Voz** (Voice-to-Voice) e **Texto para Fala** (Text-to-Speech). Ele utiliza uma arquitetura inovadora que elimina a necessidade de tokens semânticos, proporcionando desempenho superior em aplicações de áudio.

---

## **Como é ou será usado?**
Este modelo oferece uma ampla gama de aplicações, incluindo:
- **Clonagem de voz personalizada**: Criação de perfis vocais únicos a partir de amostras curtas.
- **Tradução e síntese de voz multilíngue**: Ideal para conteúdos globais.
- **Interface humano-máquina**: Uso em assistentes virtuais e dispositivos inteligentes.
- **Produção de mídia**: Geração de audiolivros, narrações e outros conteúdos.
- **Monitoramento de áudio ambiental**: Aplicações em segurança e pesquisa.

---

## **Principais Funcionalidades**
- **Clonagem de Voz Zero-shot e Few-shot**: Gera saídas de TTS de alta qualidade com uma amostra vocal curta (10-30 segundos).  
- **Multilíngue**: Suporte a idiomas como:
  - Inglês
  - Chinês
  - Francês
  - Alemão
  - Japonês
  - Coreano
  - Árabe
  - Espanhol
- **Alta Precisão**:
  - CER (Taxa de Erro de Caracteres): ~2%.
  - WER (Taxa de Erro de Palavras): ~2% em textos em inglês.
- **Velocidade e Eficiência**: Aceleração **fish-tech** para processamento rápido em GPUs.
- **Interfaces Simples**:
  - **WebUI**: Interface de navegador (Gradio).
  - **GUI Local**: Compatível com Windows, Linux e macOS.
- **Configuração Amigável**:
  - Suporte a Docker e WSL2 para fácil implantação.

---

## **Como Rodar**
### Passos Rápidos:
1. **Requisitos**:
   - **GPU**: 4GB (inferência) ou 8GB (ajuste fino).
   - **Sistema Operacional**: Linux ou Windows.

2. **Configuração Básica**:
   - Configure o ambiente Python com `conda` ou `virtualenv`.
   - Instale as dependências principais, incluindo PyTorch e Fish-Speech.

3. **Opções de Execução**:
   - **WebUI**: Use a interface gráfica baseada em navegador para inferência.
   - **API**: Implante um servidor para integração com outros sistemas.

4. **Documentação Completa**:
   Consulte a documentação detalhada, incluindo guias de instalação e exemplos de uso, em:  
   [Documentação Fish Speech](https://speech.fish.audio/pt/)

---

## **Licença**
Este projeto está licenciado sob a **BY-CC-NC-SA-4.0**, permitindo uso não comercial com atribuição apropriada.

## **Citação**
Se este projeto for útil para você, por favor cite:
```bibtex
@misc{fish-agent-0.1,
    author = {Shijia Liao and Tianyu Li e Rcell e outros},
    title = {Fish Agent V0.1 3B},
    year = {2024},
    publisher = {GitHub},
    journal = {GitHub repository},
    howpublished = {\url{https://github.com/fishaudio/fish-speech}}
}
