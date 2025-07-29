<div align="center">
  <h1> - Job4You - </h1>

  ![Foto da página inicial](preview.jpeg)

  [![PHP Version](https://img.shields.io/badge/PHP-%38.4-blue.svg?style=for-the-badge&color=purple)](https://www.php.net/)
  [![TailwindCSS Version](https://img.shields.io/badge/TailwindCSS-%5E4.0-38BDF8.svg?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
  [![Made in Brazil](https://img.shields.io/badge/Made%20in-Brazil-009933.svg?style=for-the-badge&color=28A745)](https://github.com/ItaloBrazucaDeveloper/job-four-you)
  [![MySQL Version](https://img.shields.io/badge/MySQL-%38.4-blue.svg?style=for-the-badge)](https://www.mysql.com/)
  [![Kiss-Php Version](https://img.shields.io/badge/%20%F0%9F%98%98kiss--php-0.1.0-yellow.svg?style=for-the-badge&logo=kissphp&logoColor=white)](https://github.com/ItaloBrazucaDeveloper/kiss-php)
</div>

## 💡 Sobre o projeto
Já precisou de limpeza na sua casa, alguém para passear com seu pet, um dia de fotos, mas não sabia a quem solicitar esses serviços? A plataforma Job4You resolve esse problema conectando pessoas com prestadores de serviço informal, facilitando a busca e divulgação.

## 📦 Instalação
Siga o passo a passo de como instalar o projeto na sua máquina.

1. **Clone o projeto do github**

  ```bash
    $ git clone -b main https://github.com/BrazucaDeveloper/job-four-you.git
  ```

2. **Entre na pasta do projeto**
  
  ```bash
    $ cd ./Etb-Tcc
  ```

## 🚀 Como iniciar o projeto
> **Atenção:** Certifique-se de ter o [Docker](https://www.docker.com/) e o [Docker Compose](https://docs.docker.com/compose/) instalados em sua máquina antes de usar este método.

1. **Copie e renomeie o arquivo `.example.env`**

  ```bash
    $ cp .example.env .env
  ```

2. **Defina as variáveis de ambiente no arquivo `.env`**
  ```bash
    $ nano .env
  ```

3. **Construa e inicie os containers**

  ```bash
    $ docker compose up --build
  ```
  > **Observação:** Use a flag `--build`, apenas quando for a primeira vez executando o projeto. A flag `--build` faz a contrução das imagens dos arquivos _Dockerfile_. Uma vez já construídos, omita a flag `--build` e use:`docker compose up`.

4. **Acesse o projeto pelo navegador no link: http://localhost:3000/** (substitua o número 3000 pelo número de porta que você escolheu)

## ⚒️ Ferramentas utilizadas
- 🐘 [PHP](https://www.php.net/) (Linguagem de programação)
- 🐬 [MySQL](https://www.mysql.com/) (Banco de dados)
- 🐳 [Docker](https://www.docker.com/) (Ferramenta de containerização)
- ⚙️ [Docker Compose](https://docs.docker.com/compose/) (Ferramenta de gerenciamento de containers)
- 😘 [Kiss-Php](https://github.com/ItaloBrazucaDeveloper/kiss-php) (Framework PHP)
- 🌬️ [TailwindCSS](https://tailwindcss.com/) (Framework CSS)
- ✉️ [Resend](https://resend.com/home) (API de email)
- 🔐 [JWT](https://github.com/nowakowskir/php-jwt) (Autenticação)
- 🌱 [Dotenv](https://github.com/vlucas/phpdotenv) (Gerenciamento de variáveis)

## 🧠 Mentes por trás do projeto
- [☕ Yan](https://github.com/YanGabrielton) (Desenvolvedor back-end)
- [🎨 Allana](https://github.com/leitielly) (Desenvolvedora front-end)
- [✍️ Aline](https://github.com/alineop120) (Analista de sistemas)
- [🏅 Giovanna](https://github.com/giihzinha0L70) (Analista de sistemas)
- [🎲 Ítalo](https://github.com/ItaloBrazucaDeveloper) (Desenvolvedor full-stack | DBA)
