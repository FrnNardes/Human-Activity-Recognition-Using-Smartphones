# Aplicando K-Means Clustering no DataFrame Human Activity Recognition Using Smartphones

Este projeto implementa o algoritmo de clustering K-Means, que é amplamente utilizado para dividir um conjunto de dados em K grupos (ou clusters) com base em características semelhantes. O objetivo é demonstrar como o K-Means pode ser aplicado em dados reais e como o processo de treinamento e visualização dos resultados pode ser realizado.

## Sumário

- [Visão Geral](#visão-geral)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação](#instalação)
- [Uso](#uso)
- [Exemplo de Execução](#exemplo-de-execução)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Autores](#autores)
- [Agradecimentos](#agradecimentos)

## Visão Geral

Este projeto implementa o algoritmo K-Means para realizar clustering em um conjunto de dados. Para isso, iremos utilizar o DataFrame Human Activity Recognition Using Smartphones, que recolheu uma ampla variedade de dados de sensores anexados em 30 pessoas que realizaram diversos movimentos, como sentar, levantar, deitar, etc. O algoritmo divide os dados em clusters, otimizando as distâncias entre os pontos de dados e seus centros de clusters. Ele é útil em várias áreas, como análise de dados, segmentação de clientes, e redução de dimensionalidade.

O código é escrito em Python e utiliza a biblioteca **NumPy** e **Pandas** para manipulação de dados, **Matplotlib** e **Seaborn** para visualização gráfica e **Scikit_learn** para treinar o modelo. O objetivo deste projeto é fornecer uma implementação simples e eficaz do K-Means, que pode ser facilmente adaptada a diferentes tipos de dados.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **NumPy**: Biblioteca para manipulação de arrays e operações matemáticas.
- **Matplotlib**: Biblioteca para visualização de gráficos.
- **Scikit-learn (opcional)**: Para comparar a implementação com a solução da biblioteca.

## Instalação

1. **Clone o repositório**:

```bash
git clone https://github.com/fernando-nardes/k-means-clustering.git
