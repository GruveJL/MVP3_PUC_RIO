<h1 align="center"> MVP3_PUCRIO_REGRESSAO_CLUSTERIZACAO </h1> 
<h2 align="center">Repo MVP 3 - Data Science and Analytics - PUC RIO MBA</h2> 


## Resumo do Projeto
Esse projeto tem como função cumprir etapa obrigatória do _Sprint_ de Machine Learning & Analytics do Curso de MBA em Data Science e Analytics oferecido pela Puc Rio no ano de 2025.

## Objetivo
Construir todo o fluxo para resolução de um problema de aprendizado de máquina, envolvendo pré-processamento, análise exploratória, e criação e aplicação de um modelo de Machine Learning em um banco de dados.

### Objetivo do projeto:
A ideia do projeto é fazer um MVP para praticar a aplicação de um modelo de Machine Learning em um Banco de Dados. O foco aqui será a exploração e compreensão dos dados, além de testar alguns tipos de modelos, avaliando seus resultados e entendendo qual deles teve mais "fit" ao conjunto dos dados disponíveis.

Os Arquivos e pastas estão hospedados no Google Drive nos links abaixo:
* [Arquivo](https://colab.research.google.com/drive/1c4lABjnrupla1RFAvOfg6f-5tRqFp-dt?usp=drive_link) 
* [Dataset Original](https://drive.google.com/file/d/14wEv9mRXmUyT0z_TNFRF_O95gcS0Li8c/view?usp=drive_link)
* [Pasta do Projeto no Drive](https://drive.google.com/drive/folders/1bQO6TRw0ohoOZPXk2MxwIzeh3zHjIxDA?usp=drive_link)

E como referência neste repo do Github

### Base de dados: 
A Base de dados foi retirada do [Kaggle](https://www.kaggle.com/) e pode ser encontrada nesse [link](https://www.kaggle.com/datasets/mosapabdelghany/medical-insurance-cost-dataset).

Trata - se de uma base de dados de despesas médicas com seguro de plano de saúde nos Estados Unidos da América.

A Base possui 1338 entradas com 7 colunas de características incluindo a coluna alvo "charges" (custos).

## Proposta Inicial
Entender a base de dados avaliar duas hipóteses principais:
* Possibilidade de aplicar um modelo de regressão preciso para a base, que contém poucas variáveis.
* Treinar e Testar modelos a fim de entender quais deles é o melhor e qual a relação das variáveis com a coluna "charges"(custo) do dataset. 

## Metodologia
Uso de técnicas de tratamento de dados, gráficos, estatística descritiva, treinamento e aplicação de modelos de Machine Learning para inferir as hipóteses na base de dados.

## Análise, Conclusão e Próximos Passos
Como observado ao longo do projeto, entendemos que a quantidade de informação é pouca para prever com relativa precisão os custos médicos. 

Olhando a correlação dos dados fica um tanto claro que faltam variáveis que caracterize melhor o problema encontrado.

Como próximos passos poderíamos entender se a acertividade é de extrema importância para o problema, pois caso o valor final de acerto do modelo não seja necessário, poderiamos transformar em um modelo de classificação configurando alguns *ranges* de custo o que provavelmente daria mais performance e provavelmente resultados bem mais precisos.


# Autores
| [<img src="https://avatars.githubusercontent.com/u/131409712?v=4"  width=115><br><sub>Juan Lima</sub>](https://github.com/GruveJL)
