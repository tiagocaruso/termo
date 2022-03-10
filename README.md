# termo
Algorítimo para jogar o jogo Termo com Entropia máxima
O algorítimo é feito para qualquer jogo termo, mas eu usei o site abaixo como referência
https://term.ooo

# Requerimentos:
Eu escrevi o código usando Python 3
Usei os pacotes: numpy, re, Collections que já vem pré-instalados

## Obtendo um corpos da lingua portuguesa:
Vá até o seguinte site:
https://www.linguateca.pt/acesso/ordenador.php

Lá você encontrará vários corpos da lingua portuguesa. 
Faça o download do corpo **Corpus Brasileiro** e salve-o em sua pasta local com o nome $corpus_brasileiro.txt$

## Usando o jupyter Notebook:
O notebook tem 3 partes
* A primeira serve para limpar o corpo e só considerar as palavras de 5 letras mais frequentes
* Na segunda parte há várias funções para se simular o jogo. Elas culminam com o cálculo da palavra que maximiza a entropia esperada
* Na última parte você pode simular o seu próprio jogo entrando qual o sinal que você obteve em cada dica no jogo online, que te dará o corpo de palavra que respeita esse sinal. Com esse novo corpo você poderá calcular qual a palavra que maximiza a entropia esperada ou olhar qual a palavra mais provável de ser o melhor chute no novo corpo.

Boa sorte
