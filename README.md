# 🏥 Sistema de Banco de Dados Hospitalar

Projeto acadêmico de banco de dados desenvolvido em MySQL, com o objetivo de simular a estrutura e o gerenciamento de informações de um hospital.

O projeto foi desenvolvido utilizando o MySQL Workbench e contempla a criação e manipulação de tabelas relacionadas a pacientes, médicos, quartos, internações, consultas e prescrições médicas.

Além da estruturação do banco de dados, foram desenvolvidas 10 consultas SQL para extrair informações, realizar cálculos e gerar resultados a partir dos dados cadastrados.

---

## 🛠️ Tecnologias utilizadas
- MySQL — Sistema de gerenciamento de banco de dados.
- MySQL Workbench — Ambiente utilizado para criação, execução e gerenciamento do banco.
- SQL — Linguagem utilizada para criação das tabelas e realização das consultas.
  
##🗄️ Estrutura do Banco de Dados
O banco de dados utilizado no projeto foi denominado hospital_db e possui 6 tabelas principais:
Tabela	Descrição
pacientes	Armazena os dados dos pacientes e seus convênios.
medicos	Armazena os dados dos médicos e suas especialidades.
quartos	Contém informações sobre os quartos hospitalares.
internacoes	Registra as internações, datas e valores das diárias.
consultas	Armazena os registros de consultas médicas.
prescricoes	Registra os medicamentos e suas respectivas dosagens.


As tabelas estão relacionadas por meio de chaves primárias e estrangeiras, garantindo a integridade dos dados e permitindo a realização de consultas utilizando relacionamentos (JOIN).

---

## 📊 Consultas SQL desenvolvidas
Foram elaboradas 10 consultas para atender às situações-problema propostas na atividade acadêmica:
- Faturamento Total de Consultas por Convênio — Calcula o faturamento agrupado por convênio.
- Média do Valor de Consulta por Especialidade Médica — Calcula a média dos valores das consultas por especialidade.
- Valor Médio das Diárias por Tipo de Quarto — Compara os valores médios das diárias entre tipos de quartos.
- Total de Consultas Realizadas por Médico — Calcula o valor total das consultas realizadas por cada médico.
- Soma de Diárias por Paciente com Sobrenome Silva — Identifica o total de diárias dos pacientes com esse sobrenome.
- Contagem de Prescrições por Status da Consulta — Conta prescrições de medicamentos específicos conforme o status da consulta.
- Média de Valor de Consultas por Convênio e Especialidade — Analisa a média dos valores considerando convênios e especialidades.
- Média de Diária de Internação por Convênio em Quartos de UTI — Calcula a média das diárias de pacientes internados em quartos de UTI, agrupada por convênio.
- Medicamentos Prescritos por Médico em Consultas Realizadas — Conta os registros de prescrições associados a cada médico.
- Valor Total e Média de Consultas por Paciente — Calcula o valor total e a média das consultas por paciente.
    
## 🖼️ Resultados das Consultas
Abaixo estão alguns registros dos resultados obtidos durante a execução das consultas no MySQL Workbench.
Consulta 01 — Faturamento por Convênio

Consulta 02 — Média por Especialidade

Consulta 03 — Média das Diárias por Tipo de Quarto

Consulta 04 — Total por Médico

Consulta 05 — Diárias por Pacientes Silva

Consulta 06 — Prescrições por Status

Consulta 07 — Média por Convênio e Especialidade

Consulta 08 — Média de Diárias em UTI por Convênio

Consulta 09 — Prescrições por Médico

Consulta 10 — Total e Média por Paciente

## ▶️ Como executar o projeto
1. Faça o download ou clone este repositório.
2. Abra o MySQL Workbench.
3. Abra o arquivo SQL disponibilizado neste repositório.
4. Execute o script para criar o banco de dados, as tabelas e inserir os registros.
5. Execute as consultas SQL para visualizar os resultados.
   
## 🎯 Objetivo do Projeto
Este projeto teve como objetivo colocar em prática os conhecimentos de modelagem e manipulação de bancos de dados relacionais, utilizando comandos SQL como:
- CREATE DATABASE
- CREATE TABLE
- INSERT INTO
- SELECT
- INNER JOIN
- WHERE
- GROUP BY
- SUM()
- AVG()
- COUNT()
  
Também foram trabalhados conceitos de relacionamentos entre tabelas, chaves primárias, chaves estrangeiras e agregação de dados.

### Consulta 01 — Faturamento por Convênio
![Resultado da Consulta 01](imagens/Captura%20de%20tela%202026-11-05%20110752.png)
### Consulta 02 — Média do Valor de Consulta por Especialidade Médica
![Resultado da Consulta 02](imagens/Captura%20de%20tela%202026-11-05%20111321.png)
### Consulta 03 — Valor Médio das Diárias por Tipo de Quarto
![Resultado da Consulta 03](imagens/Captura%20de%20tela%202026-11-05%20111346.png)
### Consulta 04 — Total de Consultas Realizadas por Médico
![Resultado da Consulta 04](imagens/Captura%20de%20tela%202026-11-05%20111842.png)
### Consulta 05 — Soma de Diárias por Paciente com Sobrenome Silva
![Resultado da Consulta 05](imagens/Captura%20de%20tela%202026-11-05%20111542.png)
### Consulta 06 — Contagem de Prescrições por Status da Consulta
![Resultado da Consulta 06](imagens/Captura%20de%20tela%202026-11-05%20111603.png)
### Consulta 07 — Média de Valor de Consultas por Convênio e Especialidade
![Resultado da Consulta 07](imagens/Captura%20de%20tela%202026-11-05%20111622.png)
### Consulta 08 — Média de Diária de Internação por Convênio em Quartos de UTI
![Resultado da Consulta 08](imagens/Captura%20de%20tela%202026-11-05%20111641.png)
### Consulta 09 — Medicamentos Prescritos por Médico em Consultas Realizadas
![Resultado da Consulta 09](imagens/Captura%20de%20tela%202026-11-05%20111723.png)
### Consulta 10 — Valor Total e Média de Consultas por Paciente
![Resultado da Consulta 10](imagens/Captura%20de%20tela%202026-11-05%20111742.png)
