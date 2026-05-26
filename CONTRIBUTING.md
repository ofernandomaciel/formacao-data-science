# 🤝 Guia de Contribuição — DataPath

Obrigado por considerar contribuir com este projeto! Este é um curso aberto construído pela comunidade brasileira de dados, e cada contribuição — por menor que seja — faz diferença para quem está aprendendo.

---

## 📋 Índice

1. [Código de Conduta](#-código-de-conduta)
2. [Como posso contribuir?](#-como-posso-contribuir)
3. [Configurando o ambiente](#️-configurando-o-ambiente)
4. [Padrões de conteúdo](#-padrões-de-conteúdo)
5. [Processo de Pull Request](#-processo-de-pull-request)
6. [Reportando Issues](#-reportando-issues)
7. [Reconhecimento de contribuidores](#-reconhecimento-de-contribuidores)

---

## 🌟 Código de Conduta

Este projeto adota os princípios do [Contributor Covenant](https://www.contributor-covenant.org/). Em resumo:

- Seja respeitoso e inclusivo com todos
- Aceite críticas construtivas com abertura
- Foque no que é melhor para quem está aprendendo
- Não tolere discriminação de qualquer tipo

Comportamentos inaceitáveis podem ser reportados abrindo uma issue privada ou via e-mail ao mantenedor.

---

## 🛠️ Como posso contribuir?

### 🐛 1. Reportar erros ou links quebrados

A forma mais simples de ajudar. Se encontrou:
- Um link que não funciona mais
- Uma informação desatualizada (salário, ferramenta, API)
- Um erro de português ou conceito incorreto
- Um exercício com enunciado confuso

➡️ [Abra uma issue](../../issues/new?template=bug_report.md) usando o template de bug.

---

### ✍️ 2. Escrever ou melhorar conteúdo de uma semana

Cada semana segue uma estrutura padrão. Para contribuir com uma semana nova ou melhorar uma existente:

**Semanas prioritárias (precisam de conteúdo manual):**
- Semanas 3–40 — qualquer módulo aceita contribuições

**O que incluir em cada semana:**
- Resumo didático (300–500 palavras) em PT-BR
- 3–5 vídeos recomendados (prioritariamente em português)
- 2–3 repositórios GitHub relevantes
- 1–2 livros ou documentações
- 2–3 artigos ou posts de referência
- 1–2 datasets para prática
- Exercícios nos 3 níveis (veja padrões abaixo)
- Checklist de aula de 2 horas

---

### 🌐 3. Sugerir recursos em português

Se você conhece um canal, livro, artigo ou repositório em PT-BR que deveria estar no curso e não está, abra uma issue com:
- Nome e link do recurso
- Para qual semana/tópico ele seria mais relevante
- Por que ele é melhor do que o que já está listado (se for substituição)

---

### 💡 4. Propor novos exercícios

Bons exercícios são o coração do curso. Um exercício ideal:
- Usa dados reais (preferencialmente brasileiros)
- Tem enunciado claro e objetivo
- Inclui uma dica sem entregar a solução
- Gera código que pode ir para o portfólio no GitHub

---

### 🔧 5. Melhorar a plataforma web

O arquivo `plataforma/curso_data_science.html` é um único arquivo HTML/CSS/JS. Contribuições técnicas bem-vindas:
- Melhorar acessibilidade (ARIA, contraste)
- Adicionar modo claro/escuro
- Melhorar responsividade mobile
- Adicionar sistema de progresso persistente (localStorage)
- Traduzir comentários do código para PT-BR

---

## ⚙️ Configurando o Ambiente

Não há build system — o projeto é propositalmente simples para ser acessível.

```bash
# 1. Fork o repositório no GitHub

# 2. Clone o seu fork
git clone https://github.com/SEU_USUARIO/formacao-data-science.git
cd formacao-data-science

# 3. Crie uma branch para sua contribuição
git checkout -b feat/semana-03-bancos-relacionais
# ou
git checkout -b fix/link-quebrado-semana-01

# 4. Faça suas alterações

# 5. Commit com mensagem clara
git commit -m "feat(mod02): adiciona conteúdo completo semana 3 — bancos relacionais"

# 6. Push e abra o Pull Request
git push origin feat/semana-03-bancos-relacionais
```

---

## 📐 Padrões de Conteúdo

### Convenção de branches

```
feat/semana-XX-titulo-curto      ← novo conteúdo
fix/link-semana-XX               ← correção de link
improve/semana-XX-exercicios     ← melhoria de conteúdo existente
docs/readme-update               ← mudança em documentação
```

### Convenção de commits

```
feat(mod01): adiciona glossário semana 2
fix(mod02): corrige link YouTube semana 4
improve(mod05): expande exercício nível 3 semana 17
docs: atualiza CONTRIBUTING com seção de datasets
```

### Padrão de conteúdo escrito

- **Idioma:** Português do Brasil (sem erros ortográficos)
- **Tom:** Didático, encorajador, sem condescendência
- **Exemplos:** Priorize empresas e casos brasileiros reais
- **Tecnicidade:** Semana 1 deve ser acessível a quem nunca programou; Semana 40 pode assumir conhecimento avançado
- **Fontes:** Todo dado factual (salário, estatística, data) deve ter referência

### Padrão para links

```markdown
<!-- ✅ Correto -->
[Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)

<!-- ❌ Evitar — links encurtados -->
[Livro](https://bit.ly/xyzabc)
```

- Use sempre a URL completa e oficial
- Prefira links para fontes primárias (GitHub oficial, documentação, Kaggle)
- Teste o link antes de submeter

### Padrão para exercícios

Cada exercício deve ter obrigatoriamente:

```markdown
#### Exercício X.Y — Título Descritivo

**Objetivo:** O que o estudante vai praticar com este exercício.

**Enunciado:** Descrição clara do que deve ser feito, com todos os dados
necessários para começar. Se precisar de um dataset, inclua o link.

**Dica:** Uma orientação que ajuda a começar sem entregar a solução completa.

**Critérios de avaliação** (apenas para Nível 3):
- ✓ Critério objetivo 1
- ✓ Critério objetivo 2
- ✓ Critério objetivo 3
```

---

## 🔄 Processo de Pull Request

1. **Abra o PR** contra a branch `main`
2. **Preencha o template** de PR completamente
3. **Aguarde revisão** — geralmente em até 7 dias úteis
4. **Responda comentários** se houver pedidos de ajuste
5. Após aprovação, o PR é **mergeado com squash**

### O que verificamos na revisão

- [ ] Conteúdo em português correto e sem plágio
- [ ] Todos os links testados e funcionando
- [ ] Exercícios com enunciado claro e dica útil
- [ ] Progresso de dificuldade respeitado (sem material avançado demais para a semana)
- [ ] Exemplos brasileiros incluídos quando possível
- [ ] Sem repetição de conteúdo já existente em outras semanas

---

## 🐞 Reportando Issues

Use os templates disponíveis ao [abrir uma issue](../../issues/new/choose):

| Template | Quando usar |
|----------|-------------|
| 🐛 Bug / Erro de conteúdo | Informação incorreta, link quebrado |
| 💡 Sugestão de recurso | Vídeo, livro ou dataset para adicionar |
| ✍️ Solicitação de semana | Pedir que uma semana específica seja completada |
| ❓ Dúvida | Dúvida sobre o conteúdo do curso |

**Issues bem detalhadas têm prioridade.** Inclua:
- O número da semana e módulo afetados
- O que está errado / o que deveria estar lá
- O link correto, se for o caso

---

## 🏅 Reconhecimento de Contribuidores

Todos os contribuidores são listados no README com seus usernames do GitHub. Contribuições de qualquer tamanho contam — desde a correção de um typo até a escrita completa de um módulo.

Usamos o padrão [All Contributors](https://allcontributors.org/) para reconhecer diferentes tipos de contribuição:

| Emoji | Tipo |
|-------|------|
| 📖 | Conteúdo educacional |
| 🔗 | Curadoria de links |
| 🐛 | Correção de bugs/erros |
| 💻 | Código da plataforma |
| 🌍 | Tradução |
| 📋 | Exercícios |
| 🤔 | Ideias e sugestões |

---

## ❓ Dúvidas?

- Abra uma [issue com a label `pergunta`](../../issues/new?labels=pergunta)
- Participe da discussão na aba [Discussions](../../discussions) do repositório
- Entre na comunidade [DataHackers Discord](https://discord.gg/datahackers) — use o canal `#recursos-abertos`

---

<div align="center">
  <sub>Obrigado por ajudar a democratizar o aprendizado de dados no Brasil 💜</sub>
</div>
