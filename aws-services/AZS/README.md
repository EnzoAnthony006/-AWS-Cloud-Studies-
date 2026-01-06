# Aplicativos Web de Alta Disponibilidade na AWS

Este repositório documenta a implementação de uma arquitetura de **aplicação web altamente disponível** utilizando serviços gerenciados da **Amazon Web Services (AWS)**, seguindo boas práticas de escalabilidade, resiliência e monitoramento.

## 🏗️ Arquitetura

A solução distribui a aplicação em **múltiplas Zonas de Disponibilidade (AZs)**, garantindo tolerância a falhas e alta disponibilidade.

### Serviços AWS Utilizados

- **Amazon Route 53** – Gerenciamento de DNS
- **Amazon CloudFront** – CDN para entrega de conteúdo
- **Amazon S3** – Armazenamento de conteúdo estático
- **Elastic Load Balancing (Application Load Balancer)** – Balanceamento de carga
- **Amazon EC2** – Instâncias de aplicação
- **Auto Scaling Group (ASG)** – Escalabilidade automática
- **Amazon RDS (Multi-AZ)** – Banco de dados relacional altamente disponível
- **Amazon CloudWatch** – Monitoramento e métricas

### Diagrama da Arquitetura

![Arquitetura AWS](./architecture.png)

---

## 🎯 Objetivos do Laboratório

Neste laboratório prático, você aprenderá a:

- Configurar um **Application Load Balancer**
- Criar e associar um **Auto Scaling Group**
- Configurar **health checks** do Load Balancer
- Distribuir instâncias EC2 em **múltiplas Zonas de Disponibilidade**
- Garantir **alta disponibilidade do banco de dados** com Amazon RDS Multi-AZ
- Monitorar recursos usando **Amazon CloudWatch**

---

## 🚀 Fluxo da Aplicação

1. Usuários acessam a aplicação via **Route 53**
2. O tráfego é acelerado pelo **CloudFront**
3. Conteúdo estático é servido pelo **Amazon S3**
4. Requisições dinâmicas passam pelo **Application Load Balancer**
5. O ALB distribui o tráfego entre instâncias EC2 em múltiplas AZs
6. A aplicação acessa o **Amazon RDS** com failover automático

---

## 🛡️ Benefícios da Arquitetura

- Alta disponibilidade
- Escalabilidade automática
- Balanceamento de carga inteligente
- Tolerância a falhas de zona
- Melhor performance global
- Monitoramento contínuo

---

## 📚 Referência

Laboratório baseado no **AWS Skill Builder – Centro de Soluções AWS**.

---

## 🧑‍💻 Autor

Projeto educacional para estudos de arquitetura em nuvem com AWS.
