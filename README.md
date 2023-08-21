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

#Foi feito tratamento do arquivo menor, o arquivo maior teve erro ao realizar a manutenção do arquivo SP_turno_1

o arquivo perfil_eleitorado_2020 foi tratado, pelo software JUPYTER NOTEBOOK, o arquivo que vou deixar de tratamento no repositorio mostra as linhas de códigos que utilizei.

A proposta do desafio será focada nas bases de dados PERFIL DO ELEITORADO e
RESULTADOS, ambas são referentes às eleições 2020, 

porém nosso interesse é a
análise do estado de São Paulo e seus municípios.


O desafio poderá ser realizado com a tecnologia/ferramenta da sua preferência,
sendo SQL, Python ou Excel. Portanto iremos avaliar as seguintes aptidões
técnicas:

● Tratamento dos dados: gostaríamos de saber quais registros brancos ou
nulos podem ser removidos da base; 
quais colunas ou registros não serão necessários para a 
análise, se for o caso, informar quais não foram necessários; 

eleitorado_2020 foram retiradas as colunas
ano eleicao
hh geracao
dt geracao
cd mun sit biometria
ds mun sit biometria

após análise não há registros brancos nem nulos no bd eleitorado 2020

#SP_TURNO_1
UTILIZADO POWER BI
REMOVIDA COLUNA DS_AGREGADAS(TODAS NULAS)
MANTIDO PARTIDO NM_PARTIDO (PODEM HAVER NÃO VINCULADOS A PARTIDO)

REMOVIDO TODAS AS COLUNAS COM INFORMAÇÕES REDUNDANTES

colunas com redundancias e informações repetidas não necessárias 

so será necessário tratar algum registro que estava
gramaticalmente incorreto e/ou com caracteres especiais, etc.
O importante é tratar o máximo de inconsistências possíveis.


#Infelizmente não consegui realizar todas as análises a tempo, acho que me falta conhecimento dentro da área de análises

#deixarei também o arquivo alterado em power bi foram tiradas colunas redundantes e sem informação necessária, porém nao foi possivel prosseguir adiante


