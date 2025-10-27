
# 🤖 Chat Inteligente com PDFs usando IA Generativa

Este projeto tem como objetivo desenvolver um sistema de busca inteligente que interpreta arquivos PDF e responde perguntas com base no conteúdo dos documentos. Utilizamos técnicas de IA generativa, embeddings e busca vetorial para criar um assistente virtual personalizado.

---

## 🎯 Objetivos

- Carregar arquivos PDF com conteúdo relevante.
- Indexar os documentos usando embeddings e busca vetorial.
- Utilizar IA para gerar respostas contextualizadas.
- Criar uma interface interativa para perguntas e respostas.

---

## 🧠 Tecnologias Utilizadas

- Python
- LangChain / LlamaIndex / Haystack
- FAISS / ChromaDB (para busca vetorial)
- PyMuPDF (leitura de PDFs)
- Streamlit ou Gradio (interface)
- Git / GitHub

---

## 🗂️ Estrutura do Projeto

```
chat-inteligente-pdf/
│
├── inputs/
│   └── sentencas.txt
│
├── notebooks/
│   └── chat_pdf.ipynb
│
├── vector_search/
│   └── indexacao.md
│
├── interface/
│   └── frontend.md
│
├── images/
│   └── print_chat.png
│
└── README.md
```

---

## ⚙️ Pipeline do Sistema

1. Leitura dos PDFs com PyMuPDF
2. Geração de embeddings dos textos
3. Indexação com FAISS ou ChromaDB
4. Consulta vetorial com base na pergunta
5. Geração de resposta com IA generativa
6. Exibição da resposta na interface

---

## 📊 Resultados

- O sistema consegue responder perguntas específicas com base nos PDFs carregados.
- A busca vetorial permite encontrar trechos relevantes mesmo com perguntas complexas.
- A IA gera respostas contextualizadas e explicativas.

---

## 💡 Insights

- A combinação de embeddings + IA generativa é poderosa para consultas em documentos.
- A estrutura modular permite adaptar o sistema para diferentes tipos de arquivos.
- A interface interativa torna o uso acessível para usuários não técnicos.

---

## 🔮 Possibilidades Futuras

- Suporte a múltiplos PDFs simultâneos
- Classificação automática dos documentos
- Exportação das respostas em formato de relatório

---

## 📎 Como Executar

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/chat-inteligente-pdf.git

# Instalar dependências
pip install -r requirements.txt

# Executar o notebook
jupyter notebook notebooks/chat_pdf.ipynb
```

---

## 📬 Entrega

Este projeto foi desenvolvido como parte de um desafio de portfólio. Para entregar, compartilhe o link deste repositório através do botão **"entregar projeto"** na plataforma.
