https://github.com/templateacessivel/dsdeliver-sds2
# DS Delivery 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre o projeto

https://sds2-andreza-secon.netlify.app/

DS Delivery é uma aplicação full stack web e mobile construída durante a 1ª edição da **Semana DevSuperior** (#sds), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um app de pedidos e envio de pedidos, onde um cardápio é listado ao usuário, que escolhe os produtos e adiciona o endereço de entrega, após enviar o pedido com sucesso, os pedidos são listados no app mobile do motoboy que escolhe os pedidos a serem entregues e atravé do próprio app é traçado a rota de entrega

## Layout mobile
![Mobile 1]() ![Mobile 2]()

## Layout web
![Web 1]()

![Web 2]()

## Modelo conceitual
![Image](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/modelo-conceitual.png)

## Camadas
![camadas](https://github.com/devsuperior/sds2/blob/master/assets/camadas.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven

## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native

## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
https://github.com/templateacessivel/dsdeliver-sds2

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
https://github.com/templateacessivel/dsdeliver-sds2

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
npm install

# executar o projeto
npm start
```

# Autor

Andreza Secon

https://www.linkedin.com/in/andreza-secon-b5736788/
