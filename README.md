TON-BOT V1.1
========

O robô **TON-BOT** é um kit de robótica móvel 3 em 1 com a **Plataforma TON**, destinado ao aprendizado no desenvolvimento de robôs solucionadores de labirinto (micromouse) e robôs seguidores de linha (robotracer). Também podendo ser controlado sem fio pelo Bluetooth.

![ton-bot](https://raw.githubusercontent.com/iotontech/ton-bot/master/images/ton-bot1.jpg)

# Características do Kit

* Motores: micromotor Pololu com caixa de redução de metal - 1000 rpm
* Rodas: 32x7mm (plástico e borracha)
* Encoders: magnético em quadratura - 360 ppr
* 8 Sensores de linha: QRE1113GR
* 4 Sensores de parede: SFH4545 (LED) / TEFT4300 (fototransistor)
* Ponte H dos motores: TB6612FNG
* Bateria: LiPo 1S 600mAh

Com os recursos do **TON** o kit possui: Carregador integrado + Monitor de bateria + Bluetooth 4.0 + Buzzer + accel/gyro/mag + LED RGB + Wi-Fi


# Primeiros Passos

1. Execute o código de testes do robô:
    * O **TON-BOT** é enviado com o código [ton-bot_teste](https://github.com/iotontech/ton-bot_teste) já gravado!
    * Então, conecte o robô em uma porta USB e abra o terminal (baudrate 115200)
    * São apresentadas as leituras de todos os sensores
    * Para testar os motores basta ligar a chave *MOTORS* e pressionar o botão *USER*
    * **Para recarregar a bateria:** conecte o robô no carregador com o botão *USER* pressionado (pode liberá-lo logo em seguida). Quando o LED estiver verde e piscando indica que a bateria já está carregada
2. Siga os passos deste [link](https://github.com/iotontech/IOTON-IDE) para a instalação da *IOTON-IDE* **OU** siga este [tutorial](https://github.com/iotontech/ioton-mbed-online) para usar o *mbed Online Compiler*
3. Programando seu robô:
    * Faça uma cópia do [código de teste](https://github.com/iotontech/ton-bot_teste) e utilize ele de referência
    * Abra o **Editor Atom** e adicione a pasta do projeto: `File→Add Project Folder...`
    * Edite o arquivo *main.cpp*
4. Procedimentos para gravação do código no robô:
    * Colocar o TON no modo **BOOT**: pressionar o botão *RESET/BOOT* por mais de 1s
    * Realizar o **upload**: clicar no botão *“PlatformIO: Upload”* (icone: seta para direita)
    * Aguardar o término do processo
    * Voltar o TON para a execução: pressione rapidamente o botão *RESET/BOOT*


# License

Copyright IOTON Technology 2017.

This documentation describes Open Hardware and is licensed under the CERN OHL v. 1.2.
You may redistribute and modify this documentation under the terms of the CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable conditions.
