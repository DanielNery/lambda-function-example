# Projeto de Exemplo para Funções Lambda na AWS
Bem-vindo ao Projeto de Exemplo para Funções Lambda na AWS! Este é um guia passo-a-passo para ajudá-lo a criar e implantar suas funções Lambda na Amazon Web Services (AWS). Este projeto de exemplo é uma base sólida para começar a desenvolver suas próprias funções serverless na AWS.

## Estrutura do Projeto
```
├── .github
│   ├── workflows 
│       ├── main.yml
├── src
│   ├── lambda_function.py
├── requirements.txt
├── README.md
```

+ src/lambda_function.py: Este é o arquivo Python que contém a lógica principal da sua função Lambda. Você pode personalizá-lo de acordo com suas necessidades.

+ requirements.txt: Lista as dependências do Python necessárias para sua função Lambda. Certifique-se de listar todas as dependências aqui.

+ main.yaml: Este é o arquivo Github Action que descreve sua infraestrutura serverless, incluindo a definição da função Lambda e quaisquer recursos associados automaticamente.

## Pré-requisitos
Antes de começar, você precisa ter as seguintes ferramentas instaladas e configuradas:

AWS CLI: Certifique-se de ter a AWS CLI instalada e configurada com suas credenciais. Para instalar, siga as instruções em Installing the AWS CLI.

SAM CLI: Instale o AWS Serverless Application Model (SAM) CLI seguindo as instruções em Installing the AWS SAM CLI.

## Como Usar
### Clone este repositório:

```
git clone https://github.com/DanielNery/lambda-function-example.git
cd lambda-function-example
```

### Instale as dependências:

```
pip install -r requirements.txt -t src/
```

### Implante o projeto na AWS:

sam deploy --guided
Siga as instruções interativas para configurar a implantação.

Você pode confirgurar as variveis de ambiente no repositório para realizar deploy automático.

Após a implantação bem-sucedida, você receberá a URL da sua função Lambda. Use esta URL para invocar sua função.

Testando Localmente
Você pode testar sua função Lambda localmente usando o SAM CLI:


sam local invoke
Isso invocará sua função Lambda localmente para testes rápidos e depuração.

Contribuindo
Se você encontrar problemas ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Esperamos que este projeto de exemplo seja útil para começar com o desenvolvimento de funções Lambda na AWS. Boa codificação!
