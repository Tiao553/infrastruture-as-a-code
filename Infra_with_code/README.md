# Instruções para montagem da sua infraestrutura como código de
---

# Primeiramente vamos as definições: O que são infraestruturas?

Infraestruturas são modelos de segmentação e suporte que garatem o bom funcionamento de sistemas e eles podem ser bem variados. Especificamente neste repositório visaremos a infraestrutura de TI e como monta-la por meio de código.

## **Infraestruturas TI**

Esta infraestrutura tem por base modelos preventivos do fluxo de dados e aplicações em seu ecosistema. Onde o encarregado deve saber de tecnicas de *DevOps e TI* para que desenvolva tecnicas e testes de cada aplicação ou código inserido no sistema além do seu monitoramento. 

###  Para construção desta infraestrutura o encarregado deve:

> Saber de tecnicas de engenharia de dados ou software
> Aplicar boas práticas
> Garantir a segurança e o acesso das informações.

## O que são **Boas Práticas**:

Um dos objetivos da infraestrutura como código é garantir a segurança de toda sua pipeline, para isso existe algumas **Boas práticas** que nos ajudam a garantir esse objetivo. A ferramenta que iremos utilizar para este gerenciamento é AWS IAM e em sua documentação ja nos concede algumas dessa [boas práticas](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).

1. CONCEDA PRIVILÉGIO MÍNIMO SEMPRE.
2. ABUSE DA CRIAÇÃO DE GRUPOS PARA ESCALONAR AS PERMISSÕES.
3. ANALISE OS EVENTOS QUE ESTÃO ACONTECENDO
4. VALIDE SUAS POLITICAS.
---

---

# Quando dizemos "montagem de infraestrutura como código" vamos efetuar as seguintes etapas:

1. Criar ambientes de armazenamento
   > AWS S3, AWS Redshift, AWS RDS (postgreSQL)
2. Gerir permições e criação de roles e User's acess
   > Automatizar arquiteturas de permições com AWS IAM
3. Realizar testes das aplicações antes da realização do deployments
   > Inicialmente boas práticas de Unit Tests
4. Criar uma arquitetura de Continuous Monitoring = versionamento + CI + CDelivery + CDeployment
   > Github Actions

   > Jinja templates

   > AWS CDK
5. Garantir a integração de ferramentas que irão tratar as informações.
   > Spark, Airflow, DataBricks, AWS Glue, AWS athena, AWS SageMaker
# HANDS-ON

Para aplicar estes conceitos vamos realizar duas abordagens:

## Primeira: Com cloudformation em conjunto a inserção de templates no site da AWS.

## Segundo: Automatizando a inserção destes templates com um deploy via Github Actions.

## Terceiro: Criando automações com Jinja e subindo estes templates.

## Quarta: Criando toda essa automação via AWS CLI por meio do serviço do CDK.
