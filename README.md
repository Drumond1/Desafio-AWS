# Relatório de Implementação de Serviços AWS

```text
Data: 20/05/2026
Empresa: Farmácia Mineira
Responsável: Vinicius Drumond
```

---

# Sumário

1. Introdução
2. Objetivos do Projeto
3. Descrição do Projeto

   * Etapa 1 — Amazon S3
   * Etapa 2 — Amazon RDS
   * Etapa 3 — Amazon EC2 com Auto Scaling
4. Benefícios Esperados
5. Segurança e Conformidade
6. Resultados Esperados
7. Conclusão
8. Anexos
9. Autor

---

# 1. Introdução

Este relatório apresenta a proposta de implementação de soluções em nuvem utilizando serviços da AWS (Amazon Web Services) na empresa Farmácia Mineira. O projeto tem como objetivo modernizar a infraestrutura tecnológica da organização, reduzir custos operacionais, aumentar a segurança das informações e proporcionar maior escalabilidade para os sistemas corporativos, garantindo suporte ao crescimento sustentável da empresa.

A adoção de serviços em nuvem permitirá que a empresa substitua parte da infraestrutura física atualmente utilizada por soluções gerenciadas, escaláveis e com alta disponibilidade, promovendo maior eficiência operacional e otimização de recursos financeiros.

---

# 2. Objetivos do Projeto

* Reduzir custos com infraestrutura física e manutenção de servidores locais;
* Melhorar a disponibilidade e desempenho dos sistemas corporativos;
* Garantir maior segurança e integridade dos dados empresariais;
* Automatizar processos de backup, monitoramento e escalabilidade;
* Modernizar o ambiente tecnológico da empresa;
* Preparar a infraestrutura para crescimento futuro e expansão dos serviços digitais.

---

# 3. Descrição do Projeto

O projeto de implementação foi dividido em 3 etapas estratégicas, cada uma com objetivos específicos voltados à modernização da infraestrutura tecnológica da Farmácia Mineira.

---

## Etapa 1 — Amazon S3 (Simple Storage Service)

### Foco da ferramenta

Armazenamento escalável, seguro e de alta durabilidade para dados corporativos.

### Descrição do caso de uso

A Farmácia Mineira atualmente mantém arquivos e documentos em servidores locais, o que gera elevados custos operacionais, limitações de escalabilidade e maior exposição a falhas físicas e perda de dados.

Com a implementação do Amazon S3, será possível centralizar o armazenamento de documentos administrativos, relatórios internos, resultados laboratoriais e arquivos de pesquisa em um ambiente de nuvem altamente seguro, resiliente e escalável.

O serviço oferece durabilidade de **99,999999999%**, além de alta disponibilidade e cobrança baseada no consumo efetivo, permitindo maior eficiência financeira. A utilização de políticas inteligentes de arquivamento, como o S3 Glacier, possibilitará a redução adicional de custos para arquivos de baixa frequência de acesso, mantendo conformidade, integridade e segurança das informações armazenadas.

### Principais benefícios

* Redução de custos com armazenamento físico;
* Backup automatizado;
* Alta disponibilidade dos dados;
* Escalabilidade automática;
* Maior segurança no armazenamento de informações críticas.

---

## Etapa 2 — Amazon RDS (Relational Database Service)

### Foco da ferramenta

Gerenciamento otimizado de bancos de dados relacionais com alta disponibilidade.

### Descrição do caso de uso

Atualmente, a empresa depende de infraestrutura própria para hospedagem e gerenciamento de bancos de dados internos, gerando despesas significativas com hardware, licenciamento, suporte técnico e manutenção contínua.

Com a implementação do Amazon RDS, os bancos de dados responsáveis por operações críticas — como controle de estoque, registros de vendas, cadastros de clientes e relatórios gerenciais — poderão ser migrados para um ambiente totalmente gerenciado pela AWS.

A solução automatiza processos essenciais, incluindo:

* Backups automáticos;
* Atualizações de segurança;
* Monitoramento contínuo;
* Replicação;
* Recuperação de desastres.

Além disso, o serviço proporciona maior segurança, escalabilidade sob demanda e alta disponibilidade, garantindo melhor desempenho operacional e otimização de custos através do modelo de pagamento conforme utilização.

### Principais benefícios

* Eliminação da manutenção manual de bancos de dados;
* Redução de custos operacionais;
* Alta disponibilidade;
* Escalabilidade automática;
* Segurança avançada e backups automatizados.

---

## Etapa 3 — Amazon EC2 (Elastic Compute Cloud) com Auto Scaling

### Foco da ferramenta

Infraestrutura computacional elástica para aplicações corporativas.

### Descrição do caso de uso

Os sistemas corporativos da Farmácia Mineira, incluindo ERP e plataformas internas de controle operacional, atualmente executam em servidores físicos com capacidade limitada e elevado custo de manutenção.

Com a migração para o Amazon EC2, essas aplicações passarão a operar em máquinas virtuais escaláveis e configuráveis conforme a necessidade do negócio, permitindo maior flexibilidade operacional e melhor aproveitamento dos recursos computacionais.

A integração com o recurso Auto Scaling permitirá o ajuste automático da capacidade computacional de acordo com a demanda de utilização. Em períodos de maior acesso, novos recursos serão provisionados automaticamente para manter a performance dos sistemas. Já em momentos de baixa demanda, os recursos serão reduzidos, promovendo maior eficiência operacional e significativa redução de custos com infraestrutura.

Além da flexibilidade operacional, a solução proporcionará:

* Maior disponibilidade;
* Tolerância a falhas;
* Rápida expansão da infraestrutura;
* Melhor desempenho dos sistemas corporativos.

### Principais benefícios

* Redução de custos com servidores físicos;
* Escalabilidade automática;
* Melhor desempenho das aplicações;
* Alta disponibilidade;
* Flexibilidade operacional.

---

# 4. Benefícios Esperados

Com a implementação das soluções AWS, a Farmácia Mineira poderá obter os seguintes benefícios:

* Maior confiabilidade dos sistemas corporativos;
* Redução de riscos relacionados a falhas físicas;
* Melhor controle e previsibilidade de custos com TI;
* Escalabilidade sob demanda;
* Maior produtividade da equipe técnica;
* Melhor desempenho das aplicações;
* Facilidade de expansão futura da infraestrutura;
* Maior segurança e integridade dos dados corporativos.

---

# 5. Segurança e Conformidade

Durante a implementação das soluções em nuvem, serão aplicadas boas práticas de segurança e conformidade utilizando recursos nativos da AWS, incluindo:

* Controle de acesso com IAM (Identity and Access Management);
* Criptografia de dados em repouso e em trânsito;
* Backup automatizado;
* Monitoramento contínuo com Amazon CloudWatch;
* Controle de logs e auditoria com AWS CloudTrail;
* Aplicação de políticas de acesso restritivo;
* Gerenciamento seguro de credenciais e permissões.

Essas medidas garantirão maior proteção às informações corporativas e conformidade com boas práticas de segurança da informação.

---

# 6. Resultados Esperados

Com a implementação das soluções propostas, estima-se:

* Redução de aproximadamente 65% nos custos de infraestrutura;
* Aumento da disponibilidade dos sistemas corporativos;
* Redução do tempo de manutenção de servidores;
* Maior velocidade no acesso às informações;
* Maior confiabilidade e segurança dos dados;
* Melhor desempenho operacional da empresa;
* Maior capacidade de expansão tecnológica futura.

---

# 7. Conclusão

Conclui-se que a adoção dos serviços AWS proporcionará à Farmácia Mineira uma infraestrutura moderna, segura e escalável, alinhada às melhores práticas de computação em nuvem.

Além da redução significativa de custos operacionais, a implementação permitirá maior eficiência na gestão dos recursos tecnológicos, aumento da disponibilidade dos sistemas e fortalecimento da segurança da informação.

A modernização da infraestrutura tecnológica também contribuirá para maior flexibilidade operacional, melhoria contínua dos serviços corporativos e preparação da empresa para futuras demandas de crescimento.

Recomenda-se a continuidade da estratégia de transformação digital da empresa, avaliando futuramente a adoção de serviços complementares da AWS, como AWS Lambda, Amazon CloudFront e Amazon CloudWatch, visando otimização contínua da performance, segurança e custos operacionais.

---

# 8. Anexos

## 8.1 Guia de Boas Práticas de Migração para AWS

* Avaliação detalhada do ambiente atual antes da migração;
* Planejamento de etapas e cronograma para minimizar impactos;
* Utilização de ferramentas nativas da AWS para migração segura;
* Testes de integridade e performance após a migração;
* Implementação de políticas de segurança e backup automatizado;
* Monitoramento contínuo da infraestrutura em nuvem.

### Ferramentas recomendadas

* AWS Migration Hub;
* AWS Database Migration Service (DMS);
* AWS CloudWatch;
* AWS CloudTrail.

---

## 8.2 Comparativo de Custos — Servidores Locais vs AWS

| Categoria                 | On-Premise (R$) | AWS (R$)   | Economia (R$) |
| ------------------------- | --------------- | ---------- | ------------- |
| Armazenamento de Dados    | 12.000          | 4.000      | 8.000         |
| Banco de Dados            | 8.000           | 3.000      | 5.000         |
| Servidores de Aplicação   | 15.000          | 6.000      | 9.000         |
| Energia/Manutenção        | 5.000           | 1.000      | 4.000         |
| Licenciamento de Software | 4.000           | 1.000      | 3.000         |
| **Total**                 | **44.000**      | **15.000** | **29.000**    |

> **Observação:** Os valores apresentados são estimativas anuais e podem variar de acordo com o consumo, utilização dos serviços e crescimento da infraestrutura.

---

## 8.3 Documentação Oficial dos Serviços Utilizados

* [Amazon S3 Documentation](https://docs.aws.amazon.com/pt_br/s3/index.html?utm_source=chatgpt.com)
* [Amazon RDS Documentation](https://docs.aws.amazon.com/pt_br/rds/index.html?utm_source=chatgpt.com)
* [Amazon EC2 Documentation](https://docs.aws.amazon.com/pt_br/ec2/index.html?utm_source=chatgpt.com)

---

# 9. Autor

**Desenvolvido por Vinicius Drumond**
Projeto de implementação de soluções em nuvem utilizando serviços AWS para modernização da infraestrutura tecnológica da Farmácia Mineira.
