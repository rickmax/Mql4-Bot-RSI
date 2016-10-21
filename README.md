# Mql4-Bot-RSI


Simples Forex BoT - Expert Advisor, este bot é open source, com o intúito de aumentar a comunidade de desenvolvedores MQL4.

# Estratégia

Compra:
Se o indicador iRsi estiver abaixo de 30, envia uma ordem de compra.

 



    if (iRSI(NULL, PERIOD_M5,20,PRICE_CLOSE,0) < 30)





Venda:
Se o indicador iRsi estiver acima de 70, envia uma ordem de compra.





    if (iRSI(NULL, PERIOD_M5,20,PRICE_CLOSE,0) > 70)





 # Funções

  * TrailingStop 	> Catraca para salvar lucro.
  * OpenOrderLimit 	> Gerenciamento de ordens abertas.
  * MaxLots			> Gerenciamento de tamanho máximo do Lote.
  * OrderLotsMgm		> Gerencimante de ordens e lotes para lançamento de Martin Gale.

# Cuidado!

Os códigos acima são para estudo, a utilização no mercado é de inteira responsabilidade do usuário com risco de perda de capital. 

property copyright "Copyright © 2014, by Henrque Max"
property link      "http://www.henriquemax.com.br/"