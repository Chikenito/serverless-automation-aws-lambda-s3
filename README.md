# ⚡ Automatização de Tarefas com AWS Lambda e Amazon S3

![AWS Lambda](https://img.shields.io/badge/AWS-Lambda-orange?style=for-the-badge)
![S3](https://img.shields.io/badge/AWS-S3-blue?style=for-the-badge)
![IaC](https://img.shields.io/badge/Serverless-Automation-green?style=for-the-badge)

---

## 📖 Descrição do Projeto

Este projeto tem como objetivo consolidar conhecimentos em automação de tarefas utilizando **AWS Lambda** em conjunto com **Amazon S3**, aplicando conceitos de arquitetura serverless na AWS.

A proposta é criar uma solução automatizada onde eventos em buckets S3 podem acionar funções Lambda para processamento de dados, transformação de arquivos ou execução de tarefas automatizadas.

---

## 🎯 Objetivos de Aprendizagem

Ao concluir este projeto, foi possível:

- Aplicar conceitos de arquitetura serverless
- Utilizar AWS Lambda para execução de código sem servidores
- Integrar Lambda com Amazon S3
- Entender eventos baseados em triggers
- Automatizar processos na nuvem AWS
- Documentar práticas técnicas em repositório GitHub

---

## ☁️ O que é AWS Lambda?

O AWS Lambda é um serviço serverless da AWS que permite executar código sem provisionar ou gerenciar servidores.

Ele é acionado por eventos, como:
- Upload de arquivos no S3
- Chamadas HTTP via API Gateway
- Eventos de outros serviços AWS

---

## 🪣 O que é Amazon S3?

O Amazon S3 (Simple Storage Service) é um serviço de armazenamento de objetos escalável, usado para guardar arquivos, imagens, backups e dados de aplicações.

Ele pode disparar eventos automaticamente para outros serviços, como o Lambda.

---

## 🔄 Arquitetura da Solução

Fluxo básico implementado:

1. Usuário envia arquivo para o bucket S3  
2. O evento de upload aciona a função AWS Lambda  
3. A Lambda processa o arquivo  
4. Resultado é armazenado ou registrado no S3/logs  

---

## 🧠 Conceitos Aplicados

- Arquitetura Serverless
- Event-driven architecture
- Integração entre serviços AWS
- Automação de tarefas na nuvem
- Escalabilidade automática
- Baixo custo operacional

---

## 🛠️ Tecnologias Utilizadas

- AWS Lambda
- Amazon S3
- AWS IAM
- Python (ou Node.js, dependendo da implementação)
- Git & GitHub

---

## 📁 Estrutura do Repositório

/
├── README.md
├── lambda/
│   └── function.py
├── s3/
│   └── bucket-config.json
├── images/
│   └── arquitetura.png

---

## 🚀 Como Funciona

1. Criar um bucket no Amazon S3
2. Configurar evento de upload no bucket
3. Criar função AWS Lambda
4. Definir permissão IAM para acesso ao S3
5. Testar envio de arquivo
6. Validar execução automática da Lambda

---

## 📌 Principais Aprendizados

- Serverless elimina necessidade de servidores
- Eventos do S3 podem automatizar processos inteiros
- Lambda permite escalabilidade automática
- Integrações AWS reduzem complexidade de sistemas
- Automação melhora eficiência e reduz custos

---

## 📚 Referências

- AWS Lambda Documentation: https://docs.aws.amazon.com/lambda/
- Amazon S3 Documentation: https://docs.aws.amazon.com/s3/
- AWS Serverless Guide: https://aws.amazon.com/serverless/

---

## 👨‍💻 Autor

Projeto desenvolvido como parte de estudos em **AWS Serverless, Lambda e automação com S3**.

---

## 📌 Status do Projeto

✔ Concluído  
✔ Automatizado com AWS Lambda  
✔ Integrado com Amazon S3  
✔ Documentado para portfólio
