# DYNAMODB

Banco de dados NoSQL totalmente gerenciado pela AWS.

## Conceitos Principais
- NoSQL (Key-Value)
- Baixa latência
- Escalabilidade automática
- Alta disponibilidade
- Serverless

## Estrutura
- Table
- Partition Key
- Sort Key (opcional)
- Items e Attributes

## Casos de Uso
- Aplicações serverless
- Jogos online
- Sistemas em tempo real
- Grandes volumes de leitura/escrita

## Boas Práticas
- Definir bem a Partition Key
- Evitar hot partitions
- Usar índices secundários (GSI/LSI)
- Monitorar consumo (RCU/WCU)
