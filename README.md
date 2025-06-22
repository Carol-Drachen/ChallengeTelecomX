# :gem: Challenge TelecomX 💎

## Objetivo del análisis :office: :bangbang:
La empresa TelecomX desea conocer cómo se está comportando la evasión o el abandono de los clientes (churn) a través de un análisis exploratorio de sus datos.
Los datos que se comparten para realizar el proceso de ETL contienen información como el ID de clientes, el total de pago mensual, el género, el tiempo y tipo de suscripción y de acuerdo con la edad, si son menores o mayores a 65 años, entre otros.

## Limpieza y Tratamiento de los datos :white_check_mark:
La carga de los datos se realizó mediante una API para obtener un JSON.
Se realizó la normalización de los datos y se determinó los valores nulos o vacios del dataframe.
Posteriormente se realizó la limpieza filtrando solo por aquellos datos que contenían valores en "Churn", ya que es la columna clave para el objetivo del negocio. 

## Análisis Exploratorio de Datos :large_orange_diamond:
Se realizó el análisis descriptivo de los datos. También se creó una columna de "Cuentas diarias" con la finalidad de tener la cantidad que cada cliente paga día con día.
Para realizar un mejor análsisi se generaron varias gráficas con respecto al abandono de los clientes, contrastando por género, edad, tipo de contrato y  tiempo de contrato. 
También se incluye la gráfica de abandono por método de pago.

## Conclusiones e Insights ⚡⚡
Los principales hallazgos son que del total de datos que contienen información sobre el abandono de los clientes, el 26.6% sí abandona a la empresa TelecomX. 
Por otro lado, el método de pago de “electronic check” es mediante el cuál los clientes abandonan más a la empresa, manteniéndose más fieles con el pago automático de la tarjeta de crédito. De igual forma, los clientes con el tipo de contrato de mes a mes abandonan más que aquellos que tienen un contrato de 2 años (42.7% vs 2.8%).
Por último, se obtuvo un histograma para los clientes que abandonan con respecto al tiempos de contrato, en donde de entre 0 a 4 meses hay mayor frecuencia de abandono.

Algunas de las gráficas que se pueden observar dentro del análisis es la siguiente:
![image](https://github.com/user-attachments/assets/39c765be-a630-483e-9ef7-26ac68eee566)


## Recomendaciones 📖💢
Se recomienda que la empresa TelecomX opte por ofrecer métodos de pago más apegado a la tarjeta de crédito o a las transferencias bancarias, es decir, métodos electrónicos para disminuir el abandono de los clientes
También se sugiere el cambio de tipo de contrato de mes a mes por uno o dos años. Así mismo, ofrecer alternativas para que los clientes tengan tiempos os de contrato más cortos y se evite el abandono.
Por último, se sugiere generar estrategias de retención para clientes menores de 65 años.
