### FRANCISCO JAIME DA SILVA


# Spark com Min.io

Projeto de Engenharia de dados com Spark e Data lake Min.io

<p align="center"><img src="./Engenharia.jpg" width="500"></p>

## Projeto de Engenharia de dados


__*Foi Criando um Data Lake como objetivo ser o repositório de dados*__

O projeto consistia em efetuar o upload dos dados para a zona de pouso realizar limpeza de preprocessamento dos dados, utilizar o spark para limpar e formatar os dados deixando -oos no formato mais apropriado para aplicação de análises. Realizar agregações nos dados e transportar para a zona de serviços, para serem explorados pelos cientistas e analista de dados.

---

### Etapas do Projeto

1. Foi Criado um datalake  utilizand Min.io intalado localmente com estruta abaixo
<ul>
  <li>Bancket(ingestao) - Como zona de pouso ou landing zone(dados em formato bruto)</li>
  <li>Bancket(processamento_ - Como zona de processamento ou processing zone(dados pre-processados)</li>
  <li>Bancket(servico) - Como zona de serviços ou cureted zone(Dados limpos prontos para análises)</li>  
</ul> 
2. Foi realizado o upload dos arquivos de dados na zona de pouso(ingestao), extraídos do kaggle
<ul>
  <li>T201605PDPI+BNFT.csv</li>
  <li>T201606PDPI+BNFT.csv</li>
  <li>T201607PDPI+BNFT.csv</li>  
  <li>T201608PDPI+BNFT.csv</li>    
</ul> 
3. Foi utilizado o script spark para realizar a limpeza, preprocessamento e conversão para o formato parquet, visando melhorar a performance nas proximas etapas do processo.
4. Foi realiza a agregação dos dados e disonibilização na zone de serviços para futuras análises por parte dos cientistas e nalista de dados.
