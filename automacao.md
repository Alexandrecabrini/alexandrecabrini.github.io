# 🤖 Projetos de Automação

Nesta seção estão projetos focados em **automação de processos operacionais e de negócio**,
utilizando integrações via API, scripts em Python e ferramentas low-code.

Os projetos abaixo demonstram como dados são capturados, tratados e organizados
para reduzir trabalho manual, erros operacionais e aumentar eficiência.

---

## 🔹 Automação de Captação e Qualificação de Leads (Imobiliária)

### 📌 Contexto
A imobiliária realizava campanhas no Meta Ads direcionadas para WhatsApp,
porém os leads chegavam de forma desorganizada, sem rastreio de campanha
e sem distribuição automática para os corretores.

---

### 🎯 Problema
- Leads sem identificação de origem
- Falta de rastreio por empreendimento
- Distribuição manual para corretores
- Baixa eficiência no atendimento

---

### ✅ Solução
Desenvolvimento de um fluxo automatizado integrando:

- Campanhas Meta Ads → WhatsApp  
- Captura de mensagens via **Evolution API**
- Recebimento dos dados via **Webhook no n8n**
- Tratamento e padronização conforme documentação do **CRM Facilita**
- Criação de filas automáticas por empreendimento
- Distribuição dos leads para os corretores dentro do CRM

O rastreio das campanhas era feito através de **mensagens automáticas configuradas nos anúncios**,
permitindo identificar origem, empreendimento e campanha.

---

### 🛠️ Tecnologias Utilizadas
- n8n  
- Webhooks  
- Evolution API  
- CRM Facilita  
- Meta Ads  
- WhatsApp  

---

### 📊 Impacto
- Leads organizados automaticamente
- Atendimento mais rápido
- Rastreio completo das campanhas
- Redução de processos manuais

---

## 🔹 Automação de Relatórios Operacionais em Excel com Python (Projeto RORI)

### 📌 Contexto
Este foi meu **primeiro projeto real em Python**, desenvolvido para automatizar
a geração de relatórios operacionais a partir de dados extraídos de arquivos `.txt`.

O processo antes da automação era totalmente manual, sujeito a erros
e demandava tempo excessivo da equipe operacional.

---

### 🎯 Problema
- Extração manual de dados
- Preenchimento repetitivo em planilhas Excel
- Alto risco de erro humano
- Falta de padronização por filial

---

### ✅ Solução
Criação de um **script em Python** que:

- Extrai dados de múltiplos arquivos `.txt`
- Trata e organiza as informações
- Preenche automaticamente uma planilha Excel existente
- Padroniza dados por filial
- Realiza validações de data e observações
- Remove arquivos temporários após a execução

---

### 🛠️ Tecnologias Utilizadas
- Python  
- OpenPyXL  
- Manipulação de arquivos  
- Automação de processos  

---

### 📊 Impacto
- Redução significativa do trabalho manual
- Padronização dos relatórios
- Menor taxa de erro
- Ganho de produtividade operacional

📌 *Projeto com dados internos adaptados para fins de portfólio.*
