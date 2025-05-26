# Comparação de Algoritmos de Ordenação

Este projeto implementa e compara o desempenho de seis algoritmos de ordenação populares em Java: QuickSort, MergeSort, HeapSort, RadixSort, BucketSort e TimSort. O objetivo é analisar a eficiência desses algoritmos ao ordenar um grande conjunto de dados (500.000 números inteiros) em diferentes cenários.

## Descrição

O programa lê 500.000 números inteiros de um arquivo de texto (`dados500_mil.txt`). Em seguida, para cada um dos seis algoritmos de ordenação, ele realiza as seguintes operações:

1.  **Ordenação Crescente:** Ordena os dados em ordem crescente e mede o tempo de execução.
2.  **Ordenação Decrescente:** Ordena os dados em ordem decrescente e mede o tempo de execução.
3.  **Reordenação e Ordenação Crescente:** Embaralha os dados previamente ordenados e, em seguida, ordena-os novamente em ordem crescente, medindo o tempo de execução.

Os resultados de cada ordenação (os dados ordenados) são salvos em arquivos de texto separados na pasta `results`. Os tempos de execução são impressos no console.

## Algoritmos Implementados

* **QuickSort:** Implementação do algoritmo QuickSort.
* **MergeSort:** Implementação do algoritmo MergeSort.
* **HeapSort:** Implementação do algoritmo HeapSort.
* **RadixSort:** Implementação do algoritmo RadixSort (LSD - Least Significant Digit).
* **BucketSort:** Implementação do algoritmo BucketSort.
* **TimSort:** Utiliza a implementação `Arrays.sort()` do Java, que é baseada no TimSort para objetos e um QuickSort dual-pivot para primitivos.

## Estrutura do Projeto
Markdown

# Comparação de Algoritmos de Ordenação

Este projeto implementa e compara o desempenho de seis algoritmos de ordenação populares em Java: QuickSort, MergeSort, HeapSort, RadixSort, BucketSort e TimSort. O objetivo é analisar a eficiência desses algoritmos ao ordenar um grande conjunto de dados (500.000 números inteiros) em diferentes cenários.

## Descrição

O programa lê 500.000 números inteiros de um arquivo de texto (`dados500_mil.txt`). Em seguida, para cada um dos seis algoritmos de ordenação, ele realiza as seguintes operações:

1.  **Ordenação Crescente:** Ordena os dados em ordem crescente e mede o tempo de execução.
2.  **Ordenação Decrescente:** Ordena os dados em ordem decrescente e mede o tempo de execução.
3.  **Reordenação e Ordenação Crescente:** Embaralha os dados previamente ordenados e, em seguida, ordena-os novamente em ordem crescente, medindo o tempo de execução.

Os resultados de cada ordenação (os dados ordenados) são salvos em arquivos de texto separados na pasta `results`. Os tempos de execução são impressos no console.

## Algoritmos Implementados

* **QuickSort:** Implementação do algoritmo QuickSort.
* **MergeSort:** Implementação do algoritmo MergeSort.
* **HeapSort:** Implementação do algoritmo HeapSort.
* **RadixSort:** Implementação do algoritmo RadixSort (LSD - Least Significant Digit).
* **BucketSort:** Implementação do algoritmo BucketSort.
* **TimSort:** Utiliza a implementação `Arrays.sort()` do Java, que é baseada no TimSort para objetos e um QuickSort dual-pivot para primitivos.

## Estrutura do Projeto

trabalho-referente-a-prova-/
├── Trabalho/
│   ├── .vscode/
│   │   └── settings.json
│   ├── bin/
│   │   └── com/mycompany/sortingcomparison/
│   │       └── dados500_mil.txt
│   ├── src/
│   │   └── com/mycompany/sortingcomparison/
│   │       ├── SortingComparison.java
│   │       └── dados500_mil.txt
│   └── README.md
└── results/
├── sorted_BucketSort_asc.txt
├── sorted_BucketSort_desc.txt
├── sorted_BucketSort_reordered_asc.txt
├── sorted_HeapSort_asc.txt
├── sorted_HeapSort_desc.txt
├── sorted_HeapSort_reordered_asc.txt
├── sorted_MergeSort_asc.txt
├── sorted_MergeSort_desc.txt
├── sorted_MergeSort_reordered_asc.txt
├── sorted_QuickSort_asc.txt
├── sorted_QuickSort_desc.txt
├── sorted_QuickSort_reordered_asc.txt
├── sorted_RadixSort_asc.txt
├── sorted_RadixSort_desc.txt
├── sorted_RadixSort_reordered_asc.txt
├── sorted_TimSort_asc.txt
├── sorted_TimSort_desc.txt
└── sorted_TimSort_reordered_asc.txt

## Como Executar

### Pré-requisitos

* Java Development Kit (JDK) instalado (versão 8 ou superior recomendada).

### Passos

1.  **Clone ou Baixe o Repositório:** Obtenha os arquivos do projeto.
2.  **Navegue até a Pasta `src`:** Abra um terminal ou prompt de comando e navegue até o diretório `Trabalho/src`.
3.  **Compile o Código:** Execute o seguinte comando para compilar o arquivo Java. Certifique-se de que o arquivo `dados500_mil.txt` esteja no mesmo diretório ou ajuste o caminho no código.

    ```bash
    javac com/mycompany/sortingcomparison/SortingComparison.java
    ```

4.  **Execute o Programa:** Após a compilação, execute o programa com o seguinte comando (ainda no diretório `Trabalho/src`):

    ```bash
    java com.mycompany.sortingcomparison.SortingComparison
    ```

5.  **Verifique os Resultados:** O programa imprimirá os tempos de execução no console. Os arquivos de texto com os dados ordenados serão criados na pasta `results` (você pode precisar criar esta pasta no mesmo nível que `Trabalho` ou ajustar os caminhos no código para salvá-los em outro local).

## Dataset

O arquivo `dados500_mil.txt` contém 500.000 números inteiros, um por linha, que são utilizados como entrada para os algoritmos de ordenação.

## Resultados

Os arquivos na pasta `results` contêm os 500.000 números ordenados por cada algoritmo e cenário. O nome do arquivo indica o algoritmo usado e o tipo de ordenação (ascendente, descendente ou reordenado ascendente).

## Autores

* **Fernando Alves de Souza** - [FernandoAlves049](https://github.com/FernandoAlves049)
* **Victor Hugo Marques Leite** - [TempestOFC](https://github.com/TempestOFC)
* **Felipe Montalvão Rodrigues** - [Felipemonrod](https://github.com/Felipemonrod)
* **Henrique Ferreira da Silva** - [Kobayashys](https://github.com/Kobayashys)
