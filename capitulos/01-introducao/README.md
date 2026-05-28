# Capítulo 01 - Introdução

## Visão geral

Este capítulo apresenta a ideia geral do livro por meio da **DataSciencester**, uma rede social fictícia usada para praticar conceitos básicos de ciência de dados com Python.

A proposta é mostrar, desde o início, como dados simples podem ser organizados, explorados e transformados em perguntas úteis. O capítulo funciona como uma primeira visão prática do tipo de raciocínio usado ao longo do livro: modelar dados, calcular métricas, encontrar padrões e gerar visualizações.

## Assuntos do capítulo

- Representação de usuários e relações de amizade.
- Construção de uma rede social simples em Python.
- Identificação de usuários mais conectados.
- Cálculo de grau de conexão em uma rede.
- Busca por amigos de amigos.
- Uso de interesses em comum para sugerir conexões.
- Agrupamento de dados com `defaultdict`.
- Contagem de ocorrências com `Counter`.
- Relação entre salário e anos de experiência.
- Criação de visualizações simples com `matplotlib`.
- Extração de tópicos recorrentes a partir de interesses textuais.

## O que foi feito

No notebook `cap_1.ipynb`, foi criada uma versão prática da rede fictícia **DataSciencester**.

Foram definidos usuários, pares de amizade e estruturas auxiliares para representar a rede. A partir disso, o capítulo calcula quantos amigos cada usuário possui, ordena os usuários mais conectados e gera visualizações da rede.

Também foram implementadas funções para encontrar amigos de amigos, identificar usuários com interesses parecidos e contar quais termos aparecem com mais frequência nos interesses cadastrados.

Além da parte de rede social, o capítulo explora uma pequena base de salários e tempo de experiência, agrupando os dados por faixas de experiência e calculando médias salariais por grupo.

## Arquivos do capítulo

- `cap_1.ipynb`: notebook principal do capítulo, com anotações, exemplos, implementações e visualizações.
- `images/fundamentals/rede_datasciencester.png`: visualização inicial da rede fictícia.
- `images/fundamentals/rede_datasciencester_por_grau.png`: visualização da rede com nós dimensionados pelo grau de conexão.
- `images/fundamentals/salario_por_experiencia.png`: gráfico relacionando salário e anos de experiência.

## Tópicos importantes

- **Dados como estruturas Python**: o capítulo usa listas, dicionários e tuplas para representar usuários, amizades, interesses e salários.
- **Grau de conexão**: número de amigos de cada usuário, usado como uma métrica simples de importância na rede.
- **Amigos de amigos**: primeira ideia de recomendação baseada na estrutura da rede.
- **Interesses em comum**: alternativa para sugerir conexões a partir de afinidade temática.
- **Agrupamento de dados**: uso de `defaultdict(list)` para organizar valores relacionados.
- **Contagem de frequência**: uso de `Counter` para descobrir interesses ou palavras mais recorrentes.
- **Visualização exploratória**: uso de gráficos para tornar padrões mais fáceis de perceber.

## Principais aprendizados

- Mesmo dados pequenos podem gerar perguntas interessantes.
- Uma rede social pode ser modelada com estruturas simples de Python.
- Métricas básicas, como número de conexões, já ajudam a identificar padrões.
- Recomendações podem surgir tanto da estrutura da rede quanto de atributos dos usuários.
- Agrupar, contar e ordenar dados são operações fundamentais em ciência de dados.
- Visualizações ajudam a validar e comunicar melhor os resultados.

## Resumo

O capítulo introduz ciência de dados de forma prática, usando uma rede social fictícia como cenário. A partir de dados simples sobre usuários, amizades e interesses, são criadas estruturas para responder perguntas como: quem tem mais conexões, quem pode conhecer quem e quais usuários compartilham interesses.

Depois, o capítulo amplia a exploração para dados de salário e experiência, mostrando como agrupar informações e calcular médias pode revelar padrões. Também aparece uma primeira forma de trabalhar com texto, contando palavras recorrentes nos interesses dos usuários.

Nesta adaptação, o conteúdo foi organizado em português, com implementações próprias no notebook e geração de imagens locais para documentar melhor os exemplos.

## Links citados pelo livro

- ~~[OkCupid Questions](http://blog.okcupid.com/index.php/the-best-questions-for-first-dates/)~~
- ~~[Facebook on coordinated migration](https://www.facebook.com/notes/facebook-data-science/coordinated-migration/10151930946453859)~~
- ~~[Facebook on NFL fandom](https://www.facebook.com/notes/facebook-data-science/nfl-fans-on-facebook/10151298370823859)~~
- [Target's predictive modeling](http://www.nytimes.com/2012/02/19/magazine/shopping-habits.html)
- ~~[Making government more effective](http://www.marketplace.org/topics/tech/beyond-ad-clicks-using-big-data-social-good)~~
- ~~[Helping homelessness](http://dssg.io/2014/08/20/paths-homelessness.html)~~
- ~~[Improving public health](https://plus.google.com/communities/109572103057302114737)~~

## Observações pessoais

Este capítulo foi tratado como uma introdução prática ao estilo do repositório: traduzir a ideia central do livro, adaptar os exemplos, comentar o raciocínio em português e salvar visualizações geradas pelo próprio notebook.

A intenção não é copiar o código original do livro, mas reconstruir os conceitos com uma organização própria e usá-los como base para os capítulos seguintes.

## Como executar

Com o ambiente virtual do projeto ativado e as dependências instaladas, abra o notebook:

```bash
jupyter lab capitulos/01-introducao/cap_1.ipynb
```

Também é possível abrir o arquivo diretamente pelo VS Code usando a extensão do Jupyter.

## Dependências

Este capítulo usa principalmente:

- Python
- Jupyter
- `matplotlib`
- `collections.Counter`
- `collections.defaultdict`
- `pathlib.Path`
