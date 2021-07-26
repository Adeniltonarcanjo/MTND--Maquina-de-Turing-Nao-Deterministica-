# MTND--Maquina-de-Turing-Nao-Deterministica-
Algoritimo representação de uma Máquina de Turing Não Dterministica (MTND) da matéria de Teoria da COmputação do curso de Engenharia da Computação da UFRB 

#Discente: Adenilton Morais Arcanjo 


# Introdução 


A Máquina de Turing explicitada por Alan Mathison Turing, como um dispositivo lógico capaz de ler, escrever e apagar símbolos binários em uma fita de comprimento ilimitado e dividida por quadros de igual tamanho.  Uma cabeça de leitura/gravação se moveria em qualquer direção ao longo da fita, um quadrado por vez, e uma unidade de controle poderia interpretar uma lista de instruções simples, movendo‐se para a direita ou esquerda. Esse conceito de máquina teve uma importância fundamental no desenvolvimento de áreas de computabilidade, teoria dos autômatos formais e análise de algoritmos(Botelho, 2006).

EEste trabalho é pré-requisito como uma atividade avaliativa da matéria de Teoria da Computação do curso de Engenharia da Computação da UFRB. O trabalho consiste na implementação de um algoritimo que simule uma maquina de Turing Não Determinista.

# Especificação do trabalho 


## Descrição
Implemente um algoritmo que simule uma Máquina de Turing Não Determinista. A entrada
consiste da especificação de uma MTND e de um conjunto de palavras. A saída consiste de uma
lista indicando ‘S’ caso a MTND reconheça a palavra em questão e ‘N’ caso contrário.

## Obsservações:
1. Leitura e escrita na entrada/saída padrão.
2. Qualquer divergência na saída com relação ao formato especificado implicará em nota zero.
3. A implementação não pode fazer uso de recursão.
4. No código fonte, você deve documentar como você gerenciou o não determinismo.
5. Critério de reconhecimento: parada em estado final e inexistência de transição.

## Entrada
Na primeira linha, há uma lista de estados. Na segunda linha, há o alfabeto de entrada. Na terceira
linha, há o alfabeto da fita. Na quarta linha, há o símbolo especial que limita a fita à esquerda. Na
quinta linha, há o símbolo branco da fita. Na sexta linha, há o número total n de transições. Para
cada uma das n linhas seguintes, há uma quíntupla <a, b, c, d, e> onde ‘a’ é o estado de origem, ‘b’
é o caractere a ser lido, ‘c’ é o estado de destino, ‘d’ é o símbolo a ser escrito e, por fim, ‘e’ é a
direção, imóvel (I), esquerda (E) e direita (D). Em seguida, há um caractere informando o estado
inicial. Em seguida, há uma lista de estados finais. Por fim, há uma lista de palavras de teste a ser
reconhecida. Os itens da listas serão separados por espaço em branco. A palavra vazia é
representada por *.

##Saída
Seu programa deve imprimir para cada palavra de teste ‘S’ se a MTND reconhece a palavra ou ‘N’
caso contrário.

## Exemplo


