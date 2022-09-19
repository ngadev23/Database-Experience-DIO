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




