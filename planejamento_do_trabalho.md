# 📅 Planejamento do Projeto

> Documento de acompanhamento do progresso técnico e das entregas.  
> Baseado em metodologias ágeis adaptadas para trabalho individual, com foco em **constância**, **qualidade** e **aprendizado contínuo**.
> 
> Este documento é o elo entre o PCR e o desenvolvimento prático, funcionando como o painel de controle do projeto.
> Ele organiza o backlog, as sprints, as metas técnicas, as prioridades e as datas, tudo em formato Markdown compatível com o GitHub Projects.
>
> Abaixo está o modelo completo, já padronizado com:
> - Estrutura ágil adaptada (para dev solo).
> - Seções editáveis e exemplos práticos.
> - Campos e tabelas para controle de progresso.
> - Blocos de anotações e observações pessoais (para aprendizado).


---

## 🧭 1. Visão Geral do Projeto
| Item | Descrição |
|------|------------|
| **Nome do Projeto** | *(Definir)* |
| **Objetivo Geral** | *(Definir em 1 parágrafo curto)* |
| **Data de Início** | *(dd/mm/aaaa)* |
| **Data Prevista de Conclusão** | *(dd/mm/aaaa)* |
| **Status Atual** | 🟢 Em andamento / 🟡 Em pausa / 🔵 Em revisão / ✅ Concluído |

---

## 🧩 2. Metas Técnicas Principais
Liste aqui as entregas de maior impacto do projeto (funcionais ou técnicas).

| ID | Meta Técnica | Prioridade | Status | Observações |
|----|---------------|-------------|----------|--------------|
| M1 | Implementar arquitetura base (MVC / Clean) | Alta | 🟢 | Estrutura inicial do projeto |
| M2 | Criar camada de dados com SQLAlchemy | Alta | 🟡 | Validar modelo de banco antes |
| M3 | Desenvolver interface com Flet | Média | 🔜 | Avaliar layout responsivo |
| M4 | Implementar testes unitários | Alta | 🔴 | Criar base pytest |
| M5 | Escrever documentação técnica e README | Média | 🔜 | Manter atualizada |

---

## 🧠 3. Roadmap Geral
Planeje o caminho macro do projeto, com foco nas **entregas progressivas** e **iteração constante**.

| Fase | Entrega Principal | Data Prevista | Data Real | Status |
|------|--------------------|----------------|------------|---------|
| Fase 1 | Planejamento e setup | 10/10/2025 |  | 🟢 |
| Fase 2 | Desenvolvimento base (arquitetura + repositórios) | 17/10/2025 |  | 🟡 |
| Fase 3 | Implementação de UI e integração | 24/10/2025 |  | 🔵 |
| Fase 4 | Testes, refinamento e documentação final | 30/10/2025 |  | 🔜 |

---

## 🧩 4. Backlog de Funcionalidades
Lista dinâmica com todas as features, ideias e melhorias do projeto.  
Use o GitHub Projects para acompanhar o status, e atualize este documento periodicamente.

| ID | Tarefa / Feature | Categoria | Status | Observações |
|----|-------------------|------------|----------|--------------|
| F1 | Criar estrutura de pastas padrão | Setup | ✅ | Baseado no template |
| F2 | Implementar CRUD de produtos | Backend | 🟢 | Início da camada de dados |
| F3 | Conectar SQLite via ORM | Banco de Dados | 🟡 | Verificar mapeamento automático |
| F4 | Criar tela principal com Flet | Frontend | 🔜 | Layout inicial |
| F5 | Adicionar botão “Adicionar item” | Frontend | 🔜 | Interatividade e callbacks |
| F6 | Criar testes unitários básicos | Testes | 🔴 | Começar com pytest simples |
| F7 | Escrever docstrings em todos os módulos | Documentação | 🔜 | PEP257 |
| F8 | Revisar commits e fluxo Git | Organização | 🔵 | Garantir atomicidade |

---

## 🚀 5. Planejamento de Sprints
Cada sprint representa um ciclo curto (7 a 10 dias) de entregas concretas.  
O foco é **pequenas vitórias técnicas**, mantendo o projeto ativo e evolutivo.

### 🗓️ Sprint 1 — Configuração e Arquitetura
| Item | Descrição | Status |
|------|------------|--------|
| S1.1 | Criar repositório e estrutura de pastas | ✅ |
| S1.2 | Configurar ambiente virtual e dependências | ✅ |
| S1.3 | Definir arquitetura e padrão de projeto | 🟢 |
| S1.4 | Criar repositório base no GitHub | ✅ |

### 🗓️ Sprint 2 — Implementação Base
| Item | Descrição | Status |
|------|------------|--------|
| S2.1 | Implementar camada de dados | 🟢 |
| S2.2 | Criar repositórios e entidades | 🟡 |
| S2.3 | Testar persistência local | 🔜 |
| S2.4 | Documentar decisões técnicas | 🔜 |

### 🗓️ Sprint 3 — Interface e Integração
| Item | Descrição | Status |
|------|------------|--------|
| S3.1 | Criar interface principal no Flet | 🔜 |
| S3.2 | Integrar backend com frontend | 🔜 |
| S3.3 | Validar eventos e estados | 🔜 |
| S3.4 | Ajustar layout e responsividade | 🔜 |

---

## 🧩 6. Indicadores de Progresso
| Indicador | Meta | Atual | Status |
|------------|------|--------|--------|
| **Cobertura de Testes** | ≥ 80% |  | 🔜 |
| **Commits Revisados** | 100% |  | 🔜 |
| **Documentação Atualizada** | Sempre |  | 🟢 |
| **Sprints Concluídas** | 3 |  | 🟡 |

---

## 🧠 7. Lições e Observações de Aprendizado
> Use este espaço para anotar reflexões, desafios e aprendizados técnicos ou pessoais durante o projeto.

- 📌 *Exemplo:* percebi que estruturar as funções antes de codar economiza tempo e reduz retrabalho.  
- 🧠 *Exemplo:* aprendi a usar o padrão Repository com SQLAlchemy para desacoplar o acesso ao banco.  
- ⚙️ *Exemplo:* revisar commits diariamente mantém o histórico limpo e claro.

---

## 🧾 8. Revisões e Atualizações
| Data | Versão | Descrição da Atualização | Responsável |
|------|---------|--------------------------|--------------|
| *(dd/mm/aaaa)* | 1.0 | Criação inicial do documento | *(Seu nome)* |
| *(dd/mm/aaaa)* | 1.1 | Inclusão do backlog detalhado e sprints | *(Seu nome)* |

---

> **Dica final 💡:** Atualize este documento **ao final de cada sprint** — isso mantém o histórico coerente e mostra sua evolução como desenvolvedor e gestor do próprio trabalho.
