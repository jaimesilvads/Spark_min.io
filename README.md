### FRANCISCO JAIME DA SILVA


# Spark com Min.io

Projeto básico de Engenharia de dados com Spark e Data lake Min.io

<p align="center"><img src="./DIO.png" width="500"></p>

## Projeto básico de Engenharia de dados


__*Foi Criando um ecossistema Hadoop totalmente gerenciado com Google Cloud Platform*__

O desafio consistia em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento deveira efetuar a contagem das palavras de um livro e informar quantas vezes cada palavra aparecia no mesmo.

---

### Etapas do Projeto

1. Foi Criado um datalake  utilizand Min.io intalado localmente com estruta abaixo
<ul>
  <li>Bancket(ingestao) - Como zona de pouso ou landing zone(dados em formato bruto)</li>
  <li>Bancket(processamento_ - Como zona de processamento ou processing zone(dados pre-processados)</li>
  <li>Bancket(servico) - Como zona de serviços ou cureted zone(Dados limpos prontos para análises)</li>  
</ul> 
2. Foi realizado o uploade dos arquivos de dados na zona de pouso(ingestao), extraídos do kaggle
<ul>
  <li>T201605PDPI+BNFT.csv</li>
  <li>T201606PDPI+BNFT.csv</li>
  <li>T201607PDPI+BNFT.csv</li>  
  <li>T201608PDPI+BNFT.csv</li>    
</ul> 
3. Foi utilizado o script spark para realizar a limpeza, preprocessamento e conversão para o formato parquet, visando melhorar a performance nas proximas etapas do processo.
4. Foi realiza a agregação dos dados e disonibilização na zone de serviços para futuras análises por parte dos cientistas e nalista de dados.
