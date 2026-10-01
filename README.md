# project-template

Modelo de organização de um projeto de ciência de dados, criado por Edilson Uamusse para o exercício 4 de Fundamentals of Agro-Environmental Data Science (FADS).

## Estrutura

```text
project-template/
├── README.md
├── .gitignore
├── data/
│   ├── README.md
│   ├── external/README.md
│   ├── interim/README.md
│   ├── processed/README.md
│   └── raw/README.md
├── models/README.md
├── notebooks/README.md
├── src/
│   ├── README.md
│   ├── data/README.md
│   ├── features/README.md
│   └── model/README.md
├── documentation/README.md
└── output-graphs/README.md
```

A estrutura principal segue a imagem **Proposed layout** do artigo indicado no enunciado, incluindo `src/model` no singular. As pastas `documentation` e `output-graphs` complementam essa estrutura com documentação e figuras, conforme as categorias discutidas no exercício.

## Como começar

1. Copie este modelo para um novo projeto e adapte este README ao seu objetivo.
2. Coloque dados originais em `data/raw` e dados de terceiros em `data/external`.
3. Registe as fontes, unidades, datas e decisões em `documentation`.
4. Desenvolva a exploração em `notebooks` e o código reutilizável em `src`.
5. Guarde transformações intermédias em `data/interim` e dados prontos em `data/processed`.
6. Se houver modelação, guarde o código em `src/model` e os modelos treinados em `models`.
7. Guarde as figuras produzidas em `output-graphs`.

Este repositório é um modelo: não contém dados reais, análises executáveis nem modelos treinados. Não requer dependências para consultar os ficheiros Markdown. Quando acrescentar código, documente também as versões e os comandos necessários para o executar.

## Convenções

- Use nomes descritivos, em minúsculas, sem espaços ou acentos; separe palavras com hífen ou underscore.
- Use prefixos numéricos quando a ordem for relevante, por exemplo `01-import-temperature-data.py`.
- Preserve os dados originais; faça as transformações em ficheiros separados.
- Prefira formatos abertos adequados: CSV para tabelas, Markdown para documentação e Python ou Jupyter para código.
- Use caminhos relativos à raiz do projeto para facilitar a reprodução noutros computadores.
- Mantenha um README em cada pasta. O Git versiona ficheiros e não conserva pastas vazias.

`README.md` mantém a capitalização convencional pedida no exercício. Os nomes das pastas seguem a convenção de minúsculas.

## Fontes

- [Enunciado do exercício 4](https://github.com/isa-ulisboa/greends-fads-exercises/blob/main/fads_ex_04_ds_project_structure.md).
- [Artigo e esquema de referência, na versão arquivada indicada pelo enunciado](https://web.archive.org/web/20251125222007/https://neptune.ai/blog/best-practices-for-data-science-project-workflows-and-file-organizations).
