# Conceitos de Redes e Cabeamento

## Ping

O comando `ping` é uma ferramenta usada para verificar a conectividade entre dois dispositivos em uma rede. Ao enviar um pacote ICMP (Internet Control Message Protocol) para um endereço IP específico, o comando `ping` espera receber uma resposta do dispositivo de destino. Essa resposta indica que a conexão está ativa e o tempo de resposta (latência) entre os dispositivos.

Exemplo de uso do comando `ping`:

ping www.google.com

## IPCONFIG

O comando `ipconfig` é uma ferramenta de linha de comando usada no sistema operacional Windows para exibir e modificar as configurações de IP de um dispositivo. Ele pode fornecer informações como o endereço IP atual, máscara de sub-rede, gateway padrão e muito mais.

Exemplo de uso do comando `ipconfig`:

ipconfig /all

## DNS

O DNS (Domain Name System) é um sistema que traduz nomes de domínio legíveis em endereços IP numéricos. Em vez de memorizar endereços IP complicados, como 192.168.0.1, podemos usar nomes de domínio, como www.google.com. O DNS resolve esses nomes de domínio em endereços IP para que os dispositivos possam se comunicar uns com os outros na Internet.

## IP

O IP (Internet Protocol) é um protocolo fundamental da Internet que atribui um endereço único a cada dispositivo conectado a uma rede. O endereço IP permite que os dispositivos se comuniquem uns com os outros por meio de uma rede IP. Existem dois tipos principais de endereços IP: IPv4 (exemplo: 192.168.0.1) e IPv6 (exemplo: 2001:0db8:85a3:0000:0000:8a2e:0370:7334). O IPv4 é amplamente usado atualmente, mas o IPv6 está se tornando cada vez mais comum para acomodar o crescimento da Internet e a falta de endereços IPv4 disponíveis.

## Padrões TIA T568A e T568B para cabeamento

Os padrões TIA T568A e T568B são padrões de cabeamento estruturado usados para criar cabos Ethernet. Esses padrões definem a ordem dos fios dentro do cabo e como eles são conectados aos conectores RJ-45.

O padrão TIA T568A usa a seguinte ordem de fios nos conectores RJ-45: verde e branco, verde, laranja e branco, azul, azul e branco, laranja, marrom e branco, marrom.

O padrão TIA T568B usa a seguinte ordem de fios nos conectores RJ-45: laranja e branco, laranja, verde e branco, azul, azul e branco, verde, marrom e branco, marrom.

## Cabeamento Cruzado

Em redes locais (LANs), é comum conectar dispositivos de rede diretamente uns aos outros usando cabos Ethernet. Normalmente, usamos cabos Ethernet padrão para conectar um dispositivo a um switch, roteador ou hub de rede. No entanto, às vezes é necessário fazer uma conexão direta entre dois dispositivos sem o uso de um dispositivo intermediário, como um switch.

Para esse tipo de conexão direta, usamos um cabeamento chamado "cabeamento cruzado" (cross-over). Um cabo crossover é um cabo Ethernet especial em que os fios são organizados de forma diferente nos conectores RJ-45 em cada extremidade do cabo.

Em um cabo crossover, as posições dos fios de transmissão (TX) e recepção (RX) são trocadas em uma extremidade do cabo, permitindo que dois dispositivos transmitam e recebam dados diretamente entre si. Isso é necessário porque, em uma conexão direta entre dois dispositivos sem um switch intermediário, normalmente os fios de transmissão de um dispositivo precisam ser conectados aos fios de recepção do outro dispositivo e vice-versa.