<div align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo-full.svg" alt="Logo Bootcamp" width="80">
<h1>Santander Bootcamp 2023 <br> Ciência de Dados com Python</h1>
<img src="https://hermes.dio.me/tracks/03253ff0-95b9-4904-84e7-2063e9d6cb26.png" alt="Logo Bootcamp" width="220">
</div>

##  :brain: Desafio Original DIO: Explorando IA Generativa em um Pipeline de ETL com Python
Notebook do desafio original resolvido pelo Venilton da DIO:
<a target="_blank" href="https://colab.research.google.com/drive/1SF_Q3AybFPozCcoFBptDSFbMk-6IVGF-?usp=sharing#scrollTo=k5fA5OrXt1a3">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## :rocket: Entendendo o Desafio
Inspirado pelo projeto modelo o aluno deveria replicar ou reimaginar uma pipeline ETL utilizando Python.

## :bar_chart: Meu Projeto 
Supondo que sou a Cientista de Dados de uma empresa de prestações de serviços, criei um pipeline ETL para extrair os dados de dois arquivos CSV e um excel, à saber:
- CadastroFuncionarios;
- CadastroClientes;
- BaseServiçosPrestados.

Em seguida, fiz as transformações  para fazer cálculos como:
- Valor Total da Folha Salarial;
- Faturamento da Empresa;
- Percentual de Funcionários que Já Fechou Contrato;
- Total de Contratos que Cada Área da Empresa já Fechou;
- Total de Funcionários por Área;
- Faturamento Médio Mensal.

## :technologist: Etapas do Pipeline de ETL
### :white_check_mark: Extract
Nesta etapa vamos extrair os dados de vendas do arquivo `dados-venda.csv`. 
Este arquivo traz informações referentes ao ano de 2019 considerando o período de janeiro a agosto. As colunas contidas no arquivo são as seguintes: `Produto`, `Data`, `Quantidade` e `Valor`.

### :white_check_mark: Transform
Agora vamos calcular o total de vendas por produto e por mês.

### :white_check_mark: Load
 Salvando os dados transformados em um novo arquivo CSV e gerando gráfico de barras e de linha usando a biblioteca `Matplotlib`

## :battery: Stack utilizada
![VSCODE](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?style=for-the-badge&logo=Visual-Studio-Code&logoColor=white)
![PYTHON](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![GIT](https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=Git&logoColor=white)
![GOOGLE COLAB](https://img.shields.io/badge/Google%20Colab-F9AB00.svg?style=for-the-badge&logo=Google-Colab&logoColor=white)

## :notebook_with_decorative_cover:	 Notebook do meu projeto no Google Colab
<a target="_blank" href="https://colab.research.google.com/github/walterowisk/DIO_LabProject-Pipeline-ETL-Python/blob/main/DIO_LabProject_Pipeline_ETL_Analisando_Dados_de_Venda.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
