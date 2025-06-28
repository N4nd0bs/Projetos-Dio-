# 🗃️ Configurando uma Instância de Banco de Dados na Azure

Este repositório tem como objetivo servir como material de apoio, contendo **resumos, anotações e dicas** sobre o uso da Microsoft Azure — com foco na criação e configuração de **bancos de dados na nuvem**. Ideal para estudos, revisões e futuras implementações em projetos reais.

---

## 🎯 Objetivo

Demonstrar como provisionar uma instância de banco de dados no **Azure Database for SQL**, cobrindo desde as configurações básicas até práticas recomendadas de segurança e desempenho.

---

## 🛠️ Etapas para Configurar um Banco de Dados SQL na Azure

### 1. Acessando o Portal
- Acesse o [Portal Azure](https://portal.azure.com)
- Vá em **"Criar um recurso" > "Bancos de dados" > "Banco de dados SQL"**

### 2. Informações Inseridas para Criação do Banco de Dados
- **Nome do servidor lógico**: `sql-servidor-teste`
- **Nome do banco de dados**: `banco-dados-teste`
- **Região**: `Brazil South`
- **Autenticação**: usuário/senha

### 3. Configurações de desempenho
- **Camada de serviço**: `Basic`
- **Tamanho de armazenamento**: `1GB`

### 4. Regras de firewall
- Adicione o IP local para permitir conexões externas
- Recomendação: restringir IPs autorizados e evitar acesso público irrestrito

### 5. Criação e Conexão
- Após a criação, você pode se conectar via:
  - Azure Data Studio
  - Visual Studio Code (extensão SQL)
  - SQL Server Management Studio (SSMS)
  - Linguagens de programação como Python, Node.js ou C#

---

## 🔐 Boas Práticas

- **Utilize firewalls e redes virtuais para controlar acessos**
- **Habilite auditoria e diagnóstico de logs**
- **Configure backups automáticos com retenção adequada**
- **Use alertas de performance e orçamento**
- **Evite contas com permissões administrativas irrestritas**
