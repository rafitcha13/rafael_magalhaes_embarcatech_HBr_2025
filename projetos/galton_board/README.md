# Galton Board Digital

Este projeto implementa uma versão digital de uma Galton Board (ou Plinko), demonstrando como uma série de decisões binárias aleatórias leva a uma **distribuição normal de probabilidades**.

## Objetivo

Criar uma visualização interativa que simula o comportamento de uma Galton Board usando:

- Display OLED
- Botões para incluir desequilíbrios ao modelo

##  Lista de materiais: 

| Componente            | Conexão na BitDogLab      |
|-----------------------|---------------------------|
| BitDogLab (RP2040)    | -                         |
| Matriz WS2812B 5x5    | GPIO7                     |
| Display OLED I2C      | SDA: GPIO14 / SCL: GPIO15 |
