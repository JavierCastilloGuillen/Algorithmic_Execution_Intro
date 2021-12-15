# [ES] & [EN] 
Content available in Spanish and English.
## [ES] Introducción a la ejecución algorítmica de mercado (Clase)

Con este script podremos acceder a datos de mercado, procesarlos y determinar
señales técnicas de acuerdo con nuestra estrategia operativa.

Para el ejemplo, usaremos indicadores técnicos (MACD y RSI) y el mercado de cryptodivisas.
La clase se realizó en fin de semana y este mercado permanece abierto :)

- Video: https://www.youtube.com/watch?v=5mxb8_8LqB0

¿Qué aprenderemos?

1. Conexión a un mercado RealTime (Datos - Órdenes).
2. Datos: Recopilación, procesado (uso de pandas) y análisis.
3. Funciones para determinar indicadores técnicos, lectura de mercado y señales.
4. Ejecutar órdenes cuando aparezcan nuestras condiciones.

¿Qué NO cubriremos en esta lección?

1. Análisis general del mercado (para activar-desactivar el algoritmo)
2. Monitoreo de métricas de riesgo (para activar-desactivar el algoritmo)
3. Implementación en servidores (Linode - Digital Ocean, etc.)
4. Websockets.

Para ello usaremos:

1. ccxt -> que permite conectar fácilmente los intercambios de criptomonedas más comunes
para recuperar los datos brutos y ejecutar las órdenes (compra / venta). https://ccxt.readthedocs.io/en/latest/manual.html
2. pandas -> La biblioteca común para procesar la recepción de datos sin procesar y trabajar con ellos. https://pandas.pydata.org/docs/
3. ta -> Para implementar indicadores técnicos (veremos la opción de calcularlos manualmente o usar una biblioteca) https://technical-analysis-library-in-python.readthedocs.io/en/latest/index.html
4. schedule -> para ejecutar el script cada (x) segundos / minutos / horas ... para recuperación y proceso de datos. https://schedule.readthedocs.io/en/stable/


### DESCARGO DE RESPONSABILIDAD

No utilice las lógicas de señales del video para ejecutar órdenes reales. ES PARA FINES EDUCATIVOS.

La información general contenida en este repositorio / video no se puede considerar como un consejo o recomendación financiera. Además, la información publicada no debe ser considerada como un elemento de decisión para comprar o vender ningún tipo de activo. Invertir en mercados financieros como CFD, forex, acciones, derivados, etc., es una actividad que conlleva el riesgo de perder su dinero. No invierta en mercados financieros si no comprende la gestión y las consecuencias de esta actividad. Finalmente, recuerde que los resultados basados en el pasado no son indicativos de resultados futuros.


## [EN] Introduction to Market Algorithmic Execution (Lesson)

With this script we will be able to retreive data from the exchange, process it, and determine 
technical signals according to our trading strategy. 

For the example, we will use technical indicators (MACD & RSI) and cryptocurrency assets due lesson example is done 
on weekend for training purposes and the market is open :)

- Video: https://www.youtube.com/watch?v=-xNzIiCqxQA

What will we learn?

1. Connect to an exchange RealTime (Data - Orders).
2. Data: Gathering, cleasing (Using pandas) and analysis. 
3. Functions to determine technical indicators, market reading and signals
4. Execute orders when our conditions appears.

What we WON'T cover on this lesson?

1. Overall market analysis (to activate-deactivate algorithm)
2. Risk Metrics Monitoring (to activate-deactivate algorithm)
3. Deployment on servers (Linode - Digital Ocean, etc)
4. Websocket processing (data comes structured already)

To do so, we will use:

1. ccxt -> Which allows to easily connect the most common cryptocurrency exchanges
in order to retreive the raw data, and execute the orders (buy/sell). https://ccxt.readthedocs.io/en/latest/manual.html
2. pandas -> The common library to process the raw data reception and work with it. https://pandas.pydata.org/docs/
3. ta -> To implement technical indicators (we will see the option to calculate them manually or use a library) https://technical-analysis-library-in-python.readthedocs.io/en/latest/index.html
4. schedule -> to run the script every (x) seconds/minutes/hours... for data retreival and process https://schedule.readthedocs.io/en/stable/


### DISCLAIMER

Don't use the logic setup on the video to execute real orders. IS FOR EDUCATIONAL PURPOSE. 

The general information contained in this repository/video can't be considered as financial advice or recommendation. In addition, the information published should not be considered as a decision element to buy or sell any type of asset. Investing in financial markets such as CFDs, forex, stocks, derivatives, etc., is an activity that carries risk of losing your money. Do not invest in financial markets if you do not understand the management and consequences of this activity. Finally, remember that results based on the past are not indicative of future results.
