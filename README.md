# 📊 DataPath — Formação em Ciência de Dados

[![Licença: CC BY 4.0](https://img.shields.io/badge/Conteúdo-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Licença: MIT](https://img.shields.io/badge/Código-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-yellow.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-bem--vindos-brightgreen.svg)](CONTRIBUTING.md)
[![Idioma](https://img.shields.io/badge/Idioma-Português%20BR-green.svg)]()

> Trilha completa de formação em Ciência de Dados em português do Brasil — do SQL básico ao Deep Learning, com foco no mercado brasileiro, exercícios práticos e projetos de portfólio reais.

---

## 🗺️ Sobre o Projeto

Este repositório é um **curso aberto e colaborativo** estruturado em **40 semanas** (2 semestres), com aulas diárias de 2 horas. Todo o material é em português do Brasil e gratuito.

A plataforma inclui, para cada semana:

- 📚 Conteúdo escrito didático (300–500 palavras por tópico)
- 🎥 Curadoria de vídeos (prioritariamente em PT-BR)
- 💻 Repositórios GitHub de referência
- 📖 Livros e capítulos recomendados
- 📰 Artigos acadêmicos e essays
- 📊 Datasets para prática
- ✍️ Exercícios em 3 níveis (básico → intermediário → portfólio)
- 🏆 Projetos de módulo com rubrica de avaliação
- ⏱️ Cronograma de aula de 2 horas

---

## 🗂️ Estrutura do Curso

| Semestre | Módulo | Título | Semanas |
|----------|--------|--------|---------|
| 1 | 01 | Fundamentos de Ciência de Dados | 1–2 |
| 1 | 02 | SQL — Fundamentos | 3–7 |
| 1 | 03 | SQL Avançado e Integração com Python | 8–10 |
| 1 | 04 | Python para Ciência de Dados | 11–14 |
| 1 | 05 | EDA e Visualização | 15–19 |
| 1 | 06 | Estatística e Probabilidade Aplicada | 20–22 |
| 2 | 07 | Machine Learning Básico | 23–28 |
| 2 | 08 | ML Avançado e Deep Learning | 29–33 |
| 2 | 09 | Big Data, Cloud e Engenharia de Dados | 34–37 |
| 2 | 10 | Projetos Integradores e Portfólio | 38–40 |

---

## 🚀 Como Usar

### Opção 1 — Plataforma Interativa (recomendado)

1. Faça o download ou clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/formacao-data-science.git
   cd formacao-data-science
   ```

2. Abra o arquivo da plataforma diretamente no navegador:
   ```
   plataforma/curso_data_science.html
   ```

3. Navegue pelos módulos na barra lateral e use os botões **✨ Gerar Semana** para criar conteúdo com IA para as semanas que ainda não têm material manual.

> **Nota:** O botão "Gerar Semana" usa a API da Anthropic (Claude). Para que funcione, a página deve ser aberta no contexto do Claude.ai ou você deve adicionar sua própria chave de API.

### Opção 2 — Markdown puro

Cada módulo também está disponível em arquivos `.md` na pasta correspondente, sem necessidade de JavaScript.

---

## 📁 Estrutura de Pastas

```
formacao-data-science/
│
├── README.md                    ← Este arquivo
├── CONTRIBUTING.md              ← Como contribuir
├── CHANGELOG.md                 ← Histórico de mudanças
├── LICENSE                      ← MIT (código) + CC BY 4.0 (conteúdo)
│
├── plataforma/
│   └── curso_data_science.html  ← Plataforma web interativa completa
│
├── modulo-01-fundamentos/
│   ├── semana-01-o-que-e-ds.md
│   └── semana-02-carreiras-etica.md
│
├── modulo-02-sql/
│   ├── semana-03-bancos-relacionais.md
│   ├── semana-04-select-where.md
│   ├── semana-05-funcoes-filtros.md
│   ├── semana-06-group-by.md
│   └── semana-07-joins-indices.md
│
├── modulo-03-sql-avancado/
│   ├── semana-08-subqueries-ctes.md
│   ├── semana-09-window-functions.md
│   └── semana-10-python-sql.md
│
├── modulo-04-python/
│   ├── semana-11-python-basico.md
│   ├── semana-12-estruturas-dados.md
│   ├── semana-13-numpy.md
│   └── semana-14-pandas.md
│
├── modulo-05-eda-visualizacao/
│   ├── semana-15-limpeza-dados.md
│   ├── semana-16-estatistica-descritiva.md
│   ├── semana-17-matplotlib.md
│   ├── semana-18-seaborn.md
│   └── semana-19-plotly-streamlit.md
│
├── modulo-06-estatistica/
│   ├── semana-20-probabilidade.md
│   ├── semana-21-testes-hipotese.md
│   └── semana-22-algebra-linear.md
│
├── modulo-07-machine-learning/
│   ├── semana-23-intro-ml.md
│   ├── semana-24-regressao-linear.md
│   ├── semana-25-regressao-logistica.md
│   ├── semana-26-arvore-random-forest.md
│   ├── semana-27-gradient-boosting.md
│   └── semana-28-clusterizacao-pca.md
│
├── modulo-08-deep-learning/
│   ├── semana-29-redes-neurais.md
│   ├── semana-30-cnn-transfer-learning.md
│   ├── semana-31-nlp.md
│   ├── semana-32-series-temporais.md
│   └── semana-33-interpretabilidade.md
│
├── modulo-09-big-data/
│   ├── semana-34-pyspark.md
│   ├── semana-35-cloud.md
│   ├── semana-36-pipelines-etl.md
│   └── semana-37-data-modeling.md
│
└── modulo-10-portfolio/
    ├── semana-38-projeto-integrador-1.md
    ├── semana-39-projeto-integrador-2.md
    └── semana-40-portfolio-carreira.md
```

---

## 🎯 Para Quem é Este Curso

- Pessoas iniciando na área de dados **sem experiência prévia**
- Profissionais de outras áreas em **transição de carreira**
- Estudantes que querem um **roteiro estruturado** em PT-BR
- Autodidatas que sentem falta de **exercícios práticos e projetos reais**

### Pré-requisitos

- Nenhum conhecimento técnico prévio é necessário para o Semestre 1
- Computador com acesso à internet
- Conta gratuita no [Kaggle](https://kaggle.com) e [GitHub](https://github.com)
- Vontade de estudar 2 horas por dia 🙂

---

## 🏆 Projetos de Portfólio

Ao concluir o curso, você terá ao menos **10 projetos** no GitHub:

| # | Módulo | Projeto |
|---|--------|---------|
| 1 | Fundamentos | Relatório de Mapa de Carreira em DS |
| 2 | SQL | Análise de Base de Dados de E-commerce com SQL Puro |
| 3 | SQL Avançado | Dashboard de Métricas com CTEs e Window Functions |
| 4 | Python | Análise Exploratória com pandas e NumPy |
| 5 | EDA | Relatório Completo de EDA com Storytelling Visual |
| 6 | Estatística | Análise A/B Test com Significância Estatística |
| 7 | ML Básico | Pipeline de ML: Previsão de Churn |
| 8 | Deep Learning | Classificador de Imagens ou Análise de Sentimento |
| 9 | Big Data | Pipeline de Dados com PySpark |
| 10 | Integrador | Projeto End-to-End: SQL → EDA → ML → Deploy |

---

## 📌 Status do Conteúdo

| Módulo | Conteúdo Manual | Geração por IA |
|--------|-----------------|----------------|
| 01 — Fundamentos | ✅ Semanas 1–2 completas | — |
| 02 — SQL | 🔄 Em produção | ✨ Disponível na plataforma |
| 03 — SQL Avançado | 🔄 Em produção | ✨ Disponível na plataforma |
| 04 — Python | 🔄 Em produção | ✨ Disponível na plataforma |
| 05 — EDA | 🔄 Em produção | ✨ Disponível na plataforma |
| 06 — Estatística | 🔄 Em produção | ✨ Disponível na plataforma |
| 07 — ML | 🔄 Em produção | ✨ Disponível na plataforma |
| 08 — Deep Learning | 🔄 Em produção | ✨ Disponível na plataforma |
| 09 — Big Data | 🔄 Em produção | ✨ Disponível na plataforma |
| 10 — Portfólio | 🔄 Em produção | ✨ Disponível na plataforma |

---

## ⚠️ Aviso sobre Links Externos

Os links para vídeos, artigos e datasets foram selecionados com cuidado, mas **recursos externos podem mudar ou sair do ar** sem aviso. Se encontrar um link quebrado, por favor [abra uma issue](../../issues/new) ou envie um Pull Request com a correção. Veja [CONTRIBUTING.md](CONTRIBUTING.md) para detalhes.

Os dados de **salários e mercado** têm como referência o **State of Data Brazil 2023**. Para valores atualizados, consulte sempre a edição mais recente em [datahackers.com.br](https://www.datahackers.com.br/state-of-data-brazil).

---

## 🤝 Como Contribuir

Contribuições são muito bem-vindas! Você pode ajudar de várias formas:

- 🐛 Reportar erros de conteúdo ou links quebrados
- ✍️ Escrever ou melhorar o material de uma semana
- 🌐 Sugerir recursos em português que ainda não estão listados
- 💡 Propor novos exercícios ou projetos
- 🌍 Traduzir recursos em inglês para o português

Leia o [CONTRIBUTING.md](CONTRIBUTING.md) para entender o processo completo.

---

## 📜 Licença

- **Código-fonte** (HTML, CSS, JavaScript): [MIT License](LICENSE)
- **Conteúdo educacional** (textos, exercícios, glossários): [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Você pode usar, adaptar e redistribuir livremente, desde que dê os devidos créditos.

---

## ✨ Créditos

Este projeto foi criado com o apoio da [Anthropic Claude](https://claude.ai) como assistente de geração de conteúdo educacional.

Referências principais de conteúdo:
- [State of Data Brazil — DataHackers](https://www.datahackers.com.br)
- [Python Data Science Handbook — Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Escola de Dados](https://escoladedados.org)
- [Programação Dinâmica](https://www.youtube.com/@ProgramacaoDinamica)

---

<div align="center">
  <sub>Feito com 💜 para a comunidade brasileira de dados</sub>
</div>
