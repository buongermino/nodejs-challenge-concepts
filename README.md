# nodejs-challenge-concepts
## 1º desafio do bootcamp GoStack: aplicando os conceitos de NodeJS

O código desenvolvido usa conceitos básicos usando a linguagem JavaScript, através do interpretador de código **NodeJS**, que possibilita
a escrita de código no backend de uma aplicação (server-side).

A aplicação utiliza métodos HTTP para fazer requisições através dos métodos **GET, POST, UPDATE e DELETE**, através de rotas e é
baseada num modelo de criação de repositórios, onde é possível, através destas rotas:

 - criar um repositório (POST) que título contenha título, url e tecnologias. É gerado automaticamente um ID e iniciado com o número de likes = 0. 
 - listar (GET) os repositórios que já foram criados.
 - atualizar (PUT) os campos do título, url e tecnologias, exceto os campos id e likes. 
 - deletar (DELETE) os repositórios já criados.
 - adicionar um like a um repositório criado.
 
Todos os testes foram realizados tanto em software de requisições, quanto os próprios testes automatizados incluídos.

Obs: Caso tenha interesse em testar, ao clonar o repositório instale as dependências e pacotes executando o código 'yarn' ou
gerenciador de pacotes de preferência.
