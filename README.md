## 🌐 [English Version of README](README_EN.md)

# Self-hosting-n8n-docker

Este projeto configura uma instância do [n8n](https://n8n.io/), uma plataforma de automação de fluxos de trabalho, auto-hospedada utilizando Docker e PostgreSQL como banco de dados. O `docker-compose.yml` fornece um ambiente totalmente configurado para iniciar o n8n com persistência de dados.

## 🔨 Funcionalidades do Projeto

- Instância auto-hospedada do n8n rodando em um container Docker.
- Banco de dados PostgreSQL para armazenar de forma persistente os dados dos fluxos.
- Persistência de dados através de volumes do Docker para o banco de dados.
- Fácil configuração e deployment utilizando Docker Compose.

### Exemplo Visual do Projeto
![n8n Interface](https://docs.n8n.io/assets/img/landing/hero-small.png)

## ✔️ Técnicas e Tecnologias Utilizadas

- **n8n**: Plataforma de automação de fluxos de trabalho.
- **Docker**: Ferramenta de containerização que facilita a criação de ambientes isolados.
- **PostgreSQL**: Banco de dados relacional utilizado para armazenamento de dados.
- **Docker Compose**: Ferramenta para definir e rodar multi-containers Docker.

## 📁 Estrutura do Projeto

- **Dockerfile**: Define o ambiente Docker para o n8n.
- **docker-compose.yml**: Arquivo de configuração do Docker Compose para o n8n e PostgreSQL.
- **README.md**: Documentação do projeto.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Docker e o Docker Compose estão instalados**:
   - Verifique se já tem o Docker instalado rodando:
     ```bash
     docker -v
     ```
   - Se não estiver instalado, baixe e instale o [Docker](https://www.docker.com/get-started) e o [Docker Compose](https://docs.docker.com/compose/install/).

2. **Clone o Repositório**:
   - Copie a URL do repositório e execute o comando abaixo no terminal:
     ```bash
     git clone https://github.com/LipeLacross/Self-hosting-n8n.git
     ```

3. **Configure o ambiente no Docker**:
   - No diretório raiz do projeto, execute o Docker Compose:
     ```bash
     docker-compose up -d
     ```

4. **Acesse a aplicação**:
   - Acesse o n8n na URL `http://localhost:5678`.

## 🌐 Deploy

Para deployar o projeto em um servidor ou plataforma como Render ou Azure, você pode utilizar o mesmo arquivo `docker-compose.yml`. Algumas plataformas podem necessitar de ajustes no Dockerfile ou configurações específicas de rede.
