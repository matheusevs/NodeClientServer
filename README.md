# NodeClientServer

Este projeto tem como objetivo, permitir a realização do cadastro de usuário dentro do sistema, sendo possível fornecer alguns dados básicos, como nome, e-mail, data de nascimento, sexo, etc., além disso, o mesmo possui validações sobre os dados informados no momento do cadastro. Foi implementando também, a possibilidade de realizar a edição dos usuários cadastrados, assim como, a exclusão. De princípio, o armazenamento dos usuários cadastrados foi realizado através do LocalStorage, conforme <a href="https://github.com/matheusevs/gerenciamentoDeUsuariosJs">esse repositório</a> onde caso ocorresse a limpeza do cache do navegador, sendo assim, um armazenamento volátil. Contudo, após conhecer melhor a ferramenta NodeJS, foram realizadas modificações para que o armazenamento dos dados dos usuários cadastradas fossem realizados com o NodeJS, aprimorando o conhecimento sobre a ferramenta e colocando os conhecimentos em prática. Este projeto foi desenvolvido como exemplo do Curso Completo de JavaScript e NodeJS na Udemy pela HCode.

---

# Orientação

Segue as orientações gerais para desenvolvedores que desejarem rodar o projeto em sua máquina.

**Para rodar o projeto em seu computador, é necessário ter instalado:**

- <a href="https://nodejs.org/en/">NodeJS - v14.20.1</a>

**Após a instalação de todos as ferramentas acima, rode os seguintes comandos em seu terminal:**


```bash
sudo npm install nodemon -g

cd client-server/public
sudo npm install -g bower
bower install
cd ../
npm install
npm start
```

**Após isso, abra um novo terminal na pasta raiz e continue rodando os comandos:**

```bash
cd restful
npm install
nodemon index.js
```


**Após rodar todos os comandos, acesse a url http://localhost:3000/ para ter acesso a aplicação**

---

<img src="gif.gif">

##
