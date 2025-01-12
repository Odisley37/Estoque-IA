# Estoque GPT

Um assistente inteligente para consultar o banco de dados de estoque utilizando o Streamlit e o LangChain.

## Descrição

Este projeto utiliza o modelo GPT (via LangChain) para fornecer insights sobre o estoque de produtos, preços, reposições e relatórios. Ele possui uma interface amigável desenvolvida com Streamlit, permitindo ao usuário fazer perguntas e obter respostas formatadas em português.

## Tecnologias Utilizadas

- **Streamlit**: Para construir a interface interativa.
- **LangChain**: Para gerenciar interações com o modelo de linguagem GPT.
- **SQLite**: Banco de dados para armazenar informações de estoque.
- **Python-Decouple**: Para gerenciar variáveis de ambiente, como a chave de API.

## Como Funciona

1. O usuário escolhe o modelo GPT a ser usado na barra lateral.
2. Insere uma pergunta sobre o estoque, como produtos, preços ou reposições.
3. O sistema utiliza o banco de dados SQLite e o GPT para gerar uma resposta formatada e amigável.
4. As respostas são sempre fornecidas em português brasileiro.

## Configuração do Projeto

### Pré-requisitos

Certifique-se de ter instalado:
- Python 3.8 ou superior
- [Streamlit](https://streamlit.io/)
- Uma chave de API do OpenAI

### Passos para Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/Odisley37/Estoque-IA.git
   cd estoque-gpt

### Licença
Essa estrutura inclui um resumo claro, tecnologias usadas, instruções de configuração, e uso. Ajuste conforme necessário para seu contexto.

