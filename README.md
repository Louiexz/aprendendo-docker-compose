# aprendendo-docker-compose

## 📌 Descrição

Neste projeto, foi utilizado o **Docker Compose** para executar uma aplicação HTML dentro de um container Apache. Você pode ir além e fazer alterações mais robustas no seu projeto, estilizando sua página e aplicando seus conhecimentos em **HTML**, **CSS** e **JavaScript**. Também é possível explorar outras formas de executar seus arquivos HTML com diferentes linguagens de programação.

---

## ✅ Passo a Passo

1. Crie um arquivo **YAML** com as definições de um servidor Apache (`httpd`);
2. Especifique no arquivo **YAML** o local onde os arquivos da aplicação estarão. A aplicação pode ser um simples **Hello World** — mas será que você consegue executar uma aplicação web completa?
3. Suba o arquivo **YAML** e a aplicação para um repositório no **GitHub**.

---

## 🛠️ Ferramentas necessárias

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

---

## 🚀 Executando o projeto

**1️⃣ Clone o repositório**

        git clone https://github.com/Louiexz/aprendendo-docker-compose.git

2️⃣ Clone também o repositório do site dentro do diretório do projeto

        cd aprendendo-docker-compose
        git clone https://github.com/Luixx21/Simple-todo.git website

3️⃣ Suba os containers

        docker compose up -d

4️⃣ Acesse localmente

http://127.0.0.1:8080

---

## 📂 Estrutura do projeto

        aprendendo-docker-compose/
        ├── website/             # Diretório do website (Simple-todo)
        ├── docker-compose.yml   # Arquivo de configuração do Docker Compose
        └── README.md            # Este arquivo de instruções

---

## 💡 Melhorias

Neste projeto foi utilizada a aplicação Simple-todo como exemplo para rodar no servidor Apache. Sinta-se à vontade para criar e gerenciar sua própria lista de tarefas ou substituir por outro projeto seu!

---

## 👨‍💻 Contribuições

Autor: Luiz Augusto (Louiexz)
