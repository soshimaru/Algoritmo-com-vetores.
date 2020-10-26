# Algoritmo-com-vetores.
algoritmo simples comentado com vetores simples, rápido e explicativo
algoritmo "CoresVetores"
// Função :
// Autor : Léo
// Data : 26/10/2020
// Seção de Declarações 
var
   corAzul: vetor [0..4] de inteiro
   CorVermelha: vetor [0..4] de inteiro
   num: inteiro
   num1: inteiro
   i: inteiro


inicio
    i <- 0   // i inicia com 0
    enquanto i <= 4 faca // vai se repertir 4 vezes

    escreva("Informe quantas cores azul...: ") // escreva as quantidade de cores azuis
    leia(corAzul[i]) // variável que guarda a cor azul
    escreva("Informe quantas cores vermelhas...: ")   // escreva a quantidade de cores vermelhas
    leia(CorVermelha[i])// variável que guarda a cor vermelha
    i <- i + 1 // i guarda i + ¹
    fimenquanto // finaliza o comando enquanto
    
    
    
   i <- 0 // i inicia com 0
   num <- 0  // num inicia com 0
   enquanto i <= 4 faca // vai se repertir 4 vezes
   num <- num + CorAzul[i]
   i <- i + 1   // i guarda i + ¹
   fimenquanto // finaliza o comando enquanto

   i <- 0 // i inicia com 0
   num1 <- 0  // num inicia com 0
   enquanto i <= 4 faca  // vai se repertir 4 vezes
   num1 <- num1 + CorVermelha[i]
   i <- i + 1  // i guarda i + ¹
   fimenquanto  // finaliza o comando enquanto

   escreval("-------------------------------")
   escreval("Cores vermelhas foram...:", num1)
   escreval("-------------------------------")
   escreval("Cores azuis foram....:",  num)
   escreval("-------------------------------")


fimalgoritmo
