# Quiz SPFC com Apache + Docker

Este projeto é uma aplicação web simples construída com HTML e CSS  que apresenta um quiz interativo com curiosidades sobre o São Paulo Futebol Clube. A aplicação roda em um contêiner Docker usando a imagem oficial do Apache HTTP Server.

## Tecnologias Utilizadas

- HTML5, CSS3
- Docker
- Apache HTTP Server (imagem `httpd:latest`)
- Docker Compose (versão 3.9)

## Estrutura do Projeto

├── compose.yml ├── website/ │ ├── index.html │ └── fundo.jpg


- `compose.yml`: Define o serviço Apache que servirá os arquivos HTML.
- `website/`: Pasta com o site estático (HTML e imagem de fundo).

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/danruimdegame/docker-projeto1-dio.git
   cd docker-projeto1-dio
2. Inicie os serviços com Docker Compose:
   ```bash
   docker-compose up -d
3. Acesse o site no navegador:
   ```bash
   http://localhost

## Visual da Página
A aplicação apresenta:

  - Um background personalizado com imagem (fundo.jpg)

  - Perguntas de múltipla escolha

  - Cronômetro regressivo de 60 segundos

  - Feedback visual de acertos e erros

Caso queira contribuir com novas perguntas ou temas, fique à vontade para abrir uma issue ou um pull request!
