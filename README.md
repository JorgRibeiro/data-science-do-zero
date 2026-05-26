# data-science-do-zero

Guia de estudo open-source inspirado no livro **Data Science do Zero - 2ª edição: noções fundamentais com Python**, organizado como uma trilha prática em português e com espaço para adaptações, experimentos e anotações próprias.

## Objetivo

Este repositório será a minha versão de estudo do conteúdo do livro, com uma estrutura por capítulo parecida com a do meu repositório hands-on, mas sem copiar os códigos originais. A ideia é evoluir cada capítulo com implementações próprias, comentários em português e o meu próprio jeito de organizar o aprendizado.

## Estrutura

Cada capítulo possui sua própria pasta dentro de `capitulos/`. Em cada uma delas, o conteúdo poderá crescer com exercícios, explicações, exemplos e versões revisadas ao longo do estudo.

## Como rodar o projeto

### 1. Crie o ambiente virtual

Primeiro, crie um ambiente virtual para isolar as dependências do projeto.

Exemplo utilizando o `uv`:

```bash
uv venv --python 3.12 .venv
```

### 2. Ative o ambiente virtual

Depois de criar o ambiente, ative-o:

```bash
source .venv/bin/activate
```

### 3. Instale as dependências

Com o ambiente virtual ativado, instale as dependências do projeto:

```bash
uv pip install -r requirements.txt
```

### 4. Escolha onde executar os notebooks

Você pode executar os notebooks de duas formas:

- Pelo **VS Code**, utilizando a extensão do Jupyter.
- Pelo navegador, utilizando o **JupyterLab**:

```bash
jupyter lab
```

## Créditos e aviso

- Livro-base: **Data Science do Zero - 2ª edição: noções fundamentais com Python**, de **Joel Grus**.
- Este projeto é uma versão **gratuita**, **open-source** e feita **exclusivamente para estudo e educação**.
- Não há qualquer objetivo comercial ou monetário neste material.
- Todos os direitos sobre a obra original pertencem ao autor do livro.
