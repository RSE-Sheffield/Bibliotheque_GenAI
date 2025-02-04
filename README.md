# Bibliotheque_GenAI
Tool for helping people unlock and explore the historical printed resource: [Bibliothèque Britannique](https://books.google.co.uk/books?id=LOWn5elmalEC&pg=PA339&hl=fr&source=gbs_toc_r&cad=2#v=onepage&q&f=false) using Large Language Models.

This codebase is an implementation of Retreival Augmentation Generation (RAG) on this document. This allows users to interact with the document with natural language.

## Start App

Start a [open webui](https://github.com/open-webui/open-webui) app with ollama that works with GPUs:

```sudo docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama```

