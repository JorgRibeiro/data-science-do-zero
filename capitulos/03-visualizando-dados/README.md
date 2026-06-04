# Capítulo 03 - Visualizando Dados

## Visão geral

Este capítulo apresenta os primeiros recursos de visualização de dados usados ao longo do livro **Data Science do Zero**.

A proposta é mostrar como gráficos simples ajudam a explorar, comparar e comunicar informações. O foco está no uso do `matplotlib` para criar gráficos de linhas, barras, histogramas e dispersão, além de discutir como escolhas de escala podem mudar a interpretação visual dos dados.

## Objetivo

Organizar anotações, exemplos e experimentos em português para praticar visualizações básicas com Python.

O capítulo também serve para criar uma base visual reutilizável nos próximos notebooks, incluindo uma função auxiliar para salvar figuras geradas localmente em uma pasta do próprio capítulo.

## Assuntos do capítulo

- Introdução ao `matplotlib`.
- Criação de gráficos de linhas.
- Criação de gráficos de barras.
- Uso de barras para representar histogramas.
- Configuração de títulos, rótulos e marcações dos eixos.
- Ajuste manual da escala dos eixos com `plt.axis`.
- Comparação entre gráficos com eixos enganosos e eixos mais adequados.
- Plotagem de múltiplas séries no mesmo gráfico.
- Uso de legenda para diferenciar séries.
- Criação de gráficos de dispersão.
- Anotação de pontos em gráficos com `plt.annotate`.
- Comparação entre eixos não comparáveis e eixos com escala igual.
- Salvamento de figuras com `pathlib.Path` e `plt.savefig`.

## O que foi feito

No notebook [`cap_03.ipynb`](cap_03.ipynb), os exemplos do capítulo foram organizados em células curtas, com comentários em português e figuras salvas localmente.

Foram adicionados subtítulos no início dos principais tópicos para contextualizar o uso de cada tipo de gráfico antes dos exemplos. O notebook começa com um gráfico de linhas simples, passa por gráficos de barras e histogramas, mostra como uma escala mal escolhida pode exagerar diferenças e termina com gráficos de dispersão para comparar pares de variáveis.

## Arquivos do capítulo

- [`cap_03.ipynb`](cap_03.ipynb): notebook principal do capítulo, com anotações, exemplos e visualizações.
- [`README.md`](README.md): resumo do capítulo, objetivos, conceitos principais, links e instruções de execução.
- [`images/fundamentals/`](images/fundamentals/): pasta com as figuras geradas pelo notebook.

## Figuras esperadas

- [`Figura 3-1. Um grafico de linhas simples.png`](images/fundamentals/Figura%203-1.%20Um%20grafico%20de%20linhas%20simples.png): gráfico de linhas relacionando anos e PIB nominal.
- [`Figura 3-2. Um grafico de barras simples.png`](images/fundamentals/Figura%203-2.%20Um%20grafico%20de%20barras%20simples.png): gráfico de barras com filmes e número de Oscars.
- [`Figura 3-3. Criando um histograma com um grafico de barras.png`](images/fundamentals/Figura%203-3.%20Criando%20um%20histograma%20com%20um%20grafico%20de%20barras.png): distribuição de notas agrupadas por decil.
- [`Figura 3-4. Um grafico com um eixo y malandro.png`](images/fundamentals/Figura%203-4.%20Um%20grafico%20com%20um%20eixo%20y%20malandro.png): exemplo de escala do eixo y que exagera uma diferença pequena.
- [`Figura 3-5. O mesmo grafico com um eixo y boa-praca.png`](images/fundamentals/Figura%203-5.%20O%20mesmo%20grafico%20com%20um%20eixo%20y%20boa-praca.png): versão do gráfico anterior com uma escala mais adequada.
- [`Figura 3-6. Varios graficos de linhas com uma legenda.png`](images/fundamentals/Figura%203-6.%20Varios%20graficos%20de%20linhas%20com%20uma%20legenda.png): comparação entre variância, viés ao quadrado e erro total.
- [`Figura 3-7. Um grafico de dispersao entre o numero de amigos e o tempo dedicado ao site.png`](images/fundamentals/Figura%203-7.%20Um%20grafico%20de%20dispersao%20entre%20o%20numero%20de%20amigos%20e%20o%20tempo%20dedicado%20ao%20site.png): dispersão entre número de amigos e minutos diários no site.
- [`Figura 3-8. Um grafico de dispersao com eixos imcomparaveis.png`](images/fundamentals/Figura%203-8.%20Um%20grafico%20de%20dispersao%20com%20eixos%20imcomparaveis.png): gráfico de dispersão com eixos em escalas não comparáveis.
- [`Figura 3-9. O mesmo grafico de dispersao com eixos iguais.png`](images/fundamentals/Figura%203-9.%20O%20mesmo%20grafico%20de%20dispersao%20com%20eixos%20iguais.png): versão com eixos comparáveis usando `plt.axis("equal")`.

## Tópicos importantes

- **Gráficos de linhas**: úteis para mostrar evolução, tendência ou relação ordenada entre valores.
- **Gráficos de barras**: facilitam a comparação entre categorias discretas.
- **Histogramas**: resumem a distribuição de valores numéricos em intervalos.
- **Escala dos eixos**: pode revelar padrões, mas também pode distorcer a percepção quando usada sem cuidado.
- **Legendas**: ajudam a diferenciar múltiplas séries no mesmo gráfico.
- **Gráficos de dispersão**: mostram relações entre duas variáveis numéricas.
- **Anotações**: permitem identificar pontos específicos diretamente no gráfico.
- **Salvamento de figuras**: mantém as visualizações reproduzíveis e disponíveis fora do notebook.

## Principais aprendizados

- Visualizações são ferramentas de exploração e comunicação, não apenas decoração.
- Um gráfico simples pode revelar tendências e comparações com mais clareza do que uma tabela.
- A escolha do tipo de gráfico depende da pergunta feita aos dados.
- Títulos, rótulos e escalas fazem parte da interpretação do gráfico.
- Eixos truncados ou mal configurados podem exagerar diferenças pequenas.
- Comparações visuais entre variáveis podem exigir escalas iguais.

## Resumo

O capítulo introduz visualização de dados com `matplotlib`, começando por gráficos simples e avançando para ajustes de leitura e interpretação. Os exemplos mostram como construir gráficos, nomear eixos, salvar figuras e comparar diferentes formas de apresentar os mesmos dados.

Nesta adaptação, o conteúdo foi organizado em português, com figuras geradas localmente pelo notebook e subtítulos explicativos para facilitar a navegação entre os tópicos.

## Links citados pelo livro

- [matplotlib](http://matplotlib.org/)
- [seaborn](http://www.stanford.edu/~mwaskom/software/seaborn/)
- [D3.js](http://d3js.org/)
- [Bokeh](http://bokeh.pydata.org/)
- [ggplot](https://pypi.python.org/pypi/ggplot)

## Links complementares

- [matplotlib examples](http://matplotlib.org/examples/)
- [matplotlib gallery](http://matplotlib.org/gallery.html)
- [seaborn](http://web.stanford.edu/~mwaskom/software/seaborn/)
- [Código original do capítulo 3](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/visualization.py)

## Observações pessoais

Este capítulo foi tratado como a base visual do projeto. A intenção é manter exemplos pequenos, fáceis de executar e úteis para consultar quando os próximos capítulos precisarem comunicar resultados por meio de gráficos.

Em revisões futuras, vale padronizar os nomes dos arquivos de imagem com acentuação corrigida e nomes mais curtos, para facilitar links e referências no Markdown.

## Como executar

Com o ambiente virtual do projeto ativado e as dependências instaladas, abra o notebook:

```bash
jupyter lab capitulos/03-visualizando-dados/cap_03.ipynb
```

Também é possível abrir o arquivo diretamente pelo VS Code usando a extensão do Jupyter.

## Dependências

Este capítulo usa principalmente:

- Python
- Jupyter
- `matplotlib`
- `collections.Counter`
- `pathlib.Path`
