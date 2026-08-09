# Tottenham Hotspur 2024/25 — Business Intelligence Dashboard

---

# Dashboard

<p align="center">

<img width="1286" height="731" alt="image" src="https://github.com/user-attachments/assets/35f67a4e-ff0d-4c13-bf5f-0fb97314617a" />


</p>

---

# Sobre o projeto

Este projeto consiste na construção de uma solução completa de Business Intelligence para análise da temporada **2024/25 do Tottenham Hotspur**.

Diferente da primeira versão do dashboard, este projeto foi totalmente reconstruído, contemplando desde a coleta dos dados até a modelagem dimensional em banco de dados relacional.

Todo o fluxo foi desenvolvido simulando um cenário real de BI utilizado em empresas.

---

# Objetivos

- Praticar SQL Server
- Modelagem dimensional
- Construção de Data Warehouse
- Consultas SQL
- Power BI
- Storytelling com dados
- Visualização de indicadores

---

# Pipeline do Projeto

```text
                FBref
                  │
                  ▼
         Coleta dos dados
                  │
                  ▼
          SQL Server Database
                  │
     ┌────────────┴────────────┐
     ▼                         ▼
Tabela Fato              Tabelas Dimensão
     │                         │
     └────────────┬────────────┘
                  ▼
          Modelagem Power BI
                  │
                  ▼
          Dashboard Final
```
---

# Modelagem do Banco de Dados

O projeto foi estruturado utilizando modelagem dimensional.

## Tabelas Fato

- FATO_JOGOS
- FATO_ARTILHARIA

## Dimensões

- DIM_COMPETICAO
- DIM_DATA
- DIM_JOGADOR
- DIM_OPONENTE
- CALENDARIO

---

## Modelo Relacional

<p align="center">

<img width="1296" height="637" alt="image" src="https://github.com/user-attachments/assets/f2b516dd-074f-4d62-a76c-8934ded19503" />


</p>

---

# SQL Server

Toda a estrutura do banco foi construída no SQL Server.

Foram desenvolvidas consultas para:

- criação das tabelas
- carga dos dados
- consultas analíticas
- agregações
- integração com o Power BI

<p align="center">

<img width="1197" height="430" alt="image" src="https://github.com/user-attachments/assets/3228f39b-2d5b-4b58-8380-3d5ab12f8ce0" />


</p>

---

# Indicadores

O dashboard apresenta indicadores como:

✅ Jogos

✅ Gols Marcados

✅ Gols Sofridos

✅ Vitórias

✅ Empates

✅ Derrotas

✅ Gols por Jogo

✅ Resultados Temporada

✅ Artilheiros

✅ Desempenho por competição

---

# Tecnologias

- SQL Server
- Power BI
- Power Query
- DAX

---

# Fonte dos dados

Todos os dados foram obtidos através do

**FBref**

https://fbref.com/

---

# Principais aprendizados

Durante o desenvolvimento deste projeto foram aplicados conceitos de:

- Modelagem Dimensional
- Star Schema
- SQL
- DAX
- Storytelling
- Data Visualization
- Business Intelligence
- Power BI

---

# Próximas evoluções

- Atualização automática dos dados
- Novas páginas analíticas
- Estatísticas por jogador
- Publicação no Power BI Service

---

# Autor

**Lays Roberta da Silva**

LinkedIn:
www.linkedin.com/in/lays-roberta-silva

GitHub:
https://github.com/LaysRobertaS


