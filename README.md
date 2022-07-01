<h1 align="center"> Self Balancing Robot </h1>
<p  align="center"> 
    :construction:  Projeto em construção  :construction:
</p>

<h2 align="center">  Resumo do projeto </h2>
<p>
    Será utilizado a ponte-H L298N para controlar os 2 motores, conectados cada um a um encoder para ter mais precisão no controle. <br>
    A L298N tem uma saída de 5V que irá alimentar diretamente o arduino e outros componentes com essa tensão. <br>
    Poderemos controlar o robô por um controle remoto DIY baseado na transmissão por rádio (NRF24L01). <br>
    E também pelo celular (bluetooth - HC-05) através de um app feio no MIT App Invetor. <br>
    Através do acelerômetro/giroscópio de 3 eixos MPU6050 será medido a angulação do rôbo, que deverá sempre tender a 0 graus (100% vertical). <br>
    Para fazer o controle, será usado o PID controller (controlador proporcional integral derivativo). <br>
    O LM2596 vai dar 6V ao motores pela ponte-H. <br>
    Existe um limite mínimo de tensão da bateria para que o robô funcione normalmente, abaixo desse nível será sinalizado mau funcionamento. <br>
</p>

<h2 align="center">  📁 Descrição dos arquivos </h2>
- main.ino -> arquivo que fica o programa principal

<h2 align="center">  🛠️ Lista de itens </h2>

- 2 motores com encoder
- 2 rodas
- 1 L298N
- 1 MPU6050
- 1 NRF24L01
- 1 HC-05
- Arduino nano ou uno
- 2 baterias de lítio de 4.2V
- 1 chave liga/desliga
- 1 regulador de tensão setp down LM2596
- Divisor de tensão e led vermelhor par ler/sinalizar nível de bateria

<h2 align="center">  ✔️ Técnicas e tecnologias utilizadas </h2>

- ``Arduino``
- ``C++``
- ``POO``
- ``PID controller``
