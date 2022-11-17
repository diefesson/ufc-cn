# Cálculo Numérico

Coleção das implementações dos diversos algoritmos e funções vistos durante a disciplina de calculo numérico na forma de um único notebook Jupyter facilmente navegável

**AVISO PARA PROFESSOR:** as branches de prova são [prova_1](https://github.com/diefesson/ufc-cn/blob/prova_1/src/main.ipynb) e [prova_2](https://github.com/diefesson/ufc-cn/blob/prova_2/src/main.ipynb)

Recursos:

- Calculo do erro
- Derivação numérica
- Métodos iterativos e suas condições de parada
  - Bisseção
  - Falsa posição
  - Ponto fixo
  - Newton-Raphson
- Solução de sistemas lineares
  - Gauss
  - Solução retroativa
  - Gauss-Seidel
  - Gauss-Jacob
- Interpolação
  - Polinômio de Lagrange
  - Polinômio de Newton
  - Spline Quadrática
- Ajuste de curva
  - Mínimos quadrados
- Geração de formulas Latex
- Exemplos de uso para cada implementação

Você pode ver o [Notebook pre executado](https://github.com/diefesson/ufc-cn/blob/exemplos_executados/src/main.ipynb) com as amostras de código

## Configuração do projeto

O projeto foi migrado para fazer uso do gerenciador de ambientes virtuais [pipenv](https://pypi.org/project/pipenv), substituindo o venv, exercendo maior controle sobre as dependências e evitando que coisas quebrem misteriosamente 🙃.

Instale o pipenv.

~~~~
pip install pipenv
~~~~

Crie o ambiente virtual e instale as dependências do projeto

~~~~
pipenv install --dev
~~~~

É recomendada a utilização do VS Code com a extensão [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

Mas alternativamente, pode ser criada uma instância do Jupyter Lab

~~~~
pipenv run jupyter lab
~~~~
