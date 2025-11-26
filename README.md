Sistema desenvolvido com emus colegas da faculdade

# 🏗️ Sistema Integrado de Gestão de Obras, Estoque e Compras  
### 📊 Com Suporte Analítico em Power BI  
### 📘 Projeto Integrado – UNIFEOB (Novembro)

---

## 👥 Integrantes do Grupo
- **Cauã Wilian Pereira** – RA: 25000693  
- **Leonardo da Silva Fonseca** – RA: 25000517  
- **Mateus Leandro Silva** – RA: 25000610  
- **Maria Fernanda de Almeida Lopes Borges** – RA: 25002085  

---

## 📌 Sobre o Projeto
Este repositório contém o Projeto Integrado do módulo de **Modelagem de Dados e Business Intelligence**, desenvolvido para apoiar empresas do setor de construção civil na gestão de:

- Obras e etapas
- Estoque e consumo de materiais
- Compras e fornecedores
- Equipes e alocação de funcionários

A solução inclui:

- Modelagem completa de **banco de dados** (Conceitual, Lógico e Físico)  
- Implementação real em **MySQL**
- Dashboards analíticos em **Power BI**
- Relatório técnico detalhado
- Demonstração e documentação para apresentação

---

## 🎯 Objetivos

### ✔️ Objetivo Geral
Criar uma solução integrada para gestão operacional e análise estratégica, utilizando banco de dados relacional e dashboards profissionais.

### ✔️ Objetivos Específicos
- Modelar e estruturar o banco de dados conforme boas práticas.  
- Mapear entidades essenciais: obras, compras, materiais, equipes e fornecedores.  
- Implementar KPIs e indicadores críticos no Power BI.  
- Fornecer visualizações intuitivas para tomada de decisão.  
- Minimizar inconsistências operacionais e melhorar o controle de estoque e custos.

---

## 🧱 Modelagem do Banco de Dados

### 🔹 Entidades Principais
- **Obra**  
- **Etapa**  
- **Fornecedor**  
- **Compra**  
- **Compra Item**  
- **Material**  
- **Movimentação de Material**  
- **Equipe**  
- **Funcionário**  
- **Alocação de Equipe**

### 🔹 Regras de Negócio
- Saídas de material possuem quantidade negativa.  
- Estoque atual = soma das movimentações.  
- Cada compra pertence a uma obra e a um fornecedor.  
- Cada obra possui etapas planejadas e executadas.  
- Equipes podem ser alocadas em múltiplas obras.

### 📁 Script Físico
O arquivo `.sql` contendo TODAS as tabelas e relacionamentos está disponível em:

```

/database/estoque_db.sql

```

---

## 📊 Dashboards Desenvolvidos em Power BI

O arquivo **estoque_pi.pbix** inclui análise completa com:

### 🔹 Dashboard Geral de Obras
- Obras ativas e concluídas  
- Comparação entre previsão e execução  
- Custo acumulado por obra  
- Linha do tempo das etapas  

### 🔹 Dashboard de Estoque e Materiais
- Materiais abaixo do mínimo  
- Valor total em estoque  
- Consumo por obra  
- Entradas × saídas  

### 🔹 Dashboard de Compras
- Total investido  
- Fornecedor mais relevante  
- Itens mais comprados  
- Ranking de gastos por obra  

Arquivo disponível em:

```

/powerbi/estoque_pi.pbix

```

---

## 🛠️ Tecnologias Utilizadas
- **MySQL 8.0**  
- **Power BI Desktop**  
- **SQL**  
- **GitHub**  
- **Microsoft Excel (apoio de dados)**  

---

## 📁 Estrutura do Repositório
```

/
├── database/
│   └── estoque_db.sql
│
├── powerbi/
│   └── estoque_pi.pbix
│
├── docs/
│   ├── relatorio_tecnico.docx
│   └── imagens_dashboard/
│
└── README.md

```

---

## 📈 Resultados Obtidos
- Banco de dados robusto e aplicável ao contexto real da construção civil.  
- Dashboard profissional com KPIs valiosos para tomada de decisão.  
- Detecção facilitada de gargalos, desperdícios e falta de materiais.  
- Visão estratégica integrada sobre obras, estoque, compras e equipes.  
- Ganho significativo de organização e clareza operacional.

---

## 📚 Referências
- UNIFEOB – Material de Orientação do Projeto Integrado  
- Kimball, Ralph. *Data Warehouse Toolkit*  
- MySQL Documentation  
- Microsoft – *Power BI Documentation*  
- Date, C.J. – *Introduction to Database Systems*  

---

## 🚀 Agradecimento
Projeto desenvolvido como parte do módulo de **Modelagem de Dados e BI**, integrando conhecimento prático e teórico para solução de problemas reais.

