## Status do Projeto

[![Pipeline - CI/CD](https://github.com/Gabriel-Bur/DevOpsChallenge/workflows/Pipeline%20-%20CI/CD/badge.svg)](https://github.com/Gabriel-Bur/DevOpsChallenge/actions?query=workflow%3A%22Pipeline+-+CI%2FCD%22)

[![Docker CI/CD](https://github.com/Gabriel-Bur/DevOpsChallenge/workflows/Docker%20CI/badge.svg)](https://github.com/Gabriel-Bur/DevOpsChallenge/actions?query=workflow%3A%22Docker+CI%22)

![Code Size](https://img.shields.io/github/languages/code-size/Gabriel-Bur/DevOpsChallenge)


## Explicação

Ao realizar um push na master dois workflows serão ativados, para cada workflow será feito um deploy no devido ambiente:

- [API Production](https://app-mywebapp-prod-001.azurewebsites.net/weatherforecast) | [Docker API Production](https://app-mywebapp-prod-002.azurewebsites.net/weatherforecast)

- [API Test](https://app-mywebapp-test-001.azurewebsites.net/weatherforecast) | [Docker API Test](https://app-mywebapp-test-002.azurewebsites.net/weatherforecast)
