# Teste prático com Application Gateway Ingress Controller

Repositório para criação de ambiente para testes com o Application Gateway Ingress Controller.

Os seguintes recursos são criados no Azure:
* Grupo de recurso
* Rede virtual (vnet)
* Azure Container Registry (Opcional)
* Service Principal
* Azure Kubernetes Service
* IP público
* Application Gateway

A infraestrutura acima pode ser criada a partir de modificações no arquivo azure_create.azcli na pasta azure resources. Para rodar os comandos é necessário utilizar o [Azure CLI](https://docs.microsoft.com/pt-br/cli/azure/install-azure-cli?view=azure-cli-latest).

Repositório do AGIC: https://github.com/Azure/application-gateway-kubernetes-ingress.

