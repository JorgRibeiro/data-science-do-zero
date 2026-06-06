# Capítulo 04 - Álgebra linear

## Visão geral

Este capítulo apresenta os fundamentos de álgebra linear usados ao longo de **Data Science do Zero**.

A proposta é implementar operações básicas com vetores e matrizes usando Python puro, para deixar claro o raciocínio matemático por trás de conceitos que aparecem nos próximos capítulos, como distância, similaridade, regressão, gradiente, redes neurais e sistemas de recomendação.

## Objetivo

Organizar anotações, exemplos e experimentos em português para criar uma base prática de álgebra linear aplicada à ciência de dados.

O capítulo também serve como referência para funções reutilizadas em capítulos posteriores, incluindo soma e subtração de vetores, multiplicação por escalar, produto escalar, magnitude, distância e construção de matrizes.

## Assuntos do capítulo

- Representação de vetores como listas de números.
- Soma e subtração elemento a elemento.
- Soma de múltiplos vetores.
- Multiplicação de vetor por escalar.
- Média de vetores.
- Produto escalar.
- Soma dos quadrados.
- Magnitude de um vetor.
- Distância entre vetores.
- Representação de matrizes como listas de listas.
- Cálculo da forma de uma matriz com número de linhas e colunas.
- Acesso a linhas e colunas.
- Construção de matrizes a partir de uma função.
- Criação de matriz identidade.
- Uso de matriz de adjacência para representar amizades.

## O que foi feito

No notebook [`cap_04.ipynb`](cap_04.ipynb), os exemplos do capítulo foram organizados em células executáveis, com comentários em português e verificações simples com `assert`.

Foram implementadas funções fundamentais para manipular vetores e matrizes sem depender de bibliotecas externas de álgebra linear. O notebook também gera figuras para visualizar a soma de vetores e a interpretação geométrica do produto escalar como projeção.

## Arquivos do capítulo

- [`cap_04.ipynb`](cap_04.ipynb): notebook principal do capítulo, com anotações, implementações e visualizações.
- [`README.md`](README.md): resumo do capítulo, objetivos, conceitos principais, links e instruções de execução.
- [`images/fundamentals/`](images/fundamentals/): pasta com as figuras geradas pelo notebook.

## Figuras esperadas

- [`Figura 4-1. Somando dois vetores.png`](images/fundamentals/Figura%204-1.%20Somando%20dois%20vetores.png): visualização da soma de dois vetores no plano.
- [`Figura 4-2. O produto escalar como projecao de vetor.png`](images/fundamentals/Figura%204-2.%20O%20produto%20escalar%20como%20projecao%20de%20vetor.png): interpretação do produto escalar como projeção de um vetor em outro.

## Conceitos principais

- **Vetor**: sequência numérica usada para representar pontos, medidas, parâmetros ou observações.
- **Operações elemento a elemento**: forma de combinar vetores de mesmo tamanho por posição correspondente.
- **Multiplicação por escalar**: operação que altera a escala de um vetor mantendo sua direção relativa.
- **Produto escalar**: medida algébrica que combina dois vetores e aparece em projeções, similaridade, modelos lineares e redes neurais.
- **Magnitude**: comprimento de um vetor, calculado a partir da soma dos quadrados de seus componentes.
- **Distância euclidiana**: distância entre dois vetores, calculada pela magnitude da diferença entre eles.
- **Matriz**: estrutura bidimensional usada para representar dados tabulares, transformações lineares ou relações entre entidades.
- **Matriz identidade**: matriz quadrada que preserva um vetor em multiplicações matriciais.
- **Matriz de adjacência**: representação matricial de conexões em uma rede.

## Principais aprendizados

- Estruturas simples de Python são suficientes para implementar operações essenciais de álgebra linear.
- Muitas operações de ciência de dados dependem de vetores com o mesmo número de componentes.
- O produto escalar conecta a representação algébrica dos vetores com sua interpretação geométrica.
- Distância e magnitude são blocos básicos para estatística, machine learning e otimização.
- Matrizes permitem representar tanto dados organizados em linhas e colunas quanto relações entre elementos.

## Resumo

O capítulo constrói uma pequena caixa de ferramentas de álgebra linear em Python. Primeiro, define vetores e implementa operações como soma, subtração, média, produto escalar, magnitude e distância. Depois, passa para matrizes, mostrando como identificar sua forma, extrair linhas e colunas, criar matrizes por função e construir uma matriz identidade.

Na parte final, a matriz de adjacência reaparece como forma de representar amizades entre usuários, conectando álgebra linear com a modelagem de redes vista desde a introdução. Nesta adaptação, o conteúdo foi documentado em português e acompanhado por figuras geradas localmente pelo notebook.

## Links do capítulo

- [Notebook do capítulo](cap_04.ipynb)
- [Figuras geradas pelo notebook](images/fundamentals/)
- [Código original do capítulo 4](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/linear_algebra.py)

## Links citados pelo livro

- [Linear Algebra, from UC Davis](https://www.math.ucdavis.edu/~linear/)
- [Linear Algebra, from Saint Michael's College](http://joshua.smcvt.edu/linearalgebra/)
- [Linear Algebra Done Wrong](http://www.math.brown.edu/~treil/papers/LADW/LADW.html)
- [SciPy linear algebra module](http://docs.scipy.org/doc/scipy/reference/tutorial/linalg.html)

## Observações pessoais

Este capítulo foi tratado como uma base matemática para o restante do repositório. A intenção é manter as implementações pequenas, explícitas e fáceis de consultar quando os mesmos conceitos reaparecerem em estatística, descida do gradiente e modelos preditivos.

Em revisões futuras, vale padronizar alguns nomes e comentários do notebook para corrigir pequenos erros de digitação, mantendo a compatibilidade com as figuras já salvas.

## Como executar

Com o ambiente virtual do projeto ativado e as dependências instaladas, abra o notebook:

```bash
jupyter lab capitulos/04-algebra-linear/cap_04.ipynb
```

Também é possível abrir o arquivo diretamente pelo VS Code usando a extensão do Jupyter.

## Dependências

Este capítulo usa principalmente:

- Python
- Jupyter
- `matplotlib`
- `math`
- `pathlib.Path`
- `typing`
