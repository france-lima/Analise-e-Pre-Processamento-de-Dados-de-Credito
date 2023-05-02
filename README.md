# Análise e Pré-Processamento de Dados de Credito
# Sumário
* [Descrição do projeto](#descrição-do-projeto)
* [Project description](#project-description)
* [Linguagens e tecnologias usadas](#linguagens-e-tecnologias-usadas)
* [Bibliotecas usadas](#bibliotecas-usadas)

# Descrição do projeto
Este repositório apresenta um MVP(Minimum Viable Product) elaborado como avaliação para a Sprint I do curso de pós-Graduação em Ciência de Dados e Analytics da Pontifícia Universidade Católica do Rio de Janeiro (PUC-RIO).
O projeto envolve a análise e pré-processamento dos relatórios de crédito do período de 2022 disponibilizados pelo Banco Central com a finalidade de investigar prováveis efeitos da pandemia sobre o perfil da indinplência no Brasil, considerando, principalmente, os ativos de crédito classificados pelo Banco Central como "problemáticos". 
Os ativos são considerados ativos problemáticos quando é constatado pelo menos um dos seguintes eventos:
  I - operações de crédito em atraso há mais de 90 (noventa) dias;
  II - a existência de indicativos de que a obrigação não será integralmente honrada sem que seja necessário recurso a garantias ou a colaterais (Para o BCB estes         indicativos ocorrem quando a operação é objeto de reestruturação e a instituição financeira reconhece contabilmente deterioração significativa da qualidade do crédito   do   tomador, classificando-o entre os níveis de risco E e H).
Embora não utlizemos técnicas de machine learning nessa tarefa, a base de dados utilizada foi escolhida devido à sua adequação para o futuro desenvolvimento de um modelo preditivo do risco de eventual inadimplência. Talvez, um provável desdobramento futuro deste projeto. 
A hipótese principal a qual iremos testar é de que em 2022 houve uma ocorrência maior de ativos de crédito considerados problemático entre indivíduos de camadas economicamente mais pobres relacionada, sobretudo, a modalidade de crédito de habitação. Sendo que, para tal, além de analisarmos o período de 2022, nos concetraremos nos dados do S1, que agrupa segmentos bancários mais robutos, e de Pessoa Física(PF). 
O desenvolvimento da análise e pré-processamento é construído de forma simples e clara, podendo ser facilmente compreendida por todos que possuírem algumas noções básicas da linguagem Python, sobretudo aqueles que já estejam familiarizados com a biblioteca Pandas. 

# Project Description
This repository presents a Minimum Viable Product (MVP) developed as an evaluation for the first sprint of the MBA in Data Science and Analytics at the Pontifical Catholic University of Rio de Janeiro (PUC-RIO). The project involves analyzing and preprocessing credit reports from the year 2022 that were made available by the Central Bank of Brazil to investigate the profile of delinquency in Brazil. The focus is mainly on credit assets classified by the Central Bank as "problematic". Assets are considered problematic when at least one of the following events occurs:
  I - credit operations that are overdue for more than 90 (ninety) days;
  II - the existence of indications that the obligation will not be fully honored without the need for guarantees or collaterals. 
For the Central Bank, these indications occur when the operation is subject to restructuring, and the financial institution recognizes significant deterioration in the credit quality of the borrower, classifying it between risk levels E and H.
Although we did not use machine learning techniques for this task, the database used was chosen because of its suitability for the future development of a predictive model of the risk of eventual default, which may be a probable future development of this project.
The main hypothesis we will test is that in 2022, there was a higher occurrence of credit assets considered problematic among individuals from economically poorer layers, mainly related to the housing credit modality. To do so, in addition to analyzing the 2022 period, we will focus on data from S1, which aggregates more robust banking segments, and from Individual Persons (PF).
The development of the analysis and preprocessing is presented in a simple and clear way, easily understandable by anyone who has some basic knowledge of the Python language, especially those who are already familiar with the Pandas library.

# Linguagens e tecnologias usadas
* Google Colaboratory
* Python 13.11

# Bibliotecas usadas
* Pandas
* Matplotlib
* Seaborn
* NumPy
* Opendatasets
* Os
* Missingno
* Gdown
* Zipfile
