## Status do Projeto

[![Test](https://github.com/Gabriel-Bur/DevOpsChallenge/workflows/Test/badge.svg?branch=master&event=push)](https://github.com/Gabriel-Bur/DevOpsChallenge/actions)
[![Production](https://github.com/Gabriel-Bur/DevOpsChallenge/workflows/Production/badge.svg?branch=master&event=push)](https://github.com/Gabriel-Bur/DevOpsChallenge/actions)
![Code Size](https://img.shields.io/github/languages/code-size/Gabriel-Bur/DevOpsChallenge)


## Explicação

Ao realizar um push na master dois workflows serão ativados, para cada workflow será feito um deploy no devido ambiente:

- [WorkFlow Production](https://github.com/Gabriel-Bur/DevOpsChallenge/actions?query=workflow%3AProduction) / [API Production](https://app-mywebapp-prod-001.azurewebsites.net/weatherforecast)
- [WorkFlow Test](https://github.com/Gabriel-Bur/DevOpsChallenge/actions?query=workflow%3ATest) / [API Test](https://app-mywebapp-test-001.azurewebsites.net/weatherforecast)
