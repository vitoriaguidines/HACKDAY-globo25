<<<<<<< HEAD
# Projeto: Agente de Geração e Envio de Vídeos Inteligentes

Este projeto utiliza **Google Cloud Agent Development Kit (ADK)** e
**Vertex AI** para criar agentes inteligentes capazes de:

-   Coletar dados dos usuários.\
-   Enriquecer e categorizar informações com IA.\
-   Gerar **prompts customizados**.\
-   Transformar prompts em **vídeos automatizados**.\
-   Enviar os vídeos diretamente por **Telegram** ou outros canais de
    comunicação.

O objetivo é fornecer uma solução escalável de **marketing digital
personalizado**, **comunicação automatizada** e **engajamento de
usuários**.

------------------------------------------------------------------------

## 🚀 Estrutura do Projeto

    📂 video-agent-project
     ┣ 📂 agents/               # Definições dos agentes e fluxos de dados
     ┣ 📂 services/             # Serviços auxiliares (API Telegram, armazenamento, etc.)
     ┣ 📂 models/               # Modelos e prompts de IA
     ┣ 📂 utils/                # Funções utilitárias e helpers
     ┣ 📂 config/               # Configurações (chaves, variáveis de ambiente, etc.)
     ┣ 📂 tests/                # Testes unitários e de integração
     ┣ 📄 main.py               # Ponto de entrada da aplicação
     ┣ 📄 requirements.txt      # Dependências do Python
     ┣ 📄 README.md             # Documentação do projeto
     ┗ 📄 .gitignore            # Arquivos a serem ignorados pelo Git

------------------------------------------------------------------------

## 🛠️ Pré-requisitos

-   Conta no **Google Cloud Platform (GCP)**\
-   Projeto criado no **Cloud Console**\
-   Serviços habilitados:
    -   **Vertex AI**\
    -   **Cloud Storage**\
    -   **Cloud Run**\
-   **Python 3.10+**\
-   Biblioteca **google-cloud-sdk** instalada

------------------------------------------------------------------------

## 📦 Instalação

Clone este repositório:

``` bash
git clone https://github.com/seu-usuario/video-agent-project.git
cd video-agent-project
```

Crie um ambiente virtual e instale as dependências:

``` bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate    # Windows

pip install -r requirements.txt
```

------------------------------------------------------------------------

## ▶️ Como Executar Localmente

``` bash
python main.py
```

------------------------------------------------------------------------

## ☁️ Deploy no Google Cloud Run

1.  Autentique-se no Google Cloud:

    ``` bash
    gcloud auth login
    ```

2.  Configure o projeto:

    ``` bash
    gcloud config set project SEU_PROJETO_ID
    ```

3.  Faça o deploy:

    ``` bash
    gcloud run deploy video-agent --source . --region=us-central1 --allow-unauthenticated
    ```

------------------------------------------------------------------------

## 🤖 Fluxo do Agente

1.  Usuário envia informações via canal (ex: Telegram).\
2.  Agente coleta e enriquece os dados.\
3.  IA gera um **prompt personalizado**.\
4.  Vertex AI cria um **vídeo** a partir do prompt.\
5.  Vídeo é armazenado no **Cloud Storage**.\
6.  Link assinado é gerado e enviado para o usuário no **Telegram**.

=======
# HACKDAY-globo25
>>>>>>> 0fddfebccceb915803e920032fe11ca5caddbce9

