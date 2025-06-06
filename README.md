# 🌿 BioSentinela – Monitoramento Inteligente com Oracle e Java

Projeto acadêmico desenvolvido para a disciplina **Mastering Relational and Non-Relational Database** da FIAP, com foco em banco de dados Oracle, procedures, funções, cursores e integração com aplicação Java Spring Boot.

## 📘 Descrição

O sistema **BioSentinela** foi idealizado para monitorar sensores ambientais em regiões sensíveis. Sensores de temperatura e fumaça são associados a regiões e geram alertas que são processados, armazenados e visualizados de forma inteligente.

As informações são manipuladas por meio de **procedures SQL** e **funções personalizadas**, com **cursores** e **blocos anônimos** utilizados para gerar relatórios e análises.

---

## 🧱 Estrutura do Projeto

- **Banco de Dados Oracle**:
  - Criação de 4 tabelas normalizadas (`Usuário`, `Região`, `Sensor`, `Alerta`)
  - Constraints: `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `UNIQUE`

- **Procedures**:
  - Para cada tabela: `INSERT`, `UPDATE`, `DELETE`
  - Testadas com `EXEC` e `SELECT`

- **Funções**:
  - `FUN_TOTAL_ALERTAS_POR_REGIAO`
  - `FUN_RISCO_ALERTA_SENSOR`

- **Blocos Anônimos**:
  - 1 com estrutura `IF/ELSE` para risco
  - 1 com `CURSOR` e `LOOP` para relatório de alertas por sensor

- **Consultas Relacionais**:
  - JOIN, GROUP BY, HAVING, COUNT, SUBQUERIES
  - 5+ relatórios úteis (sensores sem alerta, últimos 30 dias, total por tipo, etc.)

- **Java (Spring Boot)**:
  - Integração com o banco Oracle
  - API REST para manipulação das entidades (região, sensor, alerta)
  - Repositórios JPA conectando-se às tabelas criadas

---

## 🖼️ Prints e Estrutura

Todas as etapas da entrega foram organizadas em pastas com prints:
- `Criação de Tabelas`
- `Procedures e Inserts`
- `Funções e IF`
- `Cursor e Loop`
- `Consultas Relacionais`
- `Modelagem` (Relacional e Lógico via Data Modeler)

---

## 📹 Vídeo de Demonstração

✅ O vídeo mostra a criação e execução de cada parte do projeto + a API Java funcionando com o banco Oracle.

🔗 **Link do vídeo:** 

---

## 🛠️ Tecnologias Utilizadas

- Oracle SQL Developer
- Oracle Database
- Java 17
- Spring Boot 3
- JPA / Hibernate
- Swagger

---

## ✅ Entrega 

- [x] Modelagem Relacional (3FN)
- [x] Criação de Tabelas com Restrições
- [x] Procedures DML por tabela (3x cada)
- [x] Duas Funções
- [x] Dois Blocos Anônimos
- [x] Cursores com LOOP
- [x] 5+ Consultas SQL Relacionais
- [x] Integração com Projeto Java
- [x] Prints organizados
- [x] Vídeo gravado

---




