# 🧠 Análise de Sentimentos com Language Studio no Azure AI

Este repositório tem como objetivo documentar a experiência prática com as ferramentas **Azure Language Studio** e **Azure Speech Studio**, focando na análise de sentimentos, reconhecimento de entidades, análise de texto e fala. Serve como material de apoio para estudos, revisões e futuras implementações envolvendo **linguagem natural (NLP)** e **processamento de fala** com inteligência artificial.

---

## 🎯 Objetivo

- Experimentar a análise de sentimentos, entidades e idioma com Azure Language Studio
- Explorar funcionalidades de transcrição e conversão de fala com Azure Speech Studio
- Documentar os passos, aprendizados, desafios e recomendações práticas

---

## 🔍 Ferramentas Exploradas

### 🔹 Azure Language Studio
- Análise de sentimentos (classificação positiva, negativa, neutra)
- Extração de entidades nomeadas (pessoas, locais, datas, organizações)
- Detecção de idioma
- Extração de frases-chave
- Análise de opiniões vinculadas

### 🔹 Azure Speech Studio
- Conversão de fala em texto (STT)
- Análise de entonação e prosódia
- Personalização de modelos acústicos e linguísticos
- Geração de voz com voz neural (Text-to-Speech)
- Análise de expressividade da fala

---

## 🧠 Sobre o uso das ferramentas

- Speech Studio e Language Studio têm interfaces intuitivas, ideais para testes rápidos.
- Transcrição de fala (STT) funciona melhor com áudio limpo, sem ruído.
- A análise de sentimentos responde bem a contextos mais literais; ironias não são facilmente compreendidas.
- Ao combinar fala + linguagem, é possível extrair valor emocional e semântico de interações reais.
- Resultados variam entre idiomas: o modelo em inglês é geralmente mais robusto que em português.

---

## 💡 Insights e Aprendizados

- **Sentiment Analysis** é mais eficaz em frases completas com contexto emocional explícito.
- **Speech Studio** fornece transcrição quase em tempo real com boa acurácia para voz clara e microfone de qualidade.
- A configuração do idioma e região afeta diretamente a precisão dos modelos.
- A API REST do Azure permite automatizar a análise sem depender do portal gráfico.
- **Combinar análise de fala (Speech Studio) com análise textual (Language Studio)** gera insights ricos sobre intenção, emoção e semântica.
- O uso de **chaves de recurso e endpoints personalizados** torna o processo flexível para integração com aplicações externas.

---

## ✍️ Recomendações

- Use frases completas para obter análises de sentimentos mais confiáveis.
- Combine os estúdios com automações via API para maior produtividade.
- Utilize logs para entender melhor os acertos e falhas da IA em suas respostas.

---

## ⚙️ Exemplo de Workflow Combinado

1. Gravar entrada de voz do usuário.
2. Usar o Azure Speech Studio para transcrever fala em texto.
3. Aplicar Azure Language Studio no texto transcrito para:
   - Detectar sentimento geral
   - Identificar entidades presentes
   - Destacar palavras-chave

---

## 🔐 Considerações de Segurança

- Dados sensíveis devem ser ofuscados ou anonimizados antes da análise.
- Políticas de retenção e privacidade da Microsoft devem ser consideradas em ambientes corporativos.
- Recomendável utilizar planos pagos com SLA para aplicações críticas.

---
