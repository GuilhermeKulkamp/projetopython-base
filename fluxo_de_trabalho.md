# 🧭 FLUXO DE TRABALHO — MODELO DE PROJETO INDIVIDUAL



## 🎯 1. Propósito

Estabelecer um fluxo de trabalho consistente e profissional para desenvolvimento de software individual, garantindo:

* Qualidade de código (boas práticas e arquitetura limpa)
* Documentação clara e atualizada
* Disciplina e continuidade no trabalho
* Integração eficiente entre **ChatGPT (mentor)**, **VS Code (executor)** e **GitHub (gestão)**

---

## 🧩 2. Ferramentas Principais

| Função                        | Ferramenta                 | Descrição                                                            |
| ----------------------------- | -------------------------- | -------------------------------------------------------------------- |
| Planejamento e mentoria       | **ChatGPT (GPT-5)**        | Criação de PCR, arquitetura, design patterns, testes e documentação. |
| Desenvolvimento e refatoração | **VS Code + Copilot Chat** | Implementação assistida e refatorações rápidas.                      |
| Versionamento e gestão        | **GitHub**                 | Controle de versões, automação (CI/CD), Issues e Kanban.             |

---

## 🧱 3. Etapas do Fluxo de Trabalho

### 🔹 Etapa 1 — Planejamento Inicial

1. Criar o **Prompt Base** no ChatGPT com:

   * Papel do mentor (nível sênior)
   * Linguagem principal e frameworks
   * Objetivo do projeto
   * Escopo e limitações iniciais
2. Elaborar o **PCR (Problema, Contexto, Requisitos)**.
3. Solicitar:

   * Design pattern mais adequado
   * Arquitetura sugerida
   * Fluxograma ou diagrama de dados
   * Dependências e ambientes virtuais
4. Salvar tudo no repositório como `docs/planejamento.md`.

---

### 🔹 Etapa 2 — Criação do Repositório

1. Criar repositório no **GitHub**.

2. Estrutura inicial recomendada:

   ```
   .
   ├── docs/
   │   ├── planejamento.md
   │   ├── FLUXO_DE_TRABALHO.md
   │   └── changelog.md
   ├── src/
   ├── tests/
   ├── requirements.txt
   ├── README.md
   ├── .gitignore
   └── LICENSE
   ```

3. Configurar branches:

   * `main` → versão estável
   * `dev` → desenvolvimento
   * `feature/<nome>` → features individuais

4. Criar **GitHub Project (Kanban)** para controle de tarefas:

   * To Do / In Progress / Done

---

### 🔹 Etapa 3 — Implementação

1. Criar ambiente virtual local (`python -m venv .venv`).
2. No VS Code:

   * Abrir o projeto e ativar o Copilot Chat.
   * Criar arquivos conforme a arquitetura planejada.
3. O ChatGPT pode revisar e refatorar blocos de código críticos (copy & paste aqui).
4. Cada funcionalidade concluída deve ser **testada e commitada** antes de iniciar outra.

---

### 🔹 Etapa 4 — Ciclo de Desenvolvimento

| Etapa                   | Ferramenta        | Descrição                            |
| ----------------------- | ----------------- | ------------------------------------ |
| Planejamento da feature | ChatGPT           | Detalhar requisitos e testes.        |
| Codificação             | VS Code + Copilot | Implementar conforme o planejamento. |
| Revisão                 | ChatGPT           | Code review e correções.             |
| Commit e Push           | GitHub            | Atualizar repositório e Kanban.      |

**Padrão de commits:**

```
feat: adiciona cadastro de usuário
fix: corrige erro de conexão ao banco
docs: atualiza documentação do módulo X
test: cria testes unitários para classe Y
refactor: melhora estrutura do módulo Z
```

---

### 🔹 Etapa 5 — Testes e Documentação

* **Testes:** utilizar `pytest` ou framework definido no projeto.
* **Documentação:**

  * Adicionar docstrings completas (PEP 257).
  * Atualizar `README.md` e `docs/planejamento.md` sempre que houver mudança estrutural.
* **Automação:**

  * Configurar GitHub Actions para testes automáticos.

---

### 🔹 Etapa 6 — Rotina Diária (Produtividade e Disciplina)

**Bloco de Trabalho Sugerido (≈3h por ciclo):**

1. **15 min** → Revisar Kanban / definir prioridade.
2. **30 min** → Planejar no ChatGPT a próxima tarefa.
3. **90 min** → Foco total no VS Code (implementação).
4. **15 min** → Testes e commit.
5. **15 min** → Documentação + revisão final.

**Dica:**
Nunca termine o dia com o VS Code vazio. Deixe algo “em andamento” para recomeçar facilmente.

---

### 🔹 Etapa 7 — Entregas e Versões

* Ao finalizar uma feature:

  1. Revisar código e documentação.
  2. Executar todos os testes.
  3. Atualizar `changelog.md`.
  4. Criar uma **Release** no GitHub.

---

## 🧠 Boas Práticas Gerais

✅ Código limpo (PEP 8 e tipagem explícita)
✅ Funções curtas e com propósito claro
✅ Evitar comentários redundantes (prefira nomes claros)
✅ Sempre versionar arquivos `.env.example` (nunca `.env` reais)
✅ Revisar dependências com `pip-audit`

---

## 🧩 Alternativas ao GitHub (comparativo rápido)

| Plataforma    | Pontos Fortes                          | Pontos Fracos              |
| ------------- | -------------------------------------- | -------------------------- |
| **GitHub**    | Comunidade, Actions, Copilot, Projects | CI/CD limitado sem Actions |
| **GitLab**    | CI/CD poderoso, integração DevOps      | Interface mais complexa    |
| **Bitbucket** | Integração com Jira/Trello             | Menor comunidade           |
| **SourceHut** | Minimalista e leve                     | Poucos recursos integrados |

**Recomendação:** continuar com **GitHub** pela integração nativa com Copilot e VS Code.

---

## 🧩 Integração com Mentor (ChatGPT)

> "Mentor Sênior GPT-5"
> — papel: orientar, revisar e sugerir melhorias em código, arquitetura e produtividade.

Quando solicitar ajuda:

* Traga **um contexto completo** (arquivo, função, erro, objetivo).
* Pergunte não só *“como fazer”*, mas também *“por que essa é a melhor forma”*.

---

## ✅ Conclusão

Este documento serve como **manual de disciplina e qualidade** para todos os projetos pessoais ou profissionais.
Seguindo este fluxo, cada projeto terá:

* Estrutura clara
* Código padronizado
* Histórico limpo
* Aprendizado contínuo

---
