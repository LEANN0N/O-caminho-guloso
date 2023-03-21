# Trabalho "O caminho guloso": Implementação em C++

O programa receberá através de um arquivo, um número K de matrizes de tamanho NxN, onde ele percorrera as matrizes optando sempre andar para a casa com o maior número.

## Objetivo

O sistema fará a leitura dessas matrizes e logo, começará a partir do ponto [0,0], percorrer as matrizes de forma a sempre escolher o maior número até 1 casa de distância. Ao caminhar pelas matrizes, o programa pode escolher entre 5 direções, sendo elas:  esquerda, diagonal esquerda baixo, baixo, diagonal direita baixo e direita.</p>
Deve-se ressaltar que o código não fará a análise para cima pois, tem como critérios enquanto está andando pelas matrizes, nunca andar para a linha de cima e também, nunca deverá voltar para uma posição que foi percorrida anteriormente.
 
## Arquivos

* ```main.cpp```: Função principal do código
* ```Matriz.hpp```: Criação das funções utilizadas;
* ```Matriz.cpp```: Implementação das funções descritas no arquivo hpp;
* ```input.data```: Matrizes a serem utilizadas;
* ```Makefile```: Automatiza processos de compilação;

## Funções



## Exemplos de compilação



## Compilação e Execução

Esse código possui um arquivo Makefile que realiza todo o procedimento de compilação e execução. Para tanto, temos as seguintes diretrizes de execução:


| Comando                |  Função                                                                                           |                     
| -----------------------| ------------------------------------------------------------------------------------------------- |
|  `make clean`          | Apaga a última compilação realizada contida na pasta build                                        |
|  `make`                | Executa a compilação do programa utilizando o gcc, e o resultado vai para a pasta build           |
|  `make run`            | Executa o programa da pasta build após a realização da compilação                                 |


# Contato

✉️ <i>leanndrosousac@gmail.com</i>
</a>
