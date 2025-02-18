# DevOps Fundamentals - Azure Setup Challenge

Este repositório documenta o processo de configuração de uma infraestrutura básica na Azure, incluindo Service Principal, Resource Group e Storage Account.

## Processo de Configuração

### 1. Criação do Service Principal

#### O Service Principal foi criado com as seguintes configurações:

![Service Principal Overview](./assets/devops-fundamentals-1-service-principal-screen.png)

#### Configuração de certificados e secrets:

![Certificates and Secrets](./assets/devops-fundamentals-2-service-principal-certificates-and-secrets.png)

### 2. Resource Group

#### Criação do Resource Group para hospedar os recursos:

![Resource Group Creation](./assets/devops-fundamentals-3-resource-group.png)

#### Adição de tags para melhor organização:

![Resource Group Tags](./assets/devops-fundamentals-4-resource-group-tags.png)

### 3. Storage Infrastructure

#### Configuração da infraestrutura de armazenamento:

![Storage Infrastructure](./assets/devops-fundamentals-5-resource-group-storageinfrastructure.png)

#### Criação do container de armazenamento:

![Storage Container](./assets/devops-fundamentals-6-resource-group-storageinfrastructure-container.png)

### 4. Azure DevOps Integration

#### Configuração da conexão de serviço no Azure DevOps:

![Service Connection](./assets/devops-fundamentals-7-azure-devops-service-connection.png)

## Requisitos

- Conta ativa na Azure
- Permissões adequadas para criar recursos
- Azure DevOps configurado

## Observações

- Todos os recursos foram criados seguindo as melhores práticas de segurança
- As tags foram aplicadas para melhor gerenciamento de custos e recursos
- O Service Principal possui as permissões mínimas necessárias para operação
