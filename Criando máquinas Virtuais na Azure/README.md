# 💻 Criando Máquinas Virtuais na Microsoft Azure

Este documento registra minha experiência prática com a criação e configuração de **máquinas virtuais (VMs)** na plataforma **Microsoft Azure**, destacando os principais conceitos, etapas e boas práticas aplicadas.

## ☁️ Sobre a Microsoft Azure

**Microsoft Azure** é uma plataforma de computação em nuvem da Microsoft que fornece uma ampla gama de serviços sob demanda — como computação, armazenamento, redes, bancos de dados, inteligência artificial, segurança e muito mais — tudo isso com escalabilidade, alta disponibilidade e alcance global.

### 🧱 Modelos de Serviço na Azure

- **IaaS (Infrastructure as a Service)**  
  Permite provisionar recursos de infraestrutura como servidores virtuais, redes e discos. O controle fica sob responsabilidade do usuário, incluindo sistema operacional e aplicações.  
  **Exemplo**: Criação de máquinas virtuais, balanceadores de carga, firewalls.

- **PaaS (Platform as a Service)**  
  Oferece um ambiente gerenciado para desenvolvimento, teste e implantação de aplicações sem se preocupar com a infraestrutura subjacente.  
  **Exemplo**: Azure App Services, Azure SQL Database, Azure Functions.

- **SaaS (Software as a Service)**  
  Fornece aplicativos prontos para uso consumidos por meio da internet, sem necessidade de instalação ou manutenção.  
  **Exemplo**: Microsoft 365, Power BI, Dynamics 365.

## 🧠 Objetivo

Explorar e dominar o processo de provisionamento de máquinas virtuais na Azure, compreendendo recursos como tipos de instâncias, redes virtuais, discos, imagens, segurança e automação.

## ⚙️ Etapas executadas

1. **Acesso ao portal Azure**
2. **Criação da VM com parâmetros personalizados**
3. **Configuração de rede e segurança**
4. **Armazenamento e discos**
5. **Revisão e criação**
6. **Acesso remoto e testes via SSH**

## 🛡️ Boas práticas aplicadas

- Uso de **chaves SSH** ao invés de senhas para acesso remoto.
- Criação de **grupo de segurança de rede (NSG)** com regras restritivas.
- Escolha de **tamanho de VM econômico** para uso de testes.
- Organização da infraestrutura usando **Grupos de Recursos**.

## 💡 Lições aprendidas

- A importância do isolamento de rede para segurança.
- Como a Azure facilita o provisionamento e a escalabilidade.
