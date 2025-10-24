# 🧵 Projeto Python — Template Padrão

> 🧠 Este repositório serve como **modelo base** para iniciar projetos em **Python**, aplicando **boas práticas de engenharia de software, documentação viva e metodologia ágil adaptada** para trabalho individual.

---

## 🧭 1. Objetivo

Fornecer uma estrutura organizada e reutilizável para projetos em Python, com:

- Planejamento, registro e documentação integrados;  
- Separação clara entre código, testes e documentação;  
- Suporte à integração contínua (GitHub Actions);  
- Fluxo de trabalho baseado em sprints e melhoria contínua.

---

## ⚙️ 2. Estrutura de Diretórios

```
📦 seu-projeto/
├── README.md
├── PCR.md
├── planejamento.md
├── CHANGELOG.md
├── requirements.txt
├── .gitignore
│
├── 📁 docs/
├── 📁 src/
│   ├── main.py
│   └── core/
│       ├── controllers/
│       ├── models/
│       ├── views/
│       └── services/
│
├── 📁 tests/
│   ├── test_unit/
│   └── test_integration/
│
└── 📁 .github/
    ├── ISSUE_TEMPLATE.md
    ├── PULL_REQUEST_TEMPLATE.md
    └── workflows/
        └── ci.yml
```

>🔎 Consulte `PCR.md` para detalhes técnicos e planejamento.md para acompanhamento das sprints e metodologia.

## 🚀 3. Configuração Inicial
### 3.1 Criar ambiente virtual
```bash
python3 -m venv venv
source venv/bin/activate  # Linux
venv\Scripts\activate     # Windows
```

### 3.2 Instalar dependências
```bash
pip install -r requirements.txt
``` 

### 3.3 Executar testes
 
``` bash
pytest
```

### 🧠 4. Metodologia e Gestão
Este projeto utiliza metodologia ágil adaptada para desenvolvedores individuais, com foco em:
- Sprints curtos (1 semana ou 10 dias);
- Documentação e revisão contínua;
- Registro de aprendizados e decisões técnicas;
- Planejamento incremental e revisões constantes.

>💬 Consulte `planejamento.md` para detalhes sobre sprints, backlog e retrospectivas.

## 🧩 5. Contribuição e Workflow
Mesmo em projetos individuais, o fluxo de colaboração deve seguir boas práticas:
1. Criar uma branch para cada nova feature ou correção;
2. Abrir uma issue descrevendo a tarefa;
3. Realizar commit seguindo convenções claras (`feat:`, `fix:`, `docs:` etc.);
4. Enviar Pull Request para revisão antes do merge;
5. Atualizar `CHANGELOG.md` e documentação quando necessário.

## 📚 6. Documentação Técnica
A documentação está centralizada na pasta docs/ e é gerada de forma contínua com pdoc ou mkdocs.

| Documento            | Finalidade                         |
| -------------------- | ---------------------------------- |
| `arquitetura.md`     | Estrutura e decisões arquiteturais |
| `design_patterns.md` | Padrões de projeto utilizados      |
| `testes.md`          | Estratégia de testes e cobertura   |
| `referencias.md`     | Leituras e materiais de apoio      |


## 🧾 7. Licença
Este repositório template é de uso livre para fins educacionais e profissionais.
Sinta-se à vontade para adaptá-lo aos seus projetos.

>✨ Template desenvolvido com base em boas práticas de Engenharia de Software, Clean Code e gestão ágil individual.