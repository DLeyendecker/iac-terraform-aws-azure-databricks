# Infraestrutura de Dados com Terraform

Este repositório contém exemplos de deploy e automação de infraestrutura de dados utilizando Terraform em ambientes AWS e Azure. Abaixo estão os detalhes dos principais tópicos abordados:

## Estrutura

- **Azure Data Infrastructure Deployment**: Automatiza o deploy de stacks de infraestrutura de dados no Azure utilizando Terraform.
- **Databricks Cluster Deployment**: Implementação e deploy de clusters Databricks com Terraform para processamento distribuído de dados.
- **AWS e Azure Multi-Cloud Deploy**: Integração de infraestrutura multi-cloud, utilizando AWS e Azure, com Terraform para maior flexibilidade e escalabilidade.
- **Automação de Processamento de Dados com AWS EMR e Apache Flink**: Deploy de ambientes de processamento de dados com Amazon EMR e Apache Flink, facilitando a análise de grandes volumes de dados.
- **Deploy de Treinamento Distribuído de Machine Learning com PySpark**: Configuração e deploy de infraestrutura para treinamento distribuído de modelos de Machine Learning com PySpark no Amazon EMR.

## Pré-requisitos

- **Terraform** instalado (versão mínima recomendada: 1.x)
- **Conta AWS** e/ou **Azure** com permissões adequadas
- Ferramentas **CLI da AWS** e **Azure** configuradas (caso necessário)

## Configuração do Terraform

### Para AWS

Antes de usar o Terraform para criar e gerenciar recursos na AWS, é necessário configurar suas credenciais AWS. Você pode fazer isso de várias formas, mas a maneira mais comum é exportar as variáveis de ambiente diretamente no terminal.

#### Passos:

1. Obtenha as credenciais de acesso da AWS:
   - `AWS_ACCESS_KEY_ID`: Sua chave de acesso pública.
   - `AWS_SECRET_ACCESS_KEY`: Sua chave secreta.

2. No terminal, execute os seguintes comandos para exportar suas credenciais como variáveis de ambiente:

```bash
export AWS_ACCESS_KEY_ID="sua-chave-de-acesso"
export AWS_SECRET_ACCESS_KEY="sua-chave-secreta"

