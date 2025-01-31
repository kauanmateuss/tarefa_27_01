# TAREFA 1 27/01 - Projeto sobre interrupções e controles de LEDs

## Descrição

Este projeto tem como objetivo explorar o uso de interrupções e controle de LEDs em microcontroladores, utilizando a placa de desenvolvimento **BitDogLab** e o microcontrolador **RP2040**. A tarefa envolve a implementação de interrupções para manipular botões, debouncing via software e controle da matriz de LEDS e o LED RGB. O projeto tem como função a exibição de números em uma matriz de LEDs e interações com dois botões para incrementar e decrementar os valores exibidos.

## Objetivos

- Controlar O LED RGB e a matriz de LEDs WS2812.
- Compreender e implementar interrupções em microcontroladores.
- Utilizar debouncing via software para evitar o fenômeno de bouncing nos botões.
- Utilizar resistores de pull-up internos em botões de acionamento.
- Desenvolver um projeto funcional combinando hardware e software.

## Componentes Utilizados

- **Matriz 5x5 de LEDs WS2812** conectada à **GPIO 7**.
- **LED RGB** com pinos conectados às **GPIOs 11, 12 e 13**.
- **Botão A** conectado à **GPIO 5**.
- **Botão B** conectado à **GPIO 6**.

## Funcionalidades

1. O **LED vermelho** do LED RGB pisca continuamente 5 vezes por segundo.
2. O **botão A** incrementa o número exibido na matriz de LEDs cada vez que for pressionado.
3. O **botão B** decrementa o número exibido na matriz de LEDs cada vez que for pressionado.
4. Os LEDs WS2812 são usados para criar efeitos visuais representando números de 0 a 9, utilizando um estilo digital fixo (ou criativo, mas claramente identificável).

## Vídeo de Demonstração

[Para visualizar o funcionamento do projeto, assista ao vídeo.](https://youtube.com/shorts/cXibjiq9wIE?si=LgMv-j15H8Y0yjKz)
