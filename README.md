![image]https://upload.wikimedia.org/wikipedia/commons/4/46/Bitcoin.svg # bitcoin_trading
Algoritmo de decisión de de compra/venta de bitcoin, con indicadores: tendencia, ma50, ma200, rsi, macd, masd-signal.
Determina si es conveniente la compra/venta de Bitcoin Usando yahoo finance se obtienen los registros de los últimos 7 días con un intervalo de 5 minutos. Se crea un dataframe el cuál es tratado para obtener los valores estadísticos del bitcoin, especialmente la media y Q1 y Q3. Delimitando el rango de valores que se encuentrantran entre Q1 y Q3, se obtiene la media. Luego se obtienen los datos (precio de cierre y tendencia) en tiempo real con web scraping desde https://coinmarketcap.com/. Mediante un algoritmo se determina si es conveniente: comprar/vender/esperar. El resultado se visualiza así:

![image](https://github.com/JulioLaz/bitcoin_trading/assets/108642139/240b4ba7-e1e3-4f6b-9984-8e91e7497acf)

![image](https://github.com/JulioLaz/bitcoin_trading/assets/108642139/7d003877-5eb8-4547-b48f-f8f5e9532e52)

![image](https://github.com/JulioLaz/bitcoin_trading/assets/108642139/8cb169be-6e4c-4b02-820e-e1619a8f9e9c)
