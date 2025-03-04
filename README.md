# Infraestrutura de Dados com Terraform

Este repositório contém exemplos de deploy e automação de infraestrutura de dados utilizando Terraform em ambientes AWS e Azure. 

## Estrutura

- **Azure Data Infrastructure Deployment**: Deploy de stacks de infraestrutura de dados no Azure.
- **Databricks Cluster Deployment**: Deploy de clusters Databricks para processamento distribuído de dados.
- **AWS e Azure Multi-Cloud Deploy**: Integração multi-cloud utilizando AWS e Azure.
- **Automação de Processamento de Dados com AWS EMR e Apache Flink**: Deploy de ambientes com EMR e Apache Flink para processamento de grandes volumes de dados.
- **Deploy de Treinamento Distribuído de Machine Learning com PySpark**: Infraestrutura para treinamento distribuído de modelos com PySpark no Amazon EMR.

## Pré-requisitos

- **Terraform** (versão mínima recomendada: 1.x)
- **Conta AWS** e/ou **Azure** com permissões adequadas

## Como Usar

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-repositorio/infraestrutura-dados-terraform.git
    ```

2. Configure suas credenciais de AWS ou Azure, conforme necessário:
    - Para AWS, exporte as variáveis de ambiente `AWS_ACCESS_KEY_ID` e `AWS_SECRET_ACCESS_KEY`.
    - Para Azure, execute `az login`.

3. Execute os comandos Terraform para inicializar e aplicar o plano:
    ```bash
    terraform init
    terraform apply
    ```

## Contribuindo

Contribuições são bem-vindas! Abra uma issue ou envie um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
