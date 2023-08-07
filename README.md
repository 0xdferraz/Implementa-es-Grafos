# Implementação Grafo Não Direcionado

Esse projeto em Python apresenta a implementação de Grafos Não Direcionados utilizando listas de adjacência. Além disso, ele contém funções para realizar operações com o grafo, como adicionar e remover vértices e arestas, verificar a existência de ciclo euleriano e encontrar um ciclo euleriano no grafo. Essa implementação foi desenvolvida como parte do estudo realizado na disciplina de Grafos e Algoritmos Computacionais.

## Estruturas de Dados

O código consiste em duas classes principais:

### `Vertice`

A classe `Vertice` representa um vértice do grafo e possui os seguintes atributos:

- `conexoes`: Lista dos vértices adjacentes (vizinhos) ao vértice atual.
- `valido`: Indica se o vértice está ativo no grafo ou foi removido.

### `Grafo`

A classe `Grafo` representa o grafo e contém os seguintes atributos:

- `vG`: Número de vértices existentes no grafo.
- `l_adj`: Lista de adjacência que armazena os vértices do grafo.

## Principais Funções

O código contém diversas funções para manipulação do grafo:

- `add_aresta(v_1, v_2)`: Adiciona uma aresta entre os vértices `v_1` e `v_2`.
- `del_aresta(v_1, v_2)`: Remove a aresta entre os vértices `v_1` e `v_2`.
- `add_vertice()`: Adiciona um novo vértice ao grafo.
- `del_vertice(v)`: Remove o vértice `v` do grafo, assim como suas arestas adjacentes.
- `ciclo_euleriano()`: Verifica se o grafo possui ciclo euleriano.
- `hierholzer()`: Encontra e retorna um ciclo euleriano no grafo, caso exista.

## Exemplos

O código inclui três exemplos de grafos (`G`, `H` e `K`) criados manualmente. Para cada exemplo, é realizada uma série de operações, como adição e remoção de vértices e arestas, verificação de ciclos eulerianos e impressão dos grafos. Além disso, o repositório contém imagens e um Notebook do Google Colab para ilustrar melhor o funcionamento dessa implementação.

## Como Utilizar

Basta executar o código Python localmente ou no Google Colab e verificar para ver as informações sobre os grafos criados e as operações realizadas.
