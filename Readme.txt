# MagicBoard

MagicBoard é um programa interativo que utiliza visão computacional para desenhar em tempo real com base nos movimentos da mão capturados pela câmera. Ele permite que o usuário desenhe linhas na tela utilizando gestos específicos com os dedos.

## Funcionalidades

- **Desenho com um dedo levantado**: Quando o usuário levanta apenas um dedo (indicador), o programa desenha um ponto na posição correspondente e conecta os pontos consecutivos com linhas.
- **Pausa no desenho**: Quando o usuário levanta mais de um dedo, exceto três dedos, o desenho é pausado.
- **Limpar o desenho**: Quando o usuário levanta três dedos, o desenho atual é apagado.

## Requisitos

Certifique-se de instalar as dependências necessárias antes de executar o programa. Você pode instalá-las usando o comando abaixo:

```bash
pip install cvzone==1.6.1 mediapipe==0.10.14 opencv-python==4.9.0.80