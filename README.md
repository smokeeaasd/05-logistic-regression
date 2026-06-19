# machine_learn_0401

Projeto que apresenta a implementação de um modelo de **Regressão Logística** desenvolvido do zero (from scratch) para resolver um problema de classificação binária: a predição de sobreviventes do desastre do Titanic.

## Conteúdo

* **titanic.csv**: Dataset contendo informações dos passageiros (classe, sexo, idade, tarifa, etc.) e o rótulo de sobrevivência.
* **regressao_logistica.ipynb**: Notebook detalhado com a implementação algorítmica completa. O projeto abrange:
    - **Leitura e Tratamento de Dados**: Carregamento via CSV e limpeza de valores nulos.
    - **Pré-processamento**: Transformação de variáveis categóricas (como sexo) e normalização de recursos (features).
    - **Otimização**: Implementação da função Sigmoide e do algoritmo de **Gradiente Descendente** para ajuste dos pesos ($\\beta$).
    - **Avaliação**: Cálculo da acurácia do modelo após o treinamento por múltiplas épocas.

## Tecnologias e Bibliotecas

As ferramentas essenciais deste projeto são:

* **Python 3**: Linguagem de programação.
* **NumPy**: Operações matriciais e cálculos matemáticos otimizados.
* **CSV**: Manipulação direta do arquivo de dados.
* **Jupyter Notebook**: Ambiente para execução e visualização do fluxo de treinamento.

## Como começar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/smokeeaasd/logistic-regression.git
    ```
2.  Certifique-se de que o arquivo `titanic.csv` está na mesma pasta que o notebook.
3.  Instale o NumPy:
    ```bash
    pip install numpy
    ```
4.  Execute o notebook:
    - Abra o `regressao_logistica.ipynb` e acompanhe a evolução do custo (Cost) ao longo das épocas de treinamento.


