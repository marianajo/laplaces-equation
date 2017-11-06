# Solução Numérica da Equação de Laplace
Este trabalho foi desenvolvido como trabalho final da disciplina de Eletromagnetismo I, turma do segundo semestre de 2017, noturno, Professor Fernando Garcia, do Instituto de Física da Universidade de São Paulo.

O objetivo do trabalho é desenvolver soluções numéricas para a Equação de Laplace, utilizando métodos de relaxamento. Os métodos desenvolvidos são o Método de Jacobi e o Método de Gauss-Seidel.

O projeto até o momento é separado em duas *branches*: "paper" para o desenvolvimento do relatório e "code" para o desenvolvimento do Jupyter Notebook com a solução. Esta separação foi feita para que no final do trabalho possa-se reorganizar os commits e tornar o projeto linear, onde a história faça sentido.

O link direto para o pdf com a implementação dos métodos está [aqui](https://github.com/marianajo/laplaces-equation/blob/code/code/LaplacesEquation.pdf).

## Dependências
A utilização da distribuição [Anaconda](https://www.continuum.io/downloads) é recomendada.

- Python3
- Jupyter Notebook
- matplotlib
- seaborn
- numpy
- pandas
- itertools

## Como rodar o projeto
Navegue até a pasta do projeto e rode `jupyter notebook` para iniciar o servidor Jupyter. Isto iniciará uma sessão em seu browser. Navegue até a pasta `/code` e abra o arquivo `solution.ipynb`.
