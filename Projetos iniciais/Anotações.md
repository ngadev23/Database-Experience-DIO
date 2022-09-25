# **Anotações**

[Clique aqui para retornar ao repositório](https://github.com/ngadev23/Database-Experience-DIO)

> ## **Big Data**
 - Velocidade
 - Variedade
 - Volume


> ## **O que são Banco de Dados?**

### Dados >> São Fatos
### Dados Relacionados >> Database >> Significado

&nbsp;
> # **SGBDs**

![sgbds](https://leonardofnsca.files.wordpress.com/2021/03/sgbdmercado.png?w=350)

- Definição 
   - Tipos de Dados
   - Estrutura
   - constrains
- Construção
   - Inserção de Dados
- Manipulação
   - Recuperação
   - Relatórios
   - Query
- Compartilhamento
  - Simultaneidade
  - Acesso

O SGBD é um software modular

&nbsp;
### **MySQL: SGBD open source**

&nbsp;
#### HPC vs BIG DATA

- Processa - Processa e armazena
- Sistema de arquivos paralelos sem persistência/ com persistência
- Acesso: HFF5 eNetCDF/ 
- Modelos: MPI, OpenMP, OpenCL / MapReduce, Spark, SGBDs paralelos

&nbsp;
> # **SGBDs NoSQL**
- **Orientado à Documentos:**  mongo DB

- **Orientado à Colunas:** Cassandra

- **Orientado à Key-Value:** redis (Escrito em C)

- **Orientado à Grafos:** neo4j (Escrito em Java)

- **Orientado à Objetos:** db4objects 

&nbsp;
> # **Abordagens de BDs**

## Por que utilizar SGDBs?

&nbsp;

- **Abstração:** através da abstração consegue determinar a estrutura dos dados e manipular as informações. A abstração traz algo específico para o geral
&nbsp;

- **Isolamento:** Manutenção dos dados e sistemas (Catálogo)
- **Múltiplas Visões:**
- **Auto-descrição:** ele possui uma descrição específica e concisa do BD dentro no sistema >> Descrição da estrutura e constrains >> DB Schema >> Metadados & Schemas
- **Compartilhamento:** facilidade em compartilhar dados e informações em diversos grupos distintos
- **Transação Multiuser**

&nbsp;
> # **Compartilhamento de Dados e Processamento de Trasações multiusuários**

## Concurrency Control: Controle de Concorrência
Permite que vários usuários acessem ao mesmo tempo sem que haja inconsistência dos dados do SGBD

&nbsp;

> **OLTP:** Online Transation Processing

**Transaction-Driven:**
- Processamento de Dados 
- operacional

&nbsp;


> **OLTP vs OLAP**

Online Transaction Prcessgin | Online Analytical Processing
Ambiente Operacional | Ambiente Informativo

&nbsp;

## **Abordagens do Banco de Dados**

**Atores**

- Design do Banco de Dados (BD Design)
   - Identificar dados e requisitos
   - Representação e Estrutura
   - Fase Preliminar

- Administrador do Bando de Dados (DBA)
   - Gerenciar os recursos do banco de dados
   - Orquestração
   - Autorização de Acesso

- Usuários Finais
   
&nbsp;
> ## **Vantagens dos SGBDs**

- Controle de Redundância
- Restrição de Acesso
- Storage - Provê persistência
- Storage - Provê Estrutura
- Back up e Recovery

> # **Introdução a Modelagem de Banco de Dados SQL**

&nbsp;
## Modelagem
- foco na descrição
- relacionamento dos elementos

**Processo de Modelagem**
- Mini-mundo: delimita o contexto dos dados
- Alto nível: Requisitos para criação modelo
- Esquema: Definir estrutura relacional (E-R)
- SGBD: Criando o BD (Implementação)

> # **Arquitetura de BD**

- Modelo
- Esquemas
- Instâncias

> Abstração = Essencial

Trazer o mundo real para o banco de dados

*Modelo de BD está atrelado a estrutura*

- **Modelos de Dados Conceitual:** Visão de alto nível
   - Entidade
   - Atributos
   - Relacionamento
   - Modelo E-R
- **Modelo de Dados  de Implementação:** Representacional
   - Modelo de dados relaciona
   - Modelos hierárquicos
- **Modelo de Dados Físico:** Especialista
   - Índices
   - Hashes

*Esquema*
- Diagramas: Descrição
- Instência | Ocorrência
- Snapshot
- Descrição de Dados
- Meta dados
   - Descrição esquema
   - Contructs
   - Constrains

*Linguagens para SGBD*

- DDL: Data Definition Language
- Separação Eplíxita:
   - SDL: Stored Definition Language: Persistência dos dados
   - VDL: Views Definition Language
- DML: Data Manipulation Language

*Interfaces de SGBDs*

- Naive
- DBA
      

*Utilities - Gerenciamento*
- Loading
- Backup
- Reorganização do Storage
- Monitoramento


*Classificação dos SGBDs*
- Parâmetros
   - modelos de dados: SQL, noSQL
   - nº usuários
   - nº sites
   - custos
   - tipo de caminho de acesso
- Performance
   - OLTP
- Relacional
   - Coleção de Tabelas
   - Alto nível

   # PARA O README
   DESIGN DE BDs
   IMPLEMENTAÇÃO DE MODELO
   APLICAÇÕES DE SGBDs
   EXEMPLO DE APLICAÇÕES

> *Mundo Fechado*
   - tudo o que está dento do BD é verdadeiro

> *Mini Mundo*
   - Está dentro do mundo real, é a parte do mundo real que se quer modelar
   - O BD armazena a partir do modelo lógico o mini mundo

   > Álgebra Relacional

   Conjunto de operações
   - op. de Conjuntos
   - Op. de BD Relacional

> Processo de Criação de SGBD
- Projeto conceitual
- Projeto lógico
- Projeto físico
- Produção
- Manutenção


