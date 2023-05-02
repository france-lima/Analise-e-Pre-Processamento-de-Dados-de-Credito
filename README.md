# Analise-e-Pre-Processamento-de-Dados-de-Credito
# Sumário
* [Descrição do projeto](#descrição-do-projeto)
* [Project description]
* [Linguagens e tecnologias usadas]
* [Bibliotecas usadas]

# Descrição do projeto
Este repositório apresenta um MVP(Minimum Viable Product) elaborado como avaliação para a Sprint I do curso de pós-Graduação em Ciência de Dados e Analytics da Pontifícia Universidade Católica do Rio de Janeiro (PUC-RIO).
O projeto envolve a análise e pré-processamento dos relatórios de crédito do período de 2022 disponibilizados pelo Banco Central com a finalidade de investigar prováveis efeitos da pandemia sobre o perfil da indinplência no Brasil, considerando, principalmente, os ativos de crédito classificados pelo Banco Central como "problemáticos". 
Os ativos são considerados ativos problemáticos quando é constatado pelo menos um dos seguintes eventos:
  I - operações de crédito em atraso há mais de 90 (noventa) dias;
  II - a existência de indicativos de que a obrigação não será integralmente honrada sem que seja necessário recurso a garantias ou a colaterais (Para o BCB estes         indicativos ocorrem quando a operação é objeto de reestruturação e a instituição financeira reconhece contabilmente deterioração significativa da qualidade do crédito   do   tomador, classificando-o entre os níveis de risco E e H).
Embora não utlizemos técnicas de machine learning nessa tarefa, a base de dados utilizada foi escolhida devido à sua adequação para o futuro desenvolvimento de um modelo preditivo do risco de eventual inadimplência. Talvez, um provável desdobramento futuro deste projeto. 
A hipótese principal a qual iremos testar é de que em 2022 houve uma ocorrência maior de ativos de crédito considerados problemático entre indivíduos de camadas economicamente mais pobres relacionada, sobretudo, a modalidade de crédito de habitação. Sendo que, para tal, além de analisarmos o período de 2022, nos concetraremos nos dados do S1, que agrupa segmentos bancários mais robutos, e de Pessoa Física(PF). 
O desenvolvimento da análise e pré-processamento é construído de forma simples e clara, podendo ser facilmente compreendida por todos que possuírem algumas noções básicas da linguagem Python, sobretudo aqueles que já estejam familiarizados com a biblioteca Pandas. 

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
