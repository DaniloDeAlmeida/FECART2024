# Carrinho e Percurso LED usando o Mindwave

### Descrição:
  Para o nosso projeto da FECART 2024 nós tivemos a ideia de criar um código no arduino para fazer um carrinho andar e LEDs acenderem usando apenas a sua mente. Utilizamos o Mindwave para captar certas ondas cerebrais que chamamos de "concentração", e quando a concentração alcançava um nível específico o código prosseguia. O projeto do LED era mais simples, uma protoboard pequena com 4 LEDs posicionados em fileira, e quanto maior sua concentração, mais LEDs se acendiam.

### Códigos
  Nós utilizamos a linguagem do Arduino para conectar o Mindwave com o carrinho e os LEDs.

#### Comandos AT:
  AT+UART=57600,0,0
  AT+ROLE=1
  AT+PSWD="0000"
  AT+CMODE=0
  AT+BIND=0081,F9,12CF79
  AT+IAC=9E8B33
  AT+CLASS=0
  AT+INQM=1,9,48

#### Código do carrinho: 

#### Código do LED: 

### Materiais utilizados:

♦ 2 Arduinos

♦ 2 Motores DC

♦ Aparelho Mindwave

♦ Chassi do carrinho

♦ Fonte de alimentação do arduino(Bateria 9V)

♦ 4 pilhas AA para alimentar os motores DC

♦ 4 Leds

♦ Protoboard

♦ Jumpers

♦ Resistores

♦ Shield PonteH L298n

### Funcionamento:
O Mindwave recebe informações das ondas cerebrais e as envia para para o arduino em formato de variável, que é usada no código para fazer o carrinho andar e os LEDs acenderem.

### Objetivos:
  
♦ Apresentar a relação entre atividade cerebral e comportamento físico.
  
♦ Oferecer uma experiência educativa sobre neurociência e tecnologia.
  
♦ Demonstrar a infinidade de ideais e funções que podem ser implementadas em projetos visionários.

### Previsão de resultado:

♦ Apresentar a capacidade que a tecnologia possui de facilitar tarefas cotidianas.
