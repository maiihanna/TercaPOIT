# TercaPOIT

Repositório que abriga o código necessário para que um LED pisque por meio de programação na placa Open Source Arduino MEGA

Participantes e suas funções:

Enzo - Apagar o LED e Organizar Git

Mai - Porta do LED e Montagem de Circuito

Mateus - Simulação

Sofia - Supervisão

Gabriel - Timer

Guilherme - Saida


Ordem de mensagens e comandos no Git:

Primeiramente salve o arquivo no File>Save All

Escreva: git add --All

Escreva: git commit -m "sua mudança ai"

Escreva: git push

E este é o processo de salvamento

Comportamento do código:

O LED irá se acender e se manterá aceso por 1,5 segundos. Ao fim dos 1, segundos o LED irá apagar e se manterá apagado por 1,5 segundos.
Esse ciclo se repetirá até que a placa seja reiniciada ou que a energia pare de ser fornecida.