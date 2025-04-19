# docling-rag-tutorial-pydata-2025
This repo has collection of respurces for the tutorial **Building Rich RAG Systems with Docling: Unlock Information from Tables, Images, and Complex Documents** at PyData 2025 https://cfp.pydata.org/virginia2025/talk/XPFPFE/ 



# Pre-work
You will need a way to do LLM inference for the `generation` step of RAG. For that you can have a local `ollama` server with a smaller model (1b, 2b, 3b) or quantized version of a larger model or simply use one the services like Hugging Face / Replicate / Watsonx 
1. **Remote LLM inference:** Make sure you have a Huggging Face / Replicate token if you want to perform LLM inference (look at the setup directory for more details)
2. **Local LLM inference:** Make sure you download and install ollama https://ollama.com/  (look at the setup directory for more details)


# Docling Technical Paper: 

The Docling Technical paper (https://arxiv.org/pdf/2408.09869v4) has detailed information on the models behind and how the document processing works for layout recognition, table structure recognition and optional OCR. 


<img width="660" alt="image" src="https://github.com/user-attachments/assets/2949d164-cfd6-4f22-946d-1257cba31ee7" />



