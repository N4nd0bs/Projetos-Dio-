# 📊 Utilizando Prompts para Gerar Insights de Relatórios de Vendas

Este repositório reúne **prompts e respostas** aplicados à base de dados `Meganium_Sales_Data.csv`, demonstrando como a utilização de ferramentas com **inteligência artificial generativa** pode acelerar e ampliar a análise de relatórios de vendas.

---

## 🎯 Objetivo

Explorar como **prompts bem construídos** podem ser usados para:

- Analisar dados de vendas automaticamente
- Gerar resumos inteligentes a partir de bases CSV
- Obter rankings, agrupamentos e análises por país, produto, moeda etc.
- Facilitar a tomada de decisão com base em insights contextuais

---

## 🧠 Base de Dados

A base `Meganium_Sales_Data.csv` inclui colunas como:

- Produto vendido
- Data da venda
- Quantidade
- Valor unitário e total
- Moeda
- País de entrega
- Informações do comprador e cupom de desconto

---

## 💬 Prompts Aplicados e Respostas

### Prompt 1
> **"Quais foram os produtos mais vendidos em cada país?"**

**Resposta da IA:**
A IA agrupou os dados por país (`delivery_country`) e somou as quantidades (`quantity`) por produto, retornando a seguinte tabela:

| País        | Produto mais vendido           | Quantidade Total Vendida |
|-------------|-------------------------------|---------------------------|
| Reino Unido | NEW MEGANIUM RG 40XXV         | 20 unidades               |
| Canadá      | NEW MEGANIUM RG 40XXV         | 13 unidades               |
| EUA         | MEGANIUM RG353M              | 13 unidades               |
| Austrália   | MEGANIUM RG353M              | 11 unidades               |
| França      | NEW MEGANIUM RG35XX          | 7 unidades                |

---

### Prompt 2
> **"Me informe agora o produto com maior faturamento por país."**

**Resposta da IA:**
A IA somou o `total_price` por produto e país, identificando o produto com maior valor total:

| País        | Produto                          | Faturamento Total |
|-------------|----------------------------------|-------------------|
| Reino Unido | NEW MEGANIUM RG 40XXV           | £1.000,00          |
| Canadá      | NEW MEGANIUM RG 40XXV           | £1.100,00+         |
| EUA         | MEGANIUM RG353M                | $1.210,00          |
| França      | NEW MEGANIUM RG35XX            | €450,00            |

---

### Prompt 3
> **"Me informe o faturamento total de cada país convertido em dólar americano."**

**Resposta da IA:**
Utilizando taxas de câmbio aproximadas:

- 1 EUR ≈ 1.08 USD
- 1 GBP ≈ 1.26 USD

A IA retornou:

| País        | Faturamento (USD) |
|-------------|-------------------|
| Reino Unido | $3,603.60         |
| Canadá      | $1,588.80         |
| EUA         | $1,210.00         |
| Austrália   | $1,158.60         |
| França      | $486.00           |
| Alemanha    | $450.00           |

---

## ⚙️ Benefícios do Uso de IA com Prompts

- 🚀 Velocidade na análise de dados complexos
- 🧠 Geração automática de agrupamentos e rankings
- 🔍 Facilidade para testar hipóteses com perguntas em linguagem natural
- 💡 Apoio a decisões com dados contextualizados e interpretados
- ✨ Aumento da produtividade na geração de relatórios

---

## 🧩 Ferramentas Envolvidas

- Microsoft Copilot
- CSV importado via prompt
- Técnicas de agregação, conversão de moeda e sumarização com IA generativa

---
