# 🔍 Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados

Este repositório documenta a experiência prática na aplicação do **Azure Cognitive Search** para organizar, indexar e realizar buscas inteligentes em documentos. Inclui registros das etapas executadas, lições aprendidas e recomendações úteis para implementação de soluções baseadas em **IA para pesquisa e descoberta de dados**.

---

## 🎯 Objetivo

Documentar uma jornada prática com o Azure Cognitive Search, cobrindo:

- Ingestão de dados estruturados e não estruturados
- Indexação de conteúdo com enriquecimento por IA
- Configuração de indexadores, fontes de dados e índices
- Consultas avançadas com filtros, sinônimos e destaque
- Análise de desempenho e relevância dos resultados

---

## 📌 Funcionalidades Exploradas

- 🗃️ Criação de índices com campos pesquisáveis
- 🔗 Conexão com Azure Blob Storage como fonte de dados
- 🧠 Enriquecimento de conteúdo com Skillsets (OCR, detecção de idioma, extração de texto)
- 🧾 Busca textual com análise semântica e fuzzy search
- 🧩 Integração com aplicações externas via REST API e SDK
- 📈 Visualização dos resultados em interfaces customizadas (ex: Power BI, WebApp)

---

## ⚙️ Ferramentas e Recursos Utilizados

- Azure Cognitive Search (nível Standard)
- Azure Portal
- Azure Blob Storage (como repositório de documentos)
- Azure AI Skills integrados (pré-configurados)

---

## ✍️ Etapas Práticas

1. Criação do serviço Azure Cognitive Search
2. Armazenamento de arquivos .pdf e .txt no Blob Storage
3. Criação de:
   - Data source
   - Index
   - Indexer
   - Skillset (OCR, extractKeyPhrases)
4. Execução do processo de indexação
5. Consultas no endpoint de pesquisa
6. Testes com diferentes configurações de relevância e sinônimos

---

## 💡 Aprendizados e Dicas

- O uso de **skillsets com enriquecimento de IA** transforma arquivos brutos em dados pesquisáveis.
- A separação entre **dados, índices e indexadores** permite modularidade e manutenção simplificada.
- É possível customizar campos com **analyzers**, **sinônimos**, e atributos como `sortable`, `filterable`, `facetable`.
- A **consulta semântica** melhora a precisão na busca, mas requer configuração adicional.

---
