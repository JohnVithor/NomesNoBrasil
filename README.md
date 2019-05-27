# NomesNoBrasil

A maior parte do tempo foi gasta criando funções para interagir com a API do IBGE, tanto que a maior parte do notebook é apenas para definições dessas funções.

Por essas funções coletamos por exemplo, dados da população dos estados e dos municípios do Brasil ou informações das malhas geográficas desses lugares, além é claro das consultas sobre a frequência de determinado nome, a evolução ao longo dos anos desse nome ou o ranking de nomes deste local.

Boa parte do notebook é destinada ao tratamento dos dados obtidos, relacionamos eles a posições nas malhas obtidas e com isso geramos os mapas ou apenas combinamos os dados e criamos alguns gráficos para visualizar o ranking ou as variações da população com certo nome.

Por fim, temos uma célula no notebook que permite a edição dos dados utilizados na pesquisa. Podemos definir:
* O tipo da pesquisa:
  * Frequência de um nome em cada estado brasileiro
  * Frequência de um nome em todos os municípios de um estado
  * Ranking dos nomes em certo local
  * Frequência de um nome ao longo dos anos em certo local
* Nome a ser pesquisado
* Sexo a ser considerado na pesquisa
* Estado onde a pesquisa será feita
  * Município do estado indicado (com esse nível de detalhamento temos apenas o ranking e a frequência ao longo dos anos)

O fluxo para executar o código é bem simples. Rode todas as celulas e até a ultima e a edite com os parametros que quer. Em seguida teremos o mapa ou gráficos obtidos.
