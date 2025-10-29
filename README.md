# aws-lambda-s3-automation
Projeto de automação na AWS utilizando S3 Object Lambda e CloudFormation. Criei um modelo para automatizar a configuração e integrei uma função Lambda com S3, testando a execução automatizada de tarefas com arquivos zipados.
# 🚀 Automação com AWS S3 Object Lambda e CloudFormation

## 📘 Descrição
Este projeto tem como objetivo **automatizar a configuração do AWS S3 Object Lambda** utilizando um modelo do **AWS CloudFormation**, além de demonstrar o uso de **funções AWS Lambda** para executar tarefas automatizadas com **arquivos .zip armazenados no S3**.

O projeto foi desenvolvido como parte do **Bootcamp AWS da DIO**, reforçando práticas de automação, infraestrutura como código e integração entre serviços na nuvem.

---

## 🧩 Tecnologias e recursos utilizados
- **Amazon S3**
- **AWS Lambda**
- **AWS CloudFormation**
- **AWS IAM Roles**
- **AWS CLI**

---

## ⚙️ Estrutura do projeto
---

## 🪜 Etapas realizadas

1. Criação de um bucket no **Amazon S3** para armazenar os arquivos do projeto.  
2. Upload de um arquivo `.zip` contendo o código da **função Lambda**.  
3. Criação de um modelo **CloudFormation (template.yaml)** para automatizar toda a configuração do ambiente.  
4. Implantação do **stack** via CloudFormation.  
5. Testes de execução da **Lambda Function** integrada ao S3 Object Lambda.  

---

## 🧠 Aprendizados

Durante o desenvolvimento deste desafio, aprimorei meus conhecimentos em:
- Automação de infraestrutura com **CloudFormation (IaC)**;  
- Integração entre **S3 e Lambda**;  
- Configuração de **permissões e papéis (IAM)**;  
- Implantação e testes de funções **Lambda automatizadas**.  

Esse processo mostrou como é possível simplificar tarefas repetitivas e garantir mais eficiência em ambientes na nuvem.

---

## 📸 Capturas de tela

  ## 🖼️ Capturas de tela do projeto

### 1️⃣ Autenticação Root
![AWS Root Login](.<img width="1290" height="2796" alt="image" src="https://github.com/user-attachments/assets/627d8549-7370-4d94-bed9-7212392a6f51" />
)  
Tela de autenticação mostrando acesso Root na conta AWS utilizada para o desafio.

### 2️⃣ Bucket S3
![S3 Bucket])  <img width="1290" height="2796" alt="image" src="https://github.com/user-attachments/assets/c9f9a73e-43fb-4c27-97bc-ed7c3d736bd3" />

Bucket criado com sucesso no Amazon S3 para armazenar os arquivos do projeto Lambda.

### 3️⃣ Função Lambda
![Lambda Config] <img width="2796" height="1290" alt="image" src="https://github.com/user-attachments/assets/652863b3-f1a9-4221-bcd4-ce1dfa98a3b2" />
 
Função Lambda configurada com runtime Node.js 22.x e pacote ZIP.

### 4️⃣ CloudFormation
<img width="1290" height="2796" alt="image" src="https://github.com/user-attachments/assets/d438e130-e56a-438e-9fcf-068178056f55" />

Painel do CloudFormation utilizado para configurar automações e stacks da AWS.

---

## 💬 Autor

Projeto desenvolvido por **Jessica Lopes** 💻  
Bootcamp **AWS - DIO** | 2025  
[https://www.dio.me](https://www.dio.me)

---

⭐ Se este projeto te inspirou, não esqueça de deixar uma estrela no repositório!
