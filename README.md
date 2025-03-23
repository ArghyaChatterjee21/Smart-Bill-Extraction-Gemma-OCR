# Gemma-3 OCR App

This project leverages Gemma-3 vision capabilities and Streamlit to create a 100% locally running computer vision app that can perform both OCR and extract structured text from the image.

## Installation and setup
### Install Dependencies:
```sh
!pip install streamlit ollama pillow

### Setup Ollama:
```sh
# setup ollama on linux
!curl -fsSL https://ollama.com/install.sh | sh
# pull gemma-3 vision model
!ollama run gemma3:4b


