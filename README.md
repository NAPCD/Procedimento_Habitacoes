## IDENTIFICAÇÃO DO PROBLEMA
<p>
  O município do Recife é a nona capital mais populosa do país e a terceira do Nordeste, com população estimada em 1.661.017 habitantes em 2021 (IBGE).  No entanto, a capital pernambucana é uma das menores em extensão territorial do país, com apenas 218,4 km². Seu território, considerado totalmente urbano, é dividido em 6 Regiões Político Administrativas (RPAs) sendo formado por 94 bairros. <br>
  Sobre o Recife, destaca-se ainda que, de acordo com a Pesquisa de Núcleos Urbanos Informais no Brasil (NUIs) - desenvolvida pelo IPEA e requisitada pelo Ministério de Desenvolvimento Regional -, a cidade apresenta 48% de seus domicílios em assentamentos informais. A maioria desses NUIs caracterizados pela pesquisa são favelas ou ocupações espontâneas. Já de acordo com o IBGE, 19,52% dos domicílios ocupados estão em aglomerados subnormais em relação ao total de domicílios ocupados, o que representa um número absoluto de 103.701 domicílios em aglomerados subnormais em Recife.<br>
  Aponta-se, ainda, que, segundo o Plano Local de Habitação de Interesse Social (PLHIS) -  atualizado em 2017 pela Prefeitura do Recife em parceria com a Câmara Técnica de Habitação e Regularização Fundiária do Conselho da Cidade do Recife -, no que se refere à inadequação domiciliar, têm-se a carência de infraestrutura como principal fator, tendo sido identificados 127.868 domicílios sob essa condição .<br>
  KRAUSE et al. (2022) em um estudo recomendado pelo Ministério de Desenvolvimento Regional (MDR), na construção de modelos, indicaram que a presença de núcleos urbanos informais está completamente relacionada ao total de pessoas em famílias cadastradas no Cadúnico e à presença de domicílios com alvenaria sem revestimento. <br>
  Nesse sentido, para realização da presente avaliação diagnóstica, foram estimados possíveis recortes para a alocação de recursos destinados ao Programa Casa Melhor a partir das variáveis oferecidas pelo banco do CadÚnico da Prefeitura do Recife, em específico aquelas que se referem à infraestrutura dos domicílios das famílias cadastradas, como a existência de banheiro e a qualidade dos materiais utilizados para a construção e revestimento de superfícies dessas residências.<br>


### Cruzamento de tipos de obras de melhoria habitacional propostas pelo Ministério de Desenvolvimento Regional com variáveis do Cadúnico de Recife 

|Nível de associação entre as variáveis|Obra de melhoria especificada pelo MDR|Variável do CadÚnico utilizada para estimar necessidade de obra de melhoria|Nome da Variável no banco CadÚnico |Explicação|
|---|---|---|---|---|
|DIRETA |Novo banheiro contíguo adaptável|Existência de banheiro|d.cod_banheiro_domic_fam|Informa se existe ou não  banheiro na moradia|
|DIRETA |Revestimento e pintura externa casa|Material predominante nas paredes externas do domicílio|d.cod_material_domic_fam|Informa o material predominante nas paredes externas: Alvenaria/tijolo com revestimento;  Alvenaria/tijolo sem revestimento; Madeira aparelhada; Taipa revestida; Taipa não revestida; Madeira aproveitada; Palha; Outro Material.|
|DIRETA |Contrapiso e revestimento cerâmico piso cômodo|Material predominante no piso do domicílio|d.cod_material_piso_fam|Informa o material predominante no piso: Terra, Cimento, Madeira,  Cerâmica, Lajota.|
|INDIRETA |Reforma de banheiro |Existência de banheiro|d.cod_banheiro_domic_fam|Informa se existe ou não banheiro na moradia.|
|INDIRETA |Revestimento e pintura interna de cômodos|Material predominante nas paredes externas do domicílio|d.cod_material_domic_fam|Informa o material predominante nas paredes externas: Alvenaria/tijolo com revestimento;  Alvenaria/tijolo sem revestimento; Madeira aparelhada; Taipa revestida; Taipa não revestida; Madeira aproveitada; Palha; Outro Material.|
|INDIRETA |Retirada/Colocação de porta e janelas|Considerando a existência da porta de entrada|d.cod_material_domic_fam e d.qtd_comodos_domic_fam|Material predominante nas paredes externas do domicílio e número de cômodos servindo como dormitório.|

<p>
  Além dos critérios utilizados para seleção das famílias cujos domicílios poderiam ser alvo das melhorias habitacionais, foram levados em consideração critérios para priorização dos públicos a partir de características dos membros que compõem as mencionadas famílias. Tais critérios foram escolhidos de modo a priorizar os públicos mais vulneráveis dentro do grupo de famílias em situação de renda abaixo da linha de pobreza, a saber as pessoas com deficiência e as famílias com membros na faixa etária da primeira infância.<br>
  Dessa maneira, foram mapeadas variáveis do CADÚNICO que poderiam fornecer informações precisas que viabilizassem o cálculo de quantas pessoas/famílias compõem os grupos prioritários acima definidos.<br>
</p>
  
|Característica do grupo prioritário|Nome da Variável no banco  CadÚnico |Explicação|
|---|---|---|
|Bairro|uf|Localização da família inscrita no Cadúnico.|
|Código da família no Cadúnico|d.cod_familiar_fam|Código de identificação da família.|
|Valor da renda per capita da família|d.vlr_renda_media_fam|Define o valor da renda familiar per capita.|
|Presença de pessoa com deficiência|p.cod_deficiencia_memb|Indica a presença de pessoas com deficiência na família.|
|Primeira Infância |p.fx_idade|Indica a quantidade de famílias que possuem crianças na fase da primeira infância. |

##

<div align="center">
  <img align="center" alt="logo_napcd" height="150" style="border-radius:50px;" src="/img/NAPCD LOGO VERSOES-00.png">
  </div>
