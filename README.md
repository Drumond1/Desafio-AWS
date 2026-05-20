# Relatório de implementação de serviços AWS

```
Data: 20/05/2026
Empresa: Farmácia Mineira
Responsável: Vinicius Drumond
```

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Farmácia Mineira, realizado por Vinicius Drumond. O objetivo do projeto foi elencar 3 serviços AWS que possibilitem a redução imediata de custos, além de preparar a empresa para um crescimento sustentável e seguro no ambiente de nuvem.

## Descrição do Projeto

`O projeto de implementação foi dividido em 3 etapas, cada uma com seus objetivos específicos:`

###Etapa 1:

**Nome da ferramenta:**Amazon Web Services Amazon S3 (Simple Storage Service)

**Foco da ferramenta:**Armazenamento escalável, seguro e de alta durabilidade para dados corporativos.

**Descrição do caso de uso:**
A Farmácia Mineira atualmente mantém seus arquivos e documentos em servidores locais, o que implica elevados custos operacionais, limitações de escalabilidade e maior exposição a falhas físicas. Com a adoção do Amazon S3, será possível centralizar o armazenamento de documentos administrativos, resultados laboratoriais e arquivos de pesquisa em um ambiente de nuvem altamente seguro e resiliente.

O serviço oferece escalabilidade automática, elevada disponibilidade e cobrança baseada no consumo efetivo, proporcionando maior eficiência financeira. Além disso, a utilização de políticas inteligentes de arquivamento, como o S3 Glacier, permitirá a redução adicional de custos para dados de baixa frequência de acesso, mantendo conformidade e integridade das informações armazenadas.

###Etapa 2

**Nome da ferramenta:**Amazon RDS (Relational Database Service)

**Foco da ferramenta:**Gerenciamento otimizado de bancos de dados relacionais com alta disponibilidade.

**Descrição do caso de uso:**
Atualmente, a empresa depende de infraestrutura própria para hospedagem e gerenciamento de bancos de dados internos, gerando despesas significativas com hardware, licenciamento, suporte técnico e manutenção contínua. Com a implementação do Amazon RDS, os bancos de dados responsáveis por operações críticas — como controle de estoque, registros de vendas e cadastro de clientes — poderão ser migrados para um ambiente totalmente gerenciado pela AWS.

A solução automatiza processos essenciais, incluindo backups, atualizações, monitoramento e recuperação de desastres, reduzindo a necessidade de administração manual. Além disso, o serviço proporciona maior segurança, escalabilidade sob demanda e alta disponibilidade, garantindo melhor desempenho operacional e otimização de custos através do modelo de pagamento conforme utilização.

###Etapa 3

**Nome da ferramenta:**Amazon EC2 (Elastic Compute Cloud) com Auto Scaling

**Foco da ferramenta:**Infraestrutura computacional elástica para aplicações corporativas.

**Descrição do caso de uso:**
Os sistemas corporativos da Farmácia Mineira, incluindo ERP e plataformas internas de controle operacional, atualmente executam em servidores físicos com capacidade limitada e alto custo de manutenção. Com a migração para o Amazon EC2, essas aplicações passarão a operar em máquinas virtuais escaláveis e configuráveis conforme a necessidade do negócio.

A integração com o recurso Auto Scaling permitirá o ajuste automático da capacidade computacional de acordo com a demanda de utilização. Em períodos de maior acesso, novos recursos serão provisionados automaticamente para manter a performance dos sistemas. Já em momentos de baixa demanda, os recursos serão reduzidos, promovendo maior eficiência operacional e significativa redução de custos com infraestrutura.

Além da flexibilidade operacional, a solução proporciona maior disponibilidade, tolerância a falhas e rapidez na expansão do ambiente tecnológico da empresa.
## Conclusão

### A implementação das ferramentas na empresa Farmácia Mineira permitirá:

- Redução imediata de custos com infraestrutura física.

- Maior segurança no armazenamento e backup de dados.

- Escalabilidade e alta disponibilidade nos serviços críticos da empresa.

- Eliminação de manutenções complexas em servidores locais.

> Recomenda-se a continuidade da utilização das ferramentas implementadas e a análise de novos serviços AWS, como AWS Lambda (serverless) e Amazon CloudFront (otimização de distribuição de conteúdo), que podem trazer ganhos ainda maiores no futuro.

## Anexos

### 1. Guia de Boas Práticas de Migração para AWS

- Avaliação detalhada do ambiente atual antes da migração.
- Planejamento de etapas e cronograma para minimizar impactos.
- Utilização de ferramentas nativas da AWS para migração segura (AWS Migration Hub, AWS Database Migration Service).
- Testes de integridade e performance após a migração.
- Implementação de políticas de segurança e backup automatizado.

### 2. Comparativo de Custos: Servidores Locais vs AWS

A tabela abaixo apresenta uma análise comparativa dos custos anuais entre a infraestrutura tradicional (on-premise) e a AWS, evidenciando a economia potencial:

| Categoria                  | On-Premise (R$) | AWS (R$) | Economia (R$) |
|----------------------------|-----------------|----------|---------------|
| Armazenamento de Dados     | 12.000          | 4.000    | 8.000         |
| Banco de Dados             | 8.000           | 3.000    | 5.000         |
| Servidores de Aplicação    | 15.000          | 6.000    | 9.000         |
| Energia/Manutenção         | 5.000           | 1.000    | 4.000         |
| Licenciamento de Software  | 4.000           | 1.000    | 3.000         |
| **Total**                  | **44.000**      | **15.000** | **29.000**   |

> **Observação:** Os valores são estimativas anuais e podem variar conforme o uso e a demanda dos serviços.

### 3. Documentação Oficial dos Serviços Utilizados

- [Amazon S3](https://docs.aws.amazon.com/pt_br/s3/index.html)
- [Amazon RDS](https://docs.aws.amazon.com/pt_br/rds/index.html)
- [Amazon EC2](https://docs.aws.amazon.com/pt_br/ec2/index.html)

---
## 👤 Autor

Desenvolvido por **Vinicius Drumond**.
