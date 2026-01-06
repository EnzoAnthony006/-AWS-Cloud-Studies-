# SISTEMAS DE ARQUIVOS NA NUVEM (Amazon EFS)

Sistema de arquivos elástico e totalmente gerenciado pela AWS, permitindo compartilhamento de dados entre múltiplas instâncias EC2 em diferentes zonas de disponibilidade.

## Conceitos Principais
- Network File System (NFS)
- Alta disponibilidade (Multi-AZ)
- Escalabilidade automática
- Totalmente gerenciado
- Integração com EC2

## Arquitetura
- Amazon VPC
- Amazon EC2
- Amazon EFS
- EFS Mount Targets por Availability Zone

## Implementação
- Criação de um sistema de arquivos Amazon EFS
- Configuração de mount targets em múltiplas AZs
- Montagem do EFS em instâncias EC2
- Compartilhamento de arquivos entre instâncias

## Casos de Uso
- Aplicações distribuídas
- Compartilhamento de arquivos
- Ambientes de desenvolvimento
- Sistemas que exigem armazenamento persistente

## Boas Práticas
- Criar mount targets em todas as AZs
- Configurar corretamente os Security Groups
- Monitorar throughput e latência
- Controlar permissões de acesso aos arquivos
