# 🚀 Calculadora de Partidas Rankeadas

Este projeto é uma solução para o desafio "Calculadora de Partidas Rankeadas" proposto pela DIO. O objetivo é criar uma função que calcula o saldo de vitórias de um jogador e determina seu nível de rank.

## 🎯 Desafio Proposto

### Objetivo:

Criar uma função que recebe como parâmetro a quantidade de vitórias e derrotas de um jogador. O saldo de Rankeadas é calculado pela fórmula: `vitórias - derrotas`.

Com base na quantidade de **vitórias**, o nível do jogador é determinado da seguinte forma:

-   Menos de 10 vitórias: **Ferro**
-   Entre 11 e 20 vitórias: **Bronze**
-   Entre 21 e 50 vitórias: **Prata**
-   Entre 51 e 80 vitórias: **Ouro**
-   Entre 81 e 90 vitórias: **Diamante**
-   Entre 91 e 100 vitórias: **Lendário**
-   101 ou mais vitórias: **Imortal**

### Saída Esperada:

Ao final, a função deve retornar uma mensagem no seguinte formato:
`"O Herói tem de saldo de **{saldoVitorias}** está no nível de **{nivel}**"`

## 🛠️ Tecnologias Utilizadas

-   JavaScript

## 📂 Como usar o projeto

1.  Clone o repositório.
2.  Abra o arquivo `index.js`.
3.  Altere os valores das variáveis `playerVictories` e `playerDefeats` para testar diferentes cenários.
4.  Para ver o resultado, você pode usar `console.log(lastRank)` no final do arquivo e executá-lo com Node.js (`node index.js`).
