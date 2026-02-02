# 🤖 Projetos de Automação

## Automação de Captação, Tratamento e Distribuição de Leads (Imobiliária)

**Contexto**  
Imobiliária com múltiplas campanhas no Meta Ads direcionando leads
para atendimento via WhatsApp, utilizando CRM para gestão comercial.

**Fluxo de Entrada dos Leads**  
Campanhas no Meta Ads direcionavam os leads para o WhatsApp da empresa.
A captura dessas informações era realizada por meio da Evolution API,
responsável por coletar os dados das conversas.

Esses dados eram enviados via webhook para o n8n, onde todo o
processamento e tratamento das informações acontecia.

---

**Problema**  
- Leads chegavam sem padronização de dados  
- Dificuldade em rastrear a origem das campanhas  
- Necessidade de organizar os leads em filas corretas dentro do CRM  
- Alto risco de erro manual no processo de distribuição para corretores  

---

**Solução**  
Criação de um fluxo automatizado no n8n para receber os dados via webhook
da Evolution API, tratar e padronizar as informações conforme a
documentação do CRM Facilita.

Dentro do fluxo, também foi implementado o rastreamento das campanhas
por meio de mensagens automáticas recebidas de cada empreendimento,
permitindo identificar corretamente a origem do lead.

Após o tratamento, os dados eram enviados ao CRM Facilita, onde
configurações de filas direcionavam automaticamente os leads para os
corretores responsáveis pelo atendimento.

---

**Ferramentas e Tecnologias**  
- Meta Ads  
- WhatsApp  
- Evolution API  
- Webhook  
- n8n  
- CRM Facilita  

---

**Fluxo da Automação (Resumo)**  
1. Lead entra via campanha no Meta Ads  
2. Contato iniciado no WhatsApp  
3. Captura dos dados via Evolution API  
4. Envio dos dados via webhook para o n8n  
5. Tratamento, padronização e rastreamento de campanha  
6. Envio dos dados para o CRM Facilita  
7. Distribuição automática em filas  
8. Atendimento pelo corretor  

---

**Resultado / Impacto**  
- Leads organizados automaticamente no CRM  
- Rastreabilidade clara da origem das campanhas  
- Distribuição automática e correta para os corretores  
- Redução significativa de retrabalho manual  
- Processo comercial mais rápido e eficiente
