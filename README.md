# Cálculo Numérico

Coleção das implementações dos diversos algoritmos e funções vistos durante a disciplina de calculo numérico na forma de um único notebook Jupyter facilmente navegável

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
- Exemplos de uso para cada implementação

Você pode ver o [Notebook pre executado](https://github.com/diefesson/ufc-cn/blob/amostras_executadas/src/main.ipynb) com as amostras de código

## Configuração do projeto

Windows

~~~
python -m venv venv
.\venv\Scripts\activate.bat
pip install -r requirements.txt
jupyter-notebook
~~~

Linux

~~~
python -m venv venv
./venv/bin/activate
pip install -r requirements.txt
jupyter-notebook
~~~