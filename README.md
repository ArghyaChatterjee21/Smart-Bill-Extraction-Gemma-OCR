# Gemma Invoice Extractor

This project leverages Gemma-3 vision capabilities and Streamlit to develop a fully operational computer vision app that performs both OCR and structured text extraction from images, all developed using Google Colab.

## Installation and setup


### Setup Ollama:
```sh
# setup ollama on linux
!curl -fsSL https://ollama.com/install.sh | sh
# pull gemma-3 vision model
!ollama run gemma3:4b

```

### Install Dependencies: 
```sh
!pip install streamlit ollama pillow
```

