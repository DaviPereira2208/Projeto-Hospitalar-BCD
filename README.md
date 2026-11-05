🏥 Sistema de Banco de Dados Hospitalar
Projeto acadêmico de banco de dados desenvolvido em MySQL, com o objetivo de simular a estrutura e o gerenciamento de informações de um hospital.

O projeto foi desenvolvido utilizando o MySQL Workbench e contempla a criação e manipulação de tabelas relacionadas a pacientes, médicos, quartos, internações, consultas e prescrições médicas.

Além da estruturação do banco de dados, foram desenvolvidas 10 consultas SQL para extrair informações, realizar cálculos e gerar resultados a partir dos dados cadastrados.
🛠️ Tecnologias utilizadas
- MySQL — Sistema de gerenciamento de banco de dados.
- MySQL Workbench — Ambiente utilizado para criação, execução e gerenciamento do banco.
- SQL — Linguagem utilizada para criação das tabelas e realização das consultas.
  
🗄️ Estrutura do Banco de Dados
O banco de dados utilizado no projeto foi denominado hospital_db e possui 6 tabelas principais:
Tabela	Descrição
pacientes	Armazena os dados dos pacientes e seus convênios.
medicos	Armazena os dados dos médicos e suas especialidades.
quartos	Contém informações sobre os quartos hospitalares.
internacoes	Registra as internações, datas e valores das diárias.
consultas	Armazena os registros de consultas médicas.
prescricoes	Registra os medicamentos e suas respectivas dosagens.


As tabelas estão relacionadas por meio de chaves primárias e estrangeiras, garantindo a integridade dos dados e permitindo a realização de consultas utilizando relacionamentos (JOIN).
📊 Consultas SQL desenvolvidas
Foram elaboradas 10 consultas para atender às situações-problema propostas na atividade acadêmica:
1. Faturamento Total de Consultas por Convênio — Calcula o faturamento agrupado por convênio.
2. Média do Valor de Consulta por Especialidade Médica — Calcula a média dos valores das consultas por especialidade.
3. Valor Médio das Diárias por Tipo de Quarto — Compara os valores médios das diárias entre tipos de quartos.
4. Total de Consultas Realizadas por Médico — Calcula o valor total das consultas realizadas por cada médico.
5. Soma de Diárias por Paciente com Sobrenome Silva — Identifica o total de diárias dos pacientes com esse sobrenome.
6. Contagem de Prescrições por Status da Consulta — Conta prescrições de medicamentos específicos conforme o status da consulta.
7. Média de Valor de Consultas por Convênio e Especialidade — Analisa a média dos valores considerando convênios e especialidades.
8. Média de Diária de Internação por Convênio em Quartos de UTI — Calcula a média das diárias de pacientes internados em quartos de UTI, agrupada por convênio.
9. Medicamentos Prescritos por Médico em Consultas Realizadas — Conta os registros de prescrições associados a cada médico.
10. Valor Total e Média de Consultas por Paciente — Calcula o valor total e a média das consultas por paciente.
    
🖼️ Resultados das Consultas
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

▶️ Como executar o projeto
1. Faça o download ou clone este repositório.
2. Abra o MySQL Workbench.
3. Abra o arquivo SQL disponibilizado neste repositório.
4. Execute o script para criar o banco de dados, as tabelas e inserir os registros.
5. Execute as consultas SQL para visualizar os resultados.
   
🎯 Objetivo do Projeto
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
