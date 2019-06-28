# Automacao_Residencial_Telegram_Bot
Projeto do Laboratório de Eletrônica 2019/1

## Descrição

Dispositivo de automação residencial utilizando a placa NodeMCU ESP32 que realiza o acionamento de LEDs (simulado luminárias) e 
um servo (simulando uma fechadura eletrônica) através de mensagens enviandas para um Bot do Telegram.

## Como criar o Bot no Telegram

1-Procure por BotFather e inicie um chat com esse Bot:

![](https://github.com/gustavobartho/Automacao_Residencial_Telegram_Bot/blob/master/Imagens/img_1.png "")

2-Em seguida envie "/newbot" para criar um novo Bot vinculado a sua conta:

![](https://github.com/gustavobartho/Automacao_Residencial_Telegram_Bot/blob/master/Imagens/img_2.png "")


3-Envie o nome e em seguida o username do Bot (o username deve obrigatoriamente terminar com "bot"):

![](https://github.com/gustavobartho/Automacao_Residencial_Telegram_Bot/blob/master/Imagens/img_3.png "")


4-Com o Bot criado um Token será fornecido, esse Token é utilizado para conectar a ESP32 ao Bot:

![](https://github.com/gustavobartho/Automacao_Residencial_Telegram_Bot/blob/master/Imagens/img_4.png "")

## Circuito

![](https://github.com/gustavobartho/Automacao_Residencial_Telegram_Bot/blob/master/Imagens/Circuito.png "Circuito ESP32")


