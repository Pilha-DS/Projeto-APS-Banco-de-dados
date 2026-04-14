# Projeto-APS-Banco-de-dados

## Descrição
Este repositório contém o desenvolvimento do **Projeto APS (Atividade Prática Supervisionada)** da disciplina de **Banco de Dados**.  

O objetivo do projeto é modelar e implementar um banco de dados para uma **indústria**, onde cada integrante do grupo é responsável por um setor específico da empresa.

---

## Contexto do Projeto
A base de dados representa o funcionamento de uma **empresa industrial**, contemplando diferentes áreas essenciais para sua operação.  

Cada setor foi modelado de forma forma indivual por cada grupo, porem conjunta na finalizacao.

---

## Integrantes e Setores

|------------------|--------------------------|
| Integrante       | Setor                    |
|------------------|--------------------------|
| Isabelle         | Compras                  |
| Luiz             | Financeiro               |
| Marcelle         | Custos                   |
| Hugo Martins     | Estoque                  |
| Soler            | Vendas                   |
| Salsicha         | Contabilidade            |
| Nicole           | Qualidade                |
| Felipe           | Recursos Humanos (RH)    |
| Vinicius         | Controle de Produção     |
|------------------|--------------------------|

---

## Estrutura do Banco de Dados

O banco de dados foi dividido em módulos correspondentes aos setores da empresa:

- 🛒 **Compras**: gestão de fornecedores, pedidos de compra e recebimento de materiais  
- 💰 **Financeiro**: controle de contas a pagar e a receber  
- 📉 **Custos**: apuração de custos de produção e produtos  
- 📦 **Estoque**: controle de entrada, saída e armazenagem de produtos  
- 🛍️ **Vendas**: registro de pedidos, clientes e faturamento  
- 📚 **Contabilidade**: registros contábeis e demonstrações  
- ✅ **Qualidade**: controle de qualidade de produtos e processos  
- 👥 **RH**: gestão de funcionários e departamentos  
- 🏭 **Controle de Produção**: planejamento e acompanhamento da produção  

---

## Objetivos

- Modelar um banco de dados relacional completo  
- Aplicar conceitos como:
  - Modelo Entidade-Relacionamento (MER)
  - Normalização
  - Integridade referencial
- Simular o funcionamento de uma empresa real  
- Integrar diferentes setores em um único sistema  

---

## Tecnologias Utilizadas

- SQL (Structured Query Language)  
- Sistema Gerenciador de Banco de Dados (SGBD) *(MySQL)*  
- Ferramentas de modelagem (ex: MySQL Workbench, BRModelo, etc.)  

---

## Estrutura do Repositório

/Projeto-APS-Banco-de-dados
│
├── docs/ # Documentação do projeto
├── modelagem/ # Diagramas MER e DER
├── scripts/ # Scripts SQL (DDL e DML)
├── dados/ # Dados de teste
└── README.md # Este arquivo

---

## Status do Projeto

🚧 Em desenvolvimento  

---

## Observações

- Todos os setores foram pensados com base em uma **indústria**, garantindo maior coerência entre os módulos de acordo com decio(professor).  
- O projeto é colaborativo, e cada integrante é responsável pela modelagem e implementação do seu respectivo setor.  
