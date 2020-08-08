<div align="center">
  <img src=".github/logo.svg" alt="Proffy" title="Proffy" />
  
  <div align="center">
    <img src=".github/footer.svg" alt="Proffy Footer" title="Proffy" />
  </div>
  <h2>Sua plaforma de estudos online.</h2>

  <p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/badge/languages-4-blueviolet">

  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made_by-Pietro_Zanetti-blueviolet">

  <img alt="License" src="https://img.shields.io/badge/license-MIT-blueviolet">
</p>
</div>

<p align="center">
  <a href="#bookmark-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="Design do projeto" width="650px" src="./.github/design.png" />
<p>

## :page_with_curl: Sobre

Projeto idealizado com inspiração no **Dia Nacional dos Profissionais da Educação**, o **Proffy** é uma aplicação Web e Mobile com foco em criar uma ponte entre alunos e professores. Sendo assim, a aplicação oferece aos professores um meio de anunciarem suas aulas, com respectivas informações, e aos alunos um meio de busca por aulas.
  
A aplicação foi realizada durante o **Next Level Week**, evento organizado pela [Rocketseat](https://rocketseat.com.br/).

## :computer: Tecnologias

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](http://facebook.github.io/react-native/)
-  [Expo](https://expo.io/)
-  [Express](https://expressjs.com/)
-  [Axios](https://github.com/axios/axios)
-  [Async Storage](https://github.com/react-native-community/async-storage)

## :gear: Executar

```bash
# Clone o repositório
  git clone https://github.com/pietrolzanetti/proffy.git

# Navegue até a pasta server
  cd server
  
# Instale as dependências
  yarn

# Configure o banco de dados e crie a tabela
  yarn knex:migrate

# Inicie a API
  yarn start

# Navegue até a pasta web
  cd web

# Instale as dependências
  yarn

# Inicie o projeto
  yarn start
  
# Navegue até a pasta mobile
  cd mobile

# Instale as dependências
  yarn

# Inicie o projeto
  yarn start
```


## :paintbrush: Layout

[💻 Web](https://www.figma.com/file/Snen317VmzHluRUHBRlzTE/Proffy-Web-Copy?node-id=0%3A1)

[📱 Mobile](https://www.figma.com/file/DwHBNPVW9M0ruTIke5XOYo/Proffy-Mobile-Copy?node-id=0%3A1)

---
<sup>Projeto desenvolvido com tutoria de [Diego Fernandes](https://github.com/diego3g), [Rocketseat](rocketseat.com.br).</sup>
