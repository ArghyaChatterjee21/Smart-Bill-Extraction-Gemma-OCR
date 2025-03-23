# Gemma Invoice Extractor

This project leverages Gemma-3 vision capabilities and Streamlit to develop a fully operational computer vision app that performs both OCR and structured text extraction from images, all developed using Google Colab.

## Installation and setup

### Terminal Access Setup in Google Colab

For terminal access in Google Colab, follow these steps:

1. **Install Colab Xterm:**  
   Run the following command to install the terminal extension:
      ```sh
      !pip install colab-xterm
      ```
2. **Load and Launch the Terminal:**
  Create a new cell in your Colab notebook and run:
     ```sh
     %load_ext colabxterm
     %xterm
     ```  

### Setup Ollama:
3. **Install Ollama**
     ```sh
     # setup ollama on linux
     !curl -fsSL https://ollama.com/install.sh | sh
     ```
4. **Start the Ollama Server:**
  In your terminal, run:
     ```sh
     ollama serve
     ```
  
5. **Pull gemma-3 vision model**
      ```sh
      !ollama run gemma3:4b
      ```

### Install Dependencies: 
```sh
      !pip install streamlit ollama pillow
```

