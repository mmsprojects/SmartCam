# SmartCam
Câmera Inteligente ou SmartCam é um projeto de um protótipo de Câmera + Lidar com o proposito de coletar, analisar e gerar relatórios inteligentes em tempo real. O produto possui múltiplos sensores ópticos e um sensor lidar para coletar informações de ambientes e objetos com a integração de modelos IA.

![Mobile 1](https://lh3.googleusercontent.com/pw/ADCreHdXW0txd6Q8diZiEU2WuvuwZu1Vok41Yfp_AncVJc9L95SPsAfAOmJU3jh0Rl4boQFbqT_k05TYJUDbHOZUrWB2sjV-kK_UK0wKcE6xoNrLF6_OzPYHtfk-vtbfktUa3kR8wDsT4-2i759S_t2Si97i=w842-h842-s-no?authuser=0)

# Sobre o projeto

https://wmazoni-sds1.netlify.app

Big Game Survey é uma aplicação full stack web e mobile construída durante a 1ª edição da **Semana DevSuperior** (#sds1), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em uma pesquisa de preferência de games, onde os dados são coletados no app mobile, e depois são listados no app web, que também apresenta um dashboard com gráficos baseados nestes dados.

## Layout mobile
![Mobile 1](https://lh3.googleusercontent.com/pw/ADCreHfsz6NmAE_V79lEFHSSMoyOq71m2EbPIrDJXexpQWduaMFotcVF0yCeqcB1wuKEmbvNMgLmGJQX-WK6HZtbOOlXxB5ynYz7adB83BwUHD6gKAPl6ARfitaNE0R-KW-HqewCvTcG4cqSoe4MrEMDjvZ4=w842-h632-s-no?authuser=0) ![Mobile 2](https://github.com/acenelio/assets/raw/main/sds1/mobile2.png)

## Layout web
![Web 1](https://github.com/acenelio/assets/raw/main/sds1/web1.png)

![Web 2](https://github.com/acenelio/assets/raw/main/sds1/web2.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/acenelio/assets/raw/main/sds1/modelo-conceitual.png)

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
- Apex Charts
- Expo
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
