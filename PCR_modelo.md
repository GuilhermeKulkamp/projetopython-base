# 🧭 Plano de Controle do Projeto (PCR)

> Modelo base para gestão e documentação de projetos Python — adaptado para desenvolvedores solo com foco em boas práticas, aprendizado contínuo e metodologias ágeis leves.

---

## 📘 1. Informações Gerais
| Item | Descrição |
|------|------------|
| **Nome do Projeto** | *(Definir)* |
| **Responsável** | *(Seu nome)* |
| **Data de Início** | *(Definir)* |
| **Versão do Documento** | 1.0 |
| **Última Atualização** | *(Data atual)* |
| **Status** | Em andamento / Concluído / Suspenso |

---

## 🎯 2. Objetivo do Projeto
Descreva de forma clara o propósito do projeto, seu público-alvo e o problema que ele resolve.  
Explique **por que** este projeto é relevante técnica e/ou profissionalmente.

---

## 🧱 3. Escopo do Projeto
Liste as principais entregas (features, integrações, automações, etc.) e o que **não** está incluído no escopo inicial.

> 🔸 *Exemplo:* Este projeto visa desenvolver um sistema local de gerenciamento de tarefas em Python utilizando Flet, SQLite e o padrão MVC.  
> 🔹 Não estão incluídas: integração com APIs externas, autenticação de usuários, interface web.

---

## 🧩 4. Arquitetura e Design Patterns
Descreva a arquitetura planejada (ex: MVC, Clean Architecture, Layered, etc.) e os **padrões de projeto (Design Patterns)** recomendados.  

> 💡 *Dica:* Se estiver em dúvida, utilize o ChatGPT Mentor para sugerir o padrão mais adequado com base nas regras de negócio e tamanho do projeto.

**Exemplo de padrões possíveis:**
- Singleton → controle de instâncias únicas  
- Repository → abstração de dados  
- Observer → notificações de eventos  
- Factory → criação flexível de objetos  

---

## ⚙️ 5. Tecnologias e Ferramentas
| Categoria | Ferramenta |
|------------|-------------|
| **Linguagem** | Python 3.x |
| **Frameworks** | *(Ex: Flet, Django, FastAPI)* |
| **IDE** | Visual Studio Code 1.104.3 |
| **Sistema Operacional** | Ubuntu 25.04 |
| **Controle de Versão** | Git + GitHub |
| **Assistente de Código** | GitHub Copilot |
| **Mentoria Técnica** | ChatGPT (GPT-5) |
| **Testes** | pytest |
| **Linter / Formatação** | flake8, black |
| **Documentação** | docstring PEP257 + Markdown |
| **Gerenciamento** | GitHub Projects / Issues |

---

## 🧠 6. Metodologia de Trabalho

> Este projeto segue **metodologias ágeis adaptadas** para o desenvolvimento individual, inspiradas em **Scrum** e **Kanban**, com foco em entregas incrementais, aprendizado contínuo e redução de retrabalho.

### 💬 Por que utilizar metodologias ágeis
Como o projeto é desenvolvido individualmente e voltado ao aprendizado, a abordagem ágil traz benefícios reais:
1. **Motivação constante:** pequenas entregas criam ritmo e progresso visível.  
2. **Evita retrabalho:** revisões rápidas e ajustes a cada ciclo.  
3. **Documentação viva:** o PCR e README evoluem junto com o código.  
4. **Melhoria contínua:** cada iteração é uma oportunidade de aprendizado técnico e organizacional.  

### 🌀 Estrutura aplicada
| Elemento | Adaptação |
|-----------|------------|
| **Sprint** | 7 a 10 dias com entregas incrementais |
| **Backlog** | Gerenciado no GitHub Projects |
| **Daily** | Revisão pessoal (anotações curtas sobre progresso e bloqueios) |
| **Review** | Revisão técnica e atualização de documentação |
| **Retrospectiva** | Registro do aprendizado e ajustes no fluxo |

> 📘 *O foco é a constância e evolução, não a complexidade. O método serve para apoiar, não limitar.*

---

## 🗂️ 7. Estrutura do Repositório

```
.
├── docs/
│ ├── FLUXO_DE_TRABALHO.md
│ ├── planejamento.md
│ └── changelog.md
├── src/
│ └── (código do projeto)
├── requirements.txt
└── README.md
``` 

---

## 🔄 8. Fluxo de Trabalho
> O fluxo de trabalho define as etapas e responsabilidades dentro do ciclo de desenvolvimento.

<details>
<summary>📋 Etapas resumidas</summary>

1. **Planejamento inicial:** definir objetivo, escopo e arquitetura.  
2. **Criação do repositório GitHub:** configurar estrutura e arquivos padrão.  
3. **Desenvolvimento:** implementar código conforme planejamento.  
4. **Documentação contínua:** atualizar PCR e README a cada entrega.  
5. **Revisão:** verificar código, linting e testes antes do commit.  
6. **Commit e push:** mensagens padronizadas seguindo Conventional Commits.  
7. **Feedback:** revisar junto ao ChatGPT Mentor antes do próximo ciclo.  

</details>

---

## 🧩 9. Plano de Qualidade
| Item | Estratégia |
|------|-------------|
| **Padronização de Código** | PEP8, black, flake8 |
| **Testes Unitários** | pytest |
| **Documentação** | docstrings + README |
| **Controle de Versão** | commits atômicos e mensagens descritivas |
| **Revisões Técnicas** | ChatGPT Mentor e Copilot |

---

## 🧪 10. Testes
- Especifique a cobertura esperada (ex: ≥80%)  
- Defina o tipo de teste: unitário, integração, E2E  
- Mantenha scripts automatizados e casos documentados

---

## 🧭 11. Cronograma e Entregas
Use sprints de curta duração e defina entregas parciais:
| Sprint | Objetivo | Entrega | Status |
|--------|-----------|----------|--------|
| 1 | Configuração do ambiente | Repositório + ambiente virtual | ✅ |
| 2 | Implementação do módulo base | CRUD + testes iniciais | 🟡 |
| 3 | Interface ou API | Integração front/back | 🔜 |

---

## 📚 12. Lições Aprendidas
Registre aprendizados técnicos e estratégicos ao fim de cada sprint:
> Exemplo: “Percebi que pequenas revisões diárias evitam retrabalho e ajudam a manter a qualidade do código.”

---

## 🧾 13. Histórico de Revisões
| Data | Versão | Descrição | Responsável |
|------|---------|------------|--------------|
| *(Data)* | 1.0 | Criação inicial do documento | *(Seu nome)* |
| *(Data)* | 1.1 | Inclusão da metodologia ágil e ajustes | *(Seu nome)* |

---

## 📜 14. Licença
Distribuído sob a licença MIT — ver arquivo `LICENSE`.

---
