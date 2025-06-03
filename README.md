# Projeto Inicial Battlesnake Python

Um modelo não oficial do Battlesnake escrito em Python. Comece em [play.battlesnake.com](https://play.battlesnake.com).

![Logo Battlesnake](https://media.battlesnake.com/social/StarterSnakeGitHubRepos_Python.png)

Este projeto é um ótimo ponto de partida para quem deseja programar seu primeiro Battlesnake em Python. Ele pode ser executado localmente ou facilmente implantado em um provedor de nuvem de sua escolha. Consulte a [Documentação da API Battlesnake](https://docs.battlesnake.com/api) para mais detalhes.

## Tecnologias Utilizadas

Este projeto usa [Python 3](https://www.python.org/) e [Flask](https://flask.palletsprojects.com/).

## Execute seu Battlesnake

Inicie seu Battlesnake

```sh
python main.py
```

Você deverá ver algo do tipo assim que estiver em execução:

```sh
Running your Battlesnake at http://0.0.0.0:8000
 * Serving Flask app 'My Battlesnake'
 * Debug mode: off
```

## Jogue uma Partida Localmente

Instale a [CLI Battlesnake](https://github.com/BattlesnakeOfficial/rules/tree/main/cli)

  * Você pode [baixar binários compilados aqui](https://github.com/BattlesnakeOfficial/rules/releases)
  * ou [instalar como um pacote go](https://github.com/BattlesnakeOfficial/rules/tree/main/cli#installation) (requer Go 1.18 ou superior)

Comando para executar um jogo local

```sh
battlesnake play -W 11 -H 11 --name 'Python Starter Project' --url http://localhost:8000 -g solo --browser
```
