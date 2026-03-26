# 📘 Miniguia de Estudo — AWS Cloud Practitioner

## 1. Cloud Concepts

A certificação AWS Cloud Practitioner começa pelos fundamentos da computação em nuvem.

### Principais conceitos
- O que é **cloud computing**
- Benefícios da nuvem
- Proposta de valor da AWS
- Escalabilidade
- Elasticidade
- Infraestrutura global da AWS
- AWS Well-Architected Framework

### Resumo
A computação em nuvem permite utilizar recursos de TI sob demanda, pagando apenas pelo que for usado.  
A AWS oferece serviços escaláveis, com alta disponibilidade, agilidade e flexibilidade.

### Pontos importantes para prova
- Saber explicar o que é computação em nuvem
- Entender a diferença entre escalabilidade e elasticidade
- Conhecer os benefícios da nuvem em relação ao modelo tradicional

---

## 2. Security and Compliance

Este domínio aborda segurança, identidade, acesso e conformidade na AWS.

### Principais conceitos
- Shared Responsibility Model
- IAM
- MFA
- Least Privilege
- AWS Artifact
- Segurança “da” nuvem x segurança “na” nuvem

### Resumo
A AWS é responsável pela segurança **da infraestrutura da nuvem**, enquanto o cliente é responsável pela segurança **dos recursos, acessos, dados e configurações** dentro da nuvem.

### Pontos importantes para prova
- Saber explicar o Shared Responsibility Model
- Entender a função do IAM
- Saber o papel do MFA
- Entender o princípio do menor privilégio

---

## 3. Cloud Technology and Services

Este domínio reúne os principais serviços da AWS.

---

### 3.1 Compute

#### Serviços principais
- **Amazon EC2** → servidores virtuais
- **AWS Lambda** → execução de código sem servidor
- **Amazon ECS** → gerenciamento de contêineres

#### Resumo
Esses serviços atendem diferentes necessidades de computação:

- **EC2** → mais controle
- **Lambda** → menos gerenciamento
- **ECS** → foco em contêineres

---

### 3.2 Storage

#### Serviços principais
- **Amazon S3** → armazenamento de objetos
- **Amazon EBS** → armazenamento em bloco
- **Amazon EFS** → sistema de arquivos compartilhado

#### Resumo
- **S3** → ideal para arquivos, backups, imagens e dados não estruturados
- **EBS** → funciona como disco rígido de uma instância EC2
- **EFS** → funciona como pasta compartilhada entre várias instâncias

---

### 3.3 Database

#### Serviços principais
- **Amazon RDS** → banco de dados relacional
- **Amazon DynamoDB** → banco de dados NoSQL

#### Resumo
- **RDS** → ideal para aplicações relacionais tradicionais
- **DynamoDB** → ideal para aplicações altamente escaláveis com baixa latência

---

### 3.4 Networking

#### Serviços principais
- **Amazon VPC**
- **Amazon Route 53**

#### Resumo
- **VPC** → rede virtual isolada dentro da AWS
- **Route 53** → serviço de DNS da AWS

### Pontos importantes para prova
- Saber diferenciar os serviços por categoria
- Entender o caso de uso principal de cada serviço
- Evitar confusão entre serviços parecidos

---

## 4. Billing, Pricing and Support

Este domínio aborda custos, planejamento financeiro e suporte na AWS.

### Principais conceitos
- Pay-as-you-go
- AWS Pricing Calculator
- AWS Cost Explorer
- AWS Budgets
- AWS Support Plans

### Resumo
A AWS utiliza um modelo de **pagamento conforme o uso**, permitindo que o cliente pague apenas pelos recursos consumidos.

### Diferenças importantes
- **Pricing Calculator** → usado para **estimar custos futuros**
- **Cost Explorer** → usado para **analisar custos já ocorridos**
- **AWS Budgets** → usado para **monitorar limites e alertas de gastos**
- **Support Plans** → oferecem diferentes níveis de suporte técnico

### Pontos importantes para prova
- Saber diferenciar ferramentas de custo
- Entender o modelo de cobrança da AWS
- Saber o objetivo dos planos de suporte

---

# ✅ Resumo Final
A AWS Cloud Practitioner é uma certificação introdutória, mas exige clareza conceitual sobre:

- fundamentos da nuvem
- segurança
- serviços principais
- custos e suporte

O estudo por domínios, com apoio do NotebookLM, ajudou a transformar documentação oficial em um material mais direto, compreensível e útil para revisão.
