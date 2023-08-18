# Desafio_RenovaBR
Repositório com desafio de tratamento de dados feito pela empresa RenovaBR 

Houveram dificuldades devido ao tamanho do arquivo, não consegui de imediato a importação via excel no power bi consegui excluir linhas em branco por la porém não foi a soluçao que eu procurava reiniciei o processo
comecei o processo com python pelo Jupyter notebook

importando as bibliotecas para visualizaçao de dados e manutenção
PANDAS, SEABORN E MATPLOTLIB

primeiro tratamento realizado com pandas foi que segundo instruções apenas os dados de SP são relevantes logo foram retirados da base perfil_eleitorado_2020 todos os dados que seriam referentes a outros estados
reduzindo o numero de linhas de 4248507 para 639502

eleitorado_2020 foram retiradas as colunas
ano eleicao
hh geracao
dt geracao
cd mun sit biometria
ds mun sit biometria

colunas com redundancias e informações repetidas não necessárias 

após análise não há registros brancos nem nulos no bd eleitorado 2020
