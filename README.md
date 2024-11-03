# Script-Mikrotik-Monitor-Voltagem
Esse Script tem como Objetivo ficar monitorando voltagem na RB se a voltagem abaixar de 20 Volts, o script desativa as portas 

Voltagem Baixa= $voltage - PoE na Ether 2,3 desativado  

mas se a voltagem ficar acima de 24 Volts ele religa os POE das Ether 2 e 3. 

Esse Script é para aquelas Router OS da Mikrotik que tem POE ativo nas Portas 

Ex:  RB 960 PGS. 

Tem utilidade caso a bateria venha ficar baixa na madrugada, ela desliga uma parte dos equipamentos para não acabar com a carga da Bateria.  

Só colocar para rodar em system --> Scheduler a cada 1 Minuto, que ele vai ficar checando se esta tudo em ordem com carga da bateria.
