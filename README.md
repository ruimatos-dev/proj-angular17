# Uso do Angular 17  com Docker
Projeto útil para desenvolvimento de novos aplicativos angular utilizando docker no servidor angular.

## Como utilizar o aplicativo?

- Faça o clone do projeto através do git
- Rode os seguintes comandos

~~~bash
docker build -f Dockerfile -t proj-angular17 .
docker run -p 4200:4200 proj-angular17
~~~

Agora o aplicativo ja pode ser aberto no navegador http://localhost:4200

Use o editor de sua  preferencia para modificar o código.

