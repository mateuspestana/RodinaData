RodinaData Codebook
================

O banco de dados utiliza as mesmas variáveis disponíveis pela
[CIKRF](http://cikrf.ru), constando no banco seus nomes traduzidos para
o português (english version soon) e de maneira abreviada, para melhor
processamento e leitura.

### Links

Os dados estão disponíveis nos sites, diretamente pelos seguintes links:
- **Duma 2003 - Proporcional** :
<http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100095621&vrn=100100095619&region=0&global=1&sub_region=0&prver=0&pronetvd=0&vibid=100100095621&type=233>
- **Duma 2007 - Proporcional** :
<http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100021960186&vrn=100100021960181&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=100100021960186&type=233>
- **Duma 2008 - Proporcional** :
<http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100028713304&vrn=100100028713299&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=100100028713304&type=233>
- Mais em breve

### Variáveis

  - **regiao**: Estado
  - **tik**: Comissão Territorial Eleitoral, costumeiramente o município
  - **uik**: Número da seção eleitoral
  - **nelelist**: Número de eleitores na lista, aptos a votar
  - **ncedreceb**: Número de cédulas recebidas pela comissão eleitoral
  - **ncedantes**: Número de cédulas emitidas a eleitores que votaram
    antes da data
  - **ncedestac**: Número de cédulas emitidas a eleitores nas seções
    eleitorais
  - **ncedforaestac**: Número de cédulas emitidas a eleitores fora das
    seções eleitorais
  - **ncancelced**: Número de cédulas canceladas
  - **ncedurnamovil**: Número de cédulas em urnas móveis
  - **ncedurnafix**: Número de cédulas em urnas estacionárias
  - **ncedinval**: Número de cédulas inválidas
  - **ncedval**: Número de cédulas válidas
  - **ncedausentdistcomiss**: Número de cédulas faltantes recebidas pela
    comissão
  - **ncedausentprecomiss**: Número de cédulas faltantes emitidas nas
    seções
  - **ncedausentcanc**: Número de cédulas faltantes canceladas
  - **ncedausenttik**: Número de cédulas faltantes emitidas a eleitores
    pela Comissão Eleitoral Territorial (TIK)
  - **ncedperd**: Número de cédulas perdidas
  - **ncednaoconsid**: Número de cédulas não contadas/consideradas
  - **contratodos**: Voto “Contra Todos”, modalidade existente até esta
    eleição
  - **circunscricao**: Circunscrição a qual pertence o caso
  - **KOIB\_KEG**: Variável que indica se a eleição foi feita de forma
    analógica (valor 0); pelo sistema **KOIB** (valor 1, onde as cédulas
    são escaneadas); ou pelo sistema **KEG** (valor 2, no qual há uma
    urna onde se registra o voto e o mesmo é impresso para confirmação)
  - **p\_*NOMEDOPARTIDO***: Nome do partido reduzido (i.e.,
    p\_edinayarossiya: Rússia Unida; p\_ldpr: Partido Liberal Democrata
    da Rússia etc)
