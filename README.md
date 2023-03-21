# Trabalho "O caminho guloso": Implementação em C++

O programa receberá através de um arquivo, um número K de matrizes de tamanho NxN, onde ele percorrera as matrizes optando sempre andar para a casa com o maior número.

## Objetivo

O sistema fará a leitura dessas matrizes e logo, começará a partir do ponto [0,0], percorrer as matrizes de forma a sempre escolher o maior número até 1 casa de distância. Ao caminhar pelas matrizes, o programa pode escolher entre 5 direções, sendo elas:  esquerda, diagonal esquerda baixo, baixo, diagonal direita baixo e direita.</p>
Deve-se ressaltar que o código não fará a análise para cima pois, tem como critérios enquanto está andando pelas matrizes, nunca andar para a linha de cima e também, nunca deverá voltar para uma posição que foi percorrida anteriormente.
 
## Arquivos

* ```main.cpp```: Arquivo e função principal do código
* ```Matriz.hpp```: Criação das funções utilizadas;
* ```Matriz.cpp```: Implementação das funções descritas no arquivo hpp;
* ```input.data```: Matrizes a serem utilizadas;
* ```Makefile```: Automatiza processos de compilação;

## Funções

* ```int **criarMatriz(int **matriz, int tam)```: Responsável pela criação e retorno de uma matriz criada através de alocação dinâmica. Passados como parâmetro temos a matriz a ser criada e seu tamanho.
* ```int **limparMatriz(int **matriz, int tam)```: Realiza a limpeza da matrize após a criação de uma alocada dinâmicamente. Passados como parâmetro temos a matriz que será feito a liberação de memória alocada e seu tamanho.
* ```void mostrarCaminho(int **matriz, int tam)```: Mostra ao usuário o caminho percorrido, tendo o número -1 por onde foi passado. Passados como parâmetro temos a matriz que será lida e seu tamanho.
* ```int **int percorrerMatriz(int **matriz, int tam)```: Realiza todas as comparações nas 5 possíveis direções, observando sempre se a posição a ser analisado está dentro dos limites da matriz. Nesta função foi usados vários comandos if para comparação, e foram usadas 2 variáveis auxiliares para salvar a posição da linha e da coluna, até o momento que a caminhada é feita. Passados como parâmetro temos a matriz que será percorrida e seu tamanho.

## Exemplos de compilação

![Matrizes](https://user-images.githubusercontent.com/118322766/226504303-08c27d66-7878-48c5-8f57-3916edfe446f.jpeg)
![CaminhoMatrizes](https://user-images.githubusercontent.com/118322766/226504371-7bec61ef-0753-428b-892d-fccd22eb735c.jpeg)


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
