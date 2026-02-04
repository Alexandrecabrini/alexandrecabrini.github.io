# 🚚 Dashboard Logístico – Transportadora (SSW)

## Visão Geral
Dashboard web desenvolvido em **Python e Streamlit** para análise operacional e financeira
de uma transportadora, com dados integrados diretamente a um banco de dados
**Supabase (PostgreSQL)**.

O projeto tem como objetivo centralizar informações logísticas e financeiras,
facilitando a tomada de decisão baseada em dados confiáveis e atualizados.

---

## Contexto
A transportadora possui grande volume de dados relacionados a:
- Fretes
- Pesos transportados
- Faturamento
- Clientes
- Performance por unidade e período

Antes do dashboard, essas informações não estavam centralizadas,
dificultando análises rápidas e consistentes do negócio.

---

## Problema
- Falta de visão consolidada dos indicadores logísticos
- Dificuldade para acompanhar faturamento e performance
- Análises manuais e pouco escaláveis
- Baixa visibilidade operacional para gestão

---

## Solução
Desenvolvimento de um **dashboard interativo** que consome dados diretamente
do banco **Supabase (PostgreSQL)**, permitindo tratamento, análise e visualização
em tempo real dos dados operacionais.

A aplicação foi projetada desde o início para funcionamento em ambiente web,
com arquitetura preparada para controle de acesso por usuários.

---

## Tecnologias Utilizadas
- Python  
- Streamlit  
- Pandas  
- SQLAlchemy  
- Supabase (**PostgreSQL**)  
- Plotly  

---

## Funcionalidades Atuais
- KPIs de **Faturamento**, **Ticket Médio** e **Peso transportado**
- Ranking dos **Top 20 clientes por faturamento**
- Evolução **diária da receita**
- Filtros dinâmicos por **unidade operacional**
- Visualizações interativas e responsivas

---

## Arquitetura Atual (Simplificada)
1. Dados armazenados no **Supabase (PostgreSQL)**
2. Consulta dos dados via **SQLAlchemy**
3. Tratamento e agregações com **Pandas**
4. Visualizações interativas com **Plotly**
5. Interface web desenvolvida em **Streamlit**

---

## Roadmap (Próximos Passos)
- Implementação de autenticação de usuários
- Controle de acesso por perfil
- Otimização de consultas no banco
- Expansão dos indicadores logísticos e financeiros
- Deploy definitivo em ambiente web

---

## Status do Projeto
🟢 **Em desenvolvimento ativo**

Projeto em evolução contínua, com melhorias sendo implementadas
conforme as necessidades operacionais da transportadora.

📌 *Projeto com dados internos adaptados para fins de portfólio.*
