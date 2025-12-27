# Como a internet funciona?

## A Linguagem Universal dos Impulsos Elétricos

No nível mais básico, computadores processam apenas **ondas elétricas binárias (0 e 1), chamadas de bits**, que viajam internamente como ondas quadradas (digitais).

>Para o computador conseguir representar algo, como a letra "A", ele precisa **agrupar 8 desses bits, formando o que chamamos de Byte**, a porção mínima para representar uma informação. 

Ou seja, **o computador não entende palavras ou mídias** do jeito que nós entendemos.


## Como uma mensagem cruza o mundo num piscar de olhos?

O sinal digital funciona muito bem dentro do computador, mas ele é **péssimo para viajar por longas distâncias** em sistemas como cabos de telefone ou antenas, que só entendem ondas analógicas.

>Por conta disso, os pacotes de dados viajam entre continentes, **através de cabos de fibra ótica submarinos** que se interligam a outros sistemas de comunicação.

>Para a conversão dos sinais diferentes utiliza-se o *Modem*, que realiza a **modulação (conversão de ondas digitais em analógicas) e a demodulação (processo inverso)**. 

Os roteadores são os dispositivos **responsáveis por decidir a melhor rota para os pacotes de dados**, funcionando como um GPS que desvia o tráfego de *áreas congestionadas*.


## O Remetente e o Destinatário: Modelo Cliente-Servidor

Tudo começa quando **acessamos um site inserindo sua URL** (como https://www.google.com) no navegador. Neste momento, atuamos como **cliente** *solicitanto os dados e/ou serviço* de um servidor.

>Como o computador não entende domínios, o navegador consulta o **DNS (Domain Name System)**, que traduz o **nome do domínio no número de IP real do servidor** onde o site está guardado. 

*Obs: caso o site já tenha sido acessado anteriormente, ele consulta o próprio cache.*

>Ao receber o pedido, **o servidor procura a página solicitada** e envia uma *cópia do documento* (geralmente o arquivo `index.html`) em pequenos pacotes de volta para o seu computador. 

O navegador recebe esses pacotes e **começa a montar o site na tela.** Se o site tiver fotos e vídeos, ele faz **novos pedidos ao servidor** até que tudo apareça pronto para você.

![Modelo cliente-servidor](img/infg_cliente_servidor.png)

<!-- Perguntas (SRS):

01. Qual é a linguagem fundamental que um computador entende, resumida a apenas dois estados?

Resposta: Sinais elétricos representados por 0s e 1s, conhecidos como bits (dígitos binários).


02. Os sinais elétricos que representam os bits dentro de um computador são também conhecidos como onda _____.

Resposta: Quadrada ou Digital.


03. Um conjunto de 8 bits, que é unidade básica de dados digitais, é chamado de _____.

Resposta: Byte


04. Ao contrário da crença popular, qual é o principal meio físico para a maioria das transmissões intercontinentais de dados?

Resposta: Cabos de fibra óptica submarinos. Transmitem mais de 95% de todos os dados mundiais.


05. O processo de converter um sinal digital (onda quadrada) em um sinal analógico (onda senoidal) é chamado de _____.

Resposta: Modulação


06. Qual aparelho realiza as funções de modulação e demodulação para permitir a comunicação entre redes?

Resposta: MODEM (MOdulador/DEModulador).


07. Qual é a função principal de um roteador na internet?

Resposta: Decidir a melhor rota para os pacotes de dados viajarem pela rede, evitando congestionamentos.


08.No modelo de comunicação da internet, quais são os papeis do 'cliente' e do 'servidor'?

Resposta: O cliente é o dispositivo que solicita um serviço ou conteúdo, como acessar um site. Já o servidor é a máquina que armazena e fornece os dados solicitados.


09. O DNS traduz um _____ legível por humanos (como google.com) para o _____ correspondente do servidor.

Resposta: dominio, endereço IP


10. Quando você digita uma URL no navegador, qual é o primeiro local verificado para encontrar o IP correspondente?

Resposta: O cache do próprio navegador.
-->