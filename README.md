# SQLNotebookLM

Aqui está a estrutura completa e pronta para o seu arquivo **`README.md`**, formatada para documentar este projeto no GitHub:

```markdown
# 🗄️ Estudos Avançados e Fundamentais de SQL

> *"No SQL, a recuperação e a filtragem de dados estruturam-se em torno de cláusulas e operadores fundamentais que definem quais colunas buscar, de qual tabela extrair e quais condições os registros devem atender."*

---

## 🎯 Tema e Objetivo

O projeto tem como objetivo consolidar o aprendizado prático e conceitual sobre **Structured Query Language (SQL)** e a evolução dos sistemas de bancos de dados modernos. O escopo abrange desde as operações essenciais de manipulação e filtragem relacional (DQL/DML) até padrões arquiteturais avançados, como a especificação **ISO/IEC 9075:2023 (SQL:2023)**, o ecossistema de **Distributed SQL / NewSQL** (CockroachDB, Spanner, TiDB, YugabyteDB) e indexação vetorial de alta dimensionalidade (**pgvector**).

---

## 📚 Fontes Utilizadas e Critérios de Confiabilidade

O notebook foi alimentado com 27 fontes criteriosamente selecionadas, divididas em três pilares:

### 1. Normas e Documentações Oficiais de Referência
* **ISO/IEC 9075-16:2023 (SQL/PGQ - Property Graph Queries)** e comunicados da **Oracle Blogs** e **Wikipedia**.
* **PostgreSQL Documentation (Appendix D. SQL Conformance)**.
* **Por que confiamos:** São os documentos normativos e primários mantidos pelos comitês internacionais de padronização (ISO/IEC e ANSI) e pelos núcleos oficiais dos principais SGBDs relacionais de código aberto e corporativos.

### 2. Engenharia de Sistemas Distribuídos e Arquitetura NewSQL
* Artigos técnicos e benchmarks da **Cockroach Labs** (*CockroachDB vs Google Spanner*, *Distributed DB*), **PingCAP / TiDB** (*Scalability Meets Consistency*), **YugabyteDB** (*6 Technical Challenges Developing a Distributed SQL Database*), **Conduktor**, **Rapydo** e **AWS Pro Cert**.
* **Por que confiamos:** Produzidos pelos times de engenharia e arquitetos de software que constroem, mantêm e operam em escala global as tecnologias de consenso distribuído (Raft, Paxos, TrueTime, Spanner/Calvin).

### 3. Cursos Práticos, Otimização e Indexação
* **Dev Aprender** (*Curso SQL Completo 2025*), **Stack Mobile** (*Curso Completo de SQL com PostgreSQL*), **Código Fonte TV** (*Minicurso de SQL*), **Jerry Strazzeri** (*SQL Saia do Zero em Apenas Uma Aula*).
* Livros e referências de performance: *Use The Index, Luke!* (Markus Winand / Reddit / rieckpil) e tutoriais práticos de *pgvector vs. Dedicated Vector Databases* (MachineLearningMastery).
* **Por que confiamos:** Referências didáticas e práticas consolidadas da comunidade de dados, trazendo casos de uso reais de produção, boas práticas de modelagem e resolução de desafios de consultas.

---

## ⚙️ Diretriz de Comportamento (System Prompt / Nota)

Para guiar as respostas, raciocínios técnicos e análises das fontes, foi definida no notebook a seguinte instrução:

```text
Se comporte como um especialista em SQL
```

---

## ❓ Perguntas Realizadas e Respostas Geradas

### Pergunta 1:
> *"Como funcionam os comandos básicos para consultar e filtrar dados no SQL?"*

* **O que foi respondido:**
  * **Projeção e Origem:** Funcionamento das cláusulas estruturais `SELECT` e `FROM`, uso do curinga `*` vs. especificação de colunas e remoção de duplicatas com `SELECT DISTINCT`.
  * **Filtros com `WHERE`:** Aplicação de operadores de comparação (`=`, `<>`, `!=`, `>`, `<`, `>=`, `<=`) e lógica booleana (`AND`, `OR`, `NOT`).
  * **Operadores Especiais:** Busca por padrões com `LIKE` (curingas `%` e `_`), checagem de faixas inclusivas com `BETWEEN` e correspondência em conjuntos finitos ou subconsultas com `IN`.
  * **Apresentação dos Resultados:** Ordenação crescente/decrescente com `ORDER BY [ASC|DESC]` e controle de paginação e corte de volume com `LIMIT` (PostgreSQL/MySQL) e `TOP` (SQL Server).
* **Fontes principais que fundamentaram:** Cursos práticos e tutoriais em vídeo (*Stack Mobile*, *Dev Aprender*, *Código Fonte TV*, *Jerry Strazzeri*).

---
## 🔗 Link do Notebook Compartilhado

* **Acesse o Notebook:** [Link do Notebook Compartilhado](https://notebook.google.com/notebook/e000b447-3977-4ee4-87ec-452694b5e125)
```

---

💡 Se você quiser, posso gerar uma descrição curta pronta para a seção *"About"* do repositório no GitHub ou sugerir tags/tópicos para indexá-lo.
