# Desafio de Projeto: Pipeline de ETL com Python

O desafio consiste em desenvolver uma aplicação simples do processo de ETL, utilizando linguagem de programção Python e suas bibliotecas.

## Projeto

O objetivo deste projeto é desenvolver uma aplicação simples do processo de ETL.

Na etapa de **extração**, será carregado e lido um arquivo no formato *csv*, que contém dados com relação às vendas de uma empresa fictícia de comércio de vestuário. Após a extração, o conjunto de dados será transformado para a estrutura de dados de *dataframe do pandas*.

Na **transformação**, serão criadas novas colunas para armazenar o cálculo do total da venda, total do custo e total do lucro. Tais cálculos serão realizados por meio de funções da biblioteca *pandas*.

Na etapa de **carga**, será feito o download do arquivo final no formato csv, contendo os dados originais mais as novas colunas calculadas. Além disso, serão plotados gráficos para facilitar a **visualização e análise dos dados**, utilizando-se recursos da biblioteca *matplotlib*.

---

## Arquivos

Este repositório contém os seguintes arquivos:
* vendas_trim1.csv: Base de dados para a aplicação, deve ser carregada para o ambiente de execução.
* desafio_dio_etl_tamara.ipynb: Notebook com o código-fonte da aplicação ETL.
* vendas_transformadas.csv: Exemplo de saída após o processamento.
* relatorio.pdf: Arquivo contendo os gráficos gerados na transformação.
