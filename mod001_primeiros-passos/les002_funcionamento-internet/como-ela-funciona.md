# Como a internet funciona?

## A Linguagem Universal dos Impulsos Elétricos

No nível mais básico, computadores processam apenas **ondas elétricas binárias (0 e 1), chamadas de bits**, que viajam internamente como ondas quadradas (digitais).

>Para o computador conseguir representar algo, como a letra "A", ele precisa **agrupar 8 desses bits, formando o que chamamos de Byte**, a porção mínima para representar uma informação.

Ou seja, **o computador não entende palavras ou mídias** do jeito que nós entendemos.

## Como uma mensagem cruza o mundo num piscar de olhos?

O sinal digital funciona muito bem dentro do computador, mas ele é **péssimo para viajar por longas distâncias** em sistemas como cabos de telefone ou antenas, que só entendem ondas analógicas.

Por conta disso, os pacotes de dados viajam entre continentes, **através de cabos de fibra ótica submarinos** que se interligam a outros sistemas de comunicação.

>Para a conversão dos sinais diferentes utiliza-se o *Modem*, que realiza a **modulação (conversão de ondas digitais em analógicas) e a demodulação (processo inverso)**.

Os roteadores são os dispositivos **responsáveis por decidir a melhor rota para os pacotes de dados**, funcionando como um GPS que desvia o tráfego de *áreas congestionadas*.

## O Remetente e o Destinatário: Modelo Cliente-Servidor

Tudo começa quando **acessamos um site inserindo sua URL** (como <https://www.google.com>) no navegador. Neste momento, atuamos como **cliente** *solicitanto os dados e/ou serviço* de um servidor.

>Como o computador não entende domínios, o navegador consulta o **DNS (Domain Name System)**, que traduz o **nome do domínio no número de IP real do servidor** onde o site está guardado.

*Obs: caso o site já tenha sido acessado anteriormente, ele consulta o próprio cache.*

>Ao receber o pedido, **o servidor procura a página solicitada** e envia uma *cópia do documento* (geralmente o arquivo `index.html`) em pequenos pacotes de volta para o seu computador.

O navegador recebe esses pacotes e **começa a montar o site na tela.** Se o site tiver fotos e vídeos, ele faz **novos pedidos ao servidor** até que tudo apareça pronto para você.

![Modelo cliente-servidor](img/infg-cliente-servidor.png)

<!-- Perguntas (SRS):

01.  O computador é um equipamento eletrônico que processa informações em formato binário. Em circuitos digitais, como os sinais binários (0 e 1) são representados fisicamente?

Resposta: Ondas quadradas

02. Na computação, os múltiplos de medidas como o Kilobyte não seguem o padrão decimal de 1000 unidades. Por que a referência de cálculo é o número 1024?

Resposta: Porque o sistema binário utiliza potências de base 2 (2^10)

03. Qual é o principal meio físico responsável pela maioria das transmissões intercontinentais de dados na internet?

Resposta: Cabos de fibra óptica submarinos.

04. Complete a lacuna: O dispositivo responsável por realizar modulação e demodulação de sinais é chamado de ______.

Resposta: MODEM.

05. Sobre a função de um roteador na internet, selecione as alternativas corretas:

A) Determinar a melhor rota para pacotes de dados
B) Conectar diferentes redes entre si
D) Encaminhar pacotes entre redes diferentes

06. Sobre o modelo cliente-servidor, analise as afirmações:

I. O cliente é responsável por solicitar serviços ou recursos.
II. O servidor responde às requisições enviando dados ou executando serviços.

07.  O DNS traduz um _____ legível por humanos (como google.com) para o _____ correspondente do servidor.

Resposta: dominio, endereço IP

08.  Quando você digita uma URL no navegador, qual é normalmente o primeiro local verificado para encontrar o endereço IP correspondente?

Resposta: Cache do navegador
-->
