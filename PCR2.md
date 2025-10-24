# 🧩 PCR — Project Control Record

> Documento de controle técnico e registro de decisões do projeto.


## 🧭 1. Identificação do Projeto

| Campo | Descrição |
|--------|------------|
| **Nome do Projeto** | (ex: Lista de Compras em Python) |
| **Autor** | (ex: Guilherme Kulkamp) |
| **Data de Início** | (AAAA-MM-DD) |
| **Versão Atual** | 0.1.0 |
| **Repositório GitHub** | (URL) |

---

## 🧱 2. Contexto e Justificativa

Descreva o problema a ser resolvido e o motivo do desenvolvimento do projeto.

---

## 🎯 3. Objetivos Técnicos

- [ ] Implementar arquitetura organizada e escalável  
- [ ] Seguir padrões de código (PEP8, docstrings, testes)  
- [ ] Aplicar design patterns adequados  
- [ ] Documentar todas as decisões relevantes

---

## ⚙️ 4. Arquitetura e Design Patterns

| Aspecto | Decisão |
|----------|----------|
| **Arquitetura-base** | (Ex: MVC, Clean Architecture, Hexagonal) |
| **Padrões de Projeto** | (Ex: Repository, Observer, Strategy, Singleton, etc.) |
| **Justificativa Técnica** | Por que o padrão foi escolhido e como ele se aplica ao projeto |

---

## 🧩 5. Stack Técnica

| Item | Ferramenta |
|------|-------------|
| **Linguagem** | Python 3.12+ |
| **Frameworks** | (Ex: Flet, Django, FastAPI, etc.) |
| **ORM / DB** | (Ex: SQLAlchemy + SQLite) |
| **Testes** | pytest, unittest |
| **Documentação** | pdoc3, mkdocs |
| **CI/CD** | GitHub Actions |

---

## 📜 6. Requisitos Funcionais

| ID | Requisito | Prioridade |
|----|------------|-------------|
| RF01 | O sistema deve permitir... | Alta |
| RF02 | O usuário poderá... | Média |

---

## ⚙️ 7. Requisitos Não Funcionais

| ID | Requisito | Categoria |
|----|------------|-----------|
| RNF01 | O código deve seguir PEP8 | Qualidade |
| RNF02 | Todas as dependências devem estar documentadas | Manutenibilidade |
| RNF03 | O sistema deve possuir testes automatizados | Confiabilidade |

---

## 🧪 8. Testes e Qualidade

- **Cobertura mínima:** 80%  
- **Ferramentas:** `pytest`, `flake8`  
- **Estrutura:** testes unitários e de integração separados  
- **Execução:** automática via GitHub Actions  

---

## 🧭 9. Segurança e Boas Práticas

- Armazenar credenciais via variáveis de ambiente  
- Nunca versionar dados sensíveis  
- Aplicar princípios de **menor privilégio** e **responsabilidade única**  
- Evitar dependências desnecessárias

---

## 📚 10. Documentação e Atualizações

- Atualizar `README.md` e `planejamento.md` a cada sprint  
- Versionar decisões técnicas e mudanças no `CHANGELOG.md`  
- Gerar documentação automática com `pdoc3`  

---

## 🔁 11. Histórico de Decisões

| Data | Decisão | Motivo |
|-------|----------|--------|
| AAAA-MM-DD | Escolha do padrão MVC | Simplicidade e separação clara de responsabilidades |

---

## 🧭 12. Metodologia de Trabalho

> Este projeto adota **metodologia ágil adaptada para trabalho individual**, com foco em **entregas incrementais, documentação viva e aprendizado contínuo**.  
> Cada sprint possui revisões e retrospectivas documentadas no `planejamento.md`.

---

> 🧩 Documento PCR — Baseado em boas práticas de Engenharia de Software e Adaptado para Fluxos de Desenvolvimento Solo.
