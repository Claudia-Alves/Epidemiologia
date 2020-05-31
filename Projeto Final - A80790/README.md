# *Projeto Final da aluna A80790 para a UC de Sistemas Informação Geográfica*

Visualização de casos de COVID-19 através de gráficos e mapas

Neste notebook estão alguns gráficos relativos aos casos de COVID-19 em alguns países


## Agrupamento dos dados por países

Obtiveram-se alguns gráficos com os casos por países, utilizou-se uma função para apenas contar os países com mais de 100 casos.
__*NOTA*: em alguns gráficos, como os valores são muito elevados, aparece a notação científica.__

![Gráfico Países](Figuras/Paises_pie.png | width=100)

Gráfico com os confirmados e os mortos, de acordo com os países com mais confirmados.

![Figura_Paises](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Paises_BarraH.png)

Gráficos com o total de confirmados vs mortos, para tal fez-se a soma de todos os confirmados e mortos por país até a data.

![Confirmados vs mortos pie](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Confirmados_mortos_pie.PNG)

![Confirmados vs mortos](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/TotalConfirmados.png)

### Casos por categoria

Tendo em conta alguns dados de tempo médio até ser dada a alta a casos graves e críticos, obteve-se um gráfico com o Tempo médio de hospitalização para cada um deles. 

![TempoHGraves vs criticos](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/TempoHospitalização.png)

Fez-se um gráfico relativo aos casos de COVID-19 por três categorias, leves, graves e críticos. 

![CasosLevesGravesCriticos](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/CasosLevesGravesCriticos.png)


## Mapas mundo

Utilizaram-se os dados atuais de mortos e recuperados nos diferentes países para construir os mapas com a Taxa de Mortalidade no Mundo e com a Taxa de Recuperação no mundo. 

#### Taxa de Mortalidade 

![TaxaMortalidade](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/TaxaMortalidadeMundo.png)

#### Taxa de Recuperação 

![TaxaRecuperados](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/TaxaRecuperadosMundo.png)


## Estatísticas de top 10

Para estas estatísticas de top 10 fizeram-se alterações ao dataset utilizado, incluindo selecionar algumas colunas, agregar os dados, fazer somas e guardar esses dados em novos ficheiros csv. Estes ficheiros podem ser encontrados na pasta Dados.

### Top 10 países 

#### Com mais casos confirmados
![CasosConfirmados](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10paisesCasos.png)

#### Com mais mortos
![Mortos](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10paisesMortes.png)

#### Com mais recuperados
![Recuperados](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10paisesRecuperados.png)

#### Com mais casos hospitalizados
![CasosHospitalizados](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10paisesHospitalizados.png)

#### Com mais casos nos cuidados intensivos
![CasosUCI](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10paisesNosUCI.png)

#### Com mais testes
![Testes](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10paisesTestes.png)

### Top 10 regiões na Austrália

#### Regiões com mais casos confirmados
![CasosConfirmadosA](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10RegioesAustraliaCasos.png)

#### Regiões com mais recuperados
![RecuperadosA](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10RegioesAustraliaRecuperados.png)

#### Regiões com mais mortos
![MortosA](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10RegioesAustraliaMortos.png)

#### Regiões com mais testes
![TestesA](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10RegioesAustraliaTestados.png)

#### Regiões com mais casos hospitalizados
![HospitalizadosA](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Top10RegioesAustraliaHospitalizados.png)


## Casos em Espanha

Total de confirmados e mortos em Espanha por data.

![Espanha](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Espanha_total.png)

### Casos numa região de Espanha

Gráfico com os confirmados e mortos para as Asturias, uma das sub-regiões de Espanha, até a data mais atual, de notar que os dados para as sub-regiões não são tão atuais como os dados no país todo, ou seja, enquanto que para Espanha no geral se obteve os dados até ao dis 29 de Maio, para a sub-região o mais recente é 21 de maio.

![Asturias](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/AsturiasConfirmados.png)


## Casos em Itália

### Total de casos Confirmados e mortos 

![Itália](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Italia_total.png)

### Heurística - modelagem exponencial

Fez-se uso de uma heurística já existente e a encontrada é do dia 17 de março, portanto,  os gráficos seguintes são baseados nessa data.

![ItáliaH](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/Italia_heuristica.png)

### Estimativa de 3 dias vs dados reais

![ItáliaEst](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/ItaliaEstimativa3dias.png)

### Estimar 3 dias futuros

![ItáliaFut](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/ItaliaFuturo3dias.png)


## Casos na Corea do Sul

![CoreaS](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/CoreaSulTotal.png)

### Heurística - modelagem exponencial

Fez-se uso de uma heurística já existente e a encontrada é do dia 18 de março, portanto,  os gráficos seguintes são baseados nessa data.

![CoreaSH](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/CoreaSHeuristicaGomperstz.png)


### Estimativa de 3 dias vs dados reais

![CoreaSEst](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/CoreaSEstimativa.png)

### Estimar 3 dias futuros

![CoreaSFut](https://github.com/Claudia-Alves/Epidemiologia/tree/master/Projeto%20Final%20-%20A80790/Figuras/CoreaSFuturo3Dias.png)



