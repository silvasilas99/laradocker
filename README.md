[![author](https://img.shields.io/badge/author-silvasilas99-red.svg)](https://www.linkedin.com/in/silassantosdasilva/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/silvasilas99/)

# LaraDocker

Este projeto foi criado com a intensão de facilitar o desenvolvimento de novos projetos que podem a ser desenvolvidos por mim, ou por outra pessoa que esteja 
interessada nesta imagem, e queira utilizar a mesma.<br>
Utilizei um pouco do meu conhecimento no GNU/Linux para montar isso, e contei com pesquisas e estudos, com o propósito de criar algo útil para mim e para
se interessar pelo projeto, ele foi testado por mim, e tudo está perfeitamente funcional. 

<br>
<img src="https://i.imgur.com/2A4bSpr.png" >
<br>

## Utilização
- Gere um arquivo .env com base no .env.example: <br>
  ``` cp .env.example .env ``` <br>
- Altere as keys ```DB_DATABASE```, ```DB_USERNAME``` e ```DB_PASSWORD``` <br>
- Configure o docker-compose.yml para adaptar melhor ao seu projeto <br>
- Crie a build para a imagem: <br>
  ``` docker-compose build app ``` <br>
- Rode o ambiente do projeto em background: <br>
  ``` docker-compose up -d ``` <br>
- Verifique se os processos estão ativos: <br>
  ``` docker-compose ps ``` <br>
- Instale as dependências do projeto com o Composer: <br>
  ``` docker-compose exec app composer install ``` <br>
- Gere a app key para o seu projeto: <br>
  ``` docker-compose exec app php artisan key:generate ``` <br>
- Vá para o navegador e acesse este o endereço http://localhost:8000/, tudo deve estar funcionado normalmente <br>


<hr>
Em caso de dúvidas, entre em contato comigo <br>
LinkdIn: https://www.linkedin.com/in/silassantosdasilva/ <br>
E-mail: silvasilas66@gmail.com <br>
