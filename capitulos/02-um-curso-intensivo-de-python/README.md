# Capítulo 02 - Um Curso Intensivo de Python

## Visão geral

Este capítulo apresenta uma revisão prática dos principais recursos de Python usados ao longo do livro **Data Science do Zero**.

A proposta é consolidar a base da linguagem antes de avançar para álgebra linear, estatística, probabilidade e machine learning. O foco está nos elementos que aparecem com frequência em ciência de dados: estruturas de dados, funções, módulos, fluxo de controle, iteração, aleatoriedade, expressões regulares e anotações de tipo.

## Objetivo

Organizar anotações, exemplos e experimentos em português para formar uma referência rápida de Python aplicada aos próximos capítulos.

O capítulo também serve para revisar a sintaxe essencial da linguagem e criar familiaridade com padrões usados nos notebooks seguintes, sem copiar diretamente o código original do livro.

## Assuntos do capítulo

- Zen do Python e estilo de código.
- Ambientes virtuais e organização do ambiente de execução.
- Formatação por indentação e uso de espaços em branco.
- Importação de módulos e bibliotecas.
- Definição de funções, argumentos padrão e funções anônimas.
- Strings, concatenação, strings brutas e f-strings.
- Tratamento de exceções.
- Listas, fatiamento, pertencimento e mutabilidade.
- Tuplas, desempacotamento e retorno múltiplo.
- Dicionários, chaves, valores e acesso seguro com `get`.
- `Counter`, `defaultdict` e estruturas auxiliares de `collections`.
- Conjuntos e operações com valores únicos.
- Fluxo de controle com condicionais e laços.
- Veracidade de valores em expressões condicionais.
- Ordenação com `sorted` e `sort`.
- Compreensões de listas, dicionários e conjuntos.
- Testes simples com `assert`.
- Classes, objetos e métodos.
- Iteráveis, geradores e `yield`.
- Aleatoriedade com o módulo `random`.
- Expressões regulares com `re`.
- Uso de `zip`, desempacotamento, `*args` e `**kwargs`.
- Anotações de tipo com `typing`.

## O que foi feito

No notebook [`cap_02.ipynb`](cap_02.ipynb), os principais tópicos do capítulo foram organizados em células curtas, com exemplos executáveis e comentários em português.

Foram adicionados subtítulos explicativos no início dos tópicos para contextualizar cada assunto antes dos exemplos. O notebook funciona como uma revisão guiada da linguagem, com foco nos recursos que serão reutilizados nas implementações matemáticas e estatísticas dos capítulos seguintes.

## Arquivos do capítulo

- [`cap_02.ipynb`](cap_02.ipynb): notebook principal do capítulo, com anotações, exemplos e experimentos de Python.
- [`README.md`](README.md): resumo do capítulo, objetivos, conceitos principais, links e instruções de execução.

## Figuras esperadas

Este capítulo não possui figuras esperadas no momento.

Como o conteúdo é uma revisão da linguagem Python, os exemplos são textuais e executáveis no notebook. Caso algum exercício futuro gere visualizações, elas devem ser salvas em uma pasta `images/` dentro deste capítulo e listadas aqui.

## Tópicos importantes

- **Indentação**: em Python, blocos de código são definidos por espaços, não por chaves.
- **Funções**: permitem encapsular lógica e reutilizar operações ao longo do projeto.
- **Estruturas de dados**: listas, tuplas, dicionários e conjuntos formam a base para representar dados.
- **Coleções especializadas**: `Counter` e `defaultdict` simplificam contagens e agrupamentos.
- **Compreensões**: criam coleções de forma compacta a partir de transformações e filtros.
- **Iteradores e geradores**: permitem produzir valores sob demanda, sem carregar tudo em memória.
- **Aleatoriedade**: útil para simulações, amostragens e experimentos probabilísticos.
- **Expressões regulares**: ajudam a buscar e extrair padrões em texto.
- **Anotações de tipo**: documentam expectativas de entrada e saída, melhorando a leitura do código.
- **Asserções**: verificam hipóteses simples e ajudam a detectar erros durante o desenvolvimento.

## Principais aprendizados

- Python usa sintaxe concisa, mas depende bastante de organização e legibilidade.
- Dominar estruturas de dados simples é essencial para implementar algoritmos de ciência de dados.
- Funções, módulos e classes ajudam a organizar código conforme os exemplos ficam maiores.
- Muitas tarefas comuns envolvem contar, agrupar, ordenar, filtrar e transformar coleções.
- Geradores e iteráveis são importantes para lidar com sequências de forma eficiente.
- Anotações de tipo não mudam a execução do código, mas tornam a intenção mais clara.

## Resumo

O capítulo funciona como uma ponte entre a introdução prática do livro e os capítulos técnicos seguintes. Em vez de aprofundar a linguagem inteira, ele seleciona os recursos de Python mais úteis para acompanhar as implementações de ciência de dados feitas do zero.

Nesta adaptação, o conteúdo foi organizado em português e estruturado como material de consulta. Cada tópico apresenta uma breve explicação e exemplos voltados para leitura, experimentação e reaproveitamento nos próximos capítulos.

## Links citados pelo livro

- [Python](http://python.org)
- [Anaconda](https://store.continuum.io/cshop/anaconda/)
- [pip](https://pypi.python.org/pypi/pip)
- [IPython](http://ipython.org/)
- [The Zen of Python](http://legacy.python.org/dev/peps/pep-0020/)
- [Tutorial oficial de Python](https://docs.python.org/2/tutorial/)
- [Tutorial oficial de IPython](http://ipython.org/ipython-doc/2/interactive/tutorial.html)
- [IPython videos and presentations](http://ipython.org/videos.html)
- [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do)

## Observações pessoais

Este capítulo foi tratado como uma base de consulta para o restante do repositório. A intenção é revisar Python com exemplos pequenos e manter o notebook fácil de percorrer quando algum conceito reaparecer nos capítulos seguintes.

Alguns títulos do notebook preservam anotações feitas durante o estudo. Em revisões futuras, vale padronizar a ortografia dos tópicos e ampliar os exemplos que forem mais usados nos capítulos matemáticos.

## Como executar

Com o ambiente virtual do projeto ativado e as dependências instaladas, abra o notebook:

```bash
jupyter lab capitulos/02-um-curso-intensivo-de-python/cap_2.ipynb
```

Também é possível abrir o arquivo diretamente pelo VS Code usando a extensão do Jupyter.

## Dependências

Este capítulo usa principalmente:

- Python
- Jupyter
- `collections.Counter`
- `collections.defaultdict`
- `random`
- `re`
- `typing`
