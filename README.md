# SQL-_NoSQL
Compreendendo  o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados.

# Bancos de Dados Relacionais e Não Relacionais para Engenheiros de Dados

## Introdução
Neste repositório, documentarei conceitos sobre Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL), destacando como eles são utilizados no contexto de um Engenheiro de Dados. O objetivo é expandir meu portfólio de conhecimentos sobre essas tecnologias, essenciais para trabalhar com grandes volumes de dados e projetos de Big Data.

## Banco de Dados Relacional (SQL)

**Definição**: Bancos de dados que utilizam tabelas (linhas e colunas) para armazenar dados e a linguagem SQL para realizar consultas e manipulações de dados. Eles seguem um modelo de dados estruturado e relacionamentos entre tabelas.

- **Exemplos**: 
  - MySQL
  - PostgreSQL
  - SQL Server
  - SQLite
- **Vantagens**:
  - Estrutura rígida e organizada.
  - Transações ACID (Atomicidade, Consistência, Isolamento, Durabilidade) garantem integridade dos dados.
  - Relacionamentos bem definidos entre tabelas, garantindo alta integridade de dados.
- **Desvantagens**:
  - Escalabilidade horizontal limitada (dificuldade de expandir a capacidade para mais servidores).
  - Menor flexibilidade para trabalhar com dados não estruturados.
- **Aplicações**:
  - Empresas com dados altamente estruturados, como bancos, sistemas de gestão de recursos empresariais (ERP), e-commerce, etc.

## Banco de Dados Não Relacional (NoSQL)

**Definição**: Bancos de dados que não seguem o modelo relacional, sendo mais flexíveis para armazenar dados não estruturados ou semi-estruturados. Usam diferentes modelos de dados, como documentos, chave-valor, grafos ou colunas.

- **Exemplos**:
  - MongoDB (documento)
  - Cassandra (coluna)
  - Redis (chave-valor)
  - Firebase (documento)
- **Vantagens**:
  - Flexibilidade para trabalhar com dados não estruturados (JSON, XML, etc.).
  - Escalabilidade horizontal, permitindo que a carga de trabalho seja distribuída entre vários servidores.
  - Melhor desempenho em operações rápidas de leitura/gravação em grandes volumes de dados.
- **Desvantagens**:
  - Não garantem a mesma consistência de dados que bancos relacionais (dependendo do tipo de NoSQL).
  - Menor suporte a transações ACID completas.
- **Aplicações**:
  - Big Data, sistemas em tempo real, redes sociais, aplicativos móveis, análise de logs, etc.

## Comparação entre SQL e NoSQL

| Característica           | SQL                          | NoSQL                        |
|--------------------------|------------------------------|------------------------------|
| **Modelo de Dados**       | Tabelas (estruturado)        | Diversos (não estruturado)   |
| **Escalabilidade**        | Vertical (aumenta capacidade de um servidor) | Horizontal (distribui carga entre servidores) |
| **Transações ACID**       | Suporta completamente        | Suporte parcial (dependendo do tipo de NoSQL) |
| **Flexibilidade**         | Menos flexível (dados estruturados) | Mais flexível (dados não estruturados) |
| **Exemplos de Banco de Dados** | MySQL, PostgreSQL, SQL Server | MongoDB, Cassandra, Redis    |

## Papel do Engenheiro de Dados

O Engenheiro de Dados é responsável por projetar e manter a arquitetura de dados da empresa. Entre suas tarefas estão:

- **Escolher a Tecnologia**: Determinar quando usar bancos de dados SQL ou NoSQL com base nas necessidades do projeto, volume de dados e escalabilidade.
- **ETL (Extract, Transform, Load)**: Manipular grandes volumes de dados entre diferentes sistemas e garantir a integridade e a qualidade dos dados.
- **Otimização**: Criar soluções eficientes de armazenamento e acesso a dados, garantindo performance em grandes escalas.

## Conclusão

A escolha entre bancos de dados SQL e NoSQL depende dos requisitos do projeto e do tipo de dados que se deseja armazenar e processar. Bancos de dados relacionais são mais indicados para dados estruturados e com relações complexas entre eles, enquanto bancos de dados NoSQL são ideais para dados não estruturados ou quando a escalabilidade horizontal é crucial.

O domínio de ambos os tipos de banco de dados é fundamental para um Engenheiro de Dados, pois cada um tem suas vantagens dependendo do contexto do projeto.

## Referências

- [Documentação do MySQL](https://dev.mysql.com/doc/)
- [Documentação do MongoDB](https://www.mongodb.com/docs/)
- [Artigo sobre NoSQL vs SQL](https://www.digitalocean.com/community/tutorials)


