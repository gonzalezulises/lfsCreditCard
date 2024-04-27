# Credit Card Fraud Prediction

## Elaborado por Ulises González

### Descripción del Proyecto
Este proyecto tiene como objetivo analizar y predecir transacciones fraudulentas utilizando un conjunto de datos exhaustivo de transacciones con tarjeta de crédito. El dataset consta de 555,719 instancias y 22 atributos variados, incluyendo tipos de datos tanto categóricos como numéricos. Con una limpieza de datos completa y una ausencia de valores nulos, este conjunto de datos es ideal para aplicar técnicas de aprendizaje automático y visualización de datos para identificar patrones de fraude.

### Atributos del Dataset
El conjunto de datos contiene la siguiente información:
- **Trans_date_trans_time**: Marca de tiempo de la transacción (fecha y hora).
- **Cc_num**: Número único de identificación del cliente.
- **Merchant**: El comerciante involucrado en la transacción.
- **Category**: Tipo de transacción (por ejemplo, personal, cuidado de niños).
- **Amt**: Monto de la transacción.
- **First**: Nombre del titular de la tarjeta.
- **Last**: Apellido del titular de la tarjeta.
- **Gender**: Género del titular de la tarjeta.
- **Street**: Dirección postal del titular de la tarjeta.
- **City**: Ciudad de residencia del titular de la tarjeta.
- **State**: Estado de residencia del titular de la tarjeta.
- **Zip**: Código postal del titular de la tarjeta.
- **Lat**: Latitud de la ubicación del titular de la tarjeta.
- **Long**: Longitud de la ubicación del titular de la tarjeta.
- **City_pop**: Población de la ciudad del titular de la tarjeta.
- **Job**: Puesto de trabajo del titular de la tarjeta.
- **Dob**: Fecha de nacimiento del titular de la tarjeta.
- **Trans_num**: Identificador único de transacción.
- **Unix_time**: Marca de tiempo de la transacción (formato Unix).
- **Merch_lat**: Ubicación del comerciante (latitud).
- **Merch_long**: Ubicación del comerciante (longitud).
- **Is_fraud**: Indicador de transacción fraudulenta (1 = fraude, 0 = no fraudulento).

### Fuente de Datos
Los datos han sido tomados del reto "Credit Card Fraud Prediction" en Kaggle. Puedes encontrar el conjunto de datos completo aquí: [Kaggle Dataset](https://www.kaggle.com/datasets/kelvinkelue/credit-card-fraud-prediction).

### Actividad: Primera Entrega Trabajo Final
Para la primera entrega de este trabajo final, se debe preparar un notebook Jupyter que contenga:

1. **Abstract**: 
El fraude con tarjetas de crédito se ha convertido en una preocupación creciente, con tácticas cada vez más sofisticadas empleadas por los defraudadores.
La detección temprana y precisa de tales actividades es fundamental para la protección financiera de los consumidores y la sostenibilidad de las instituciones crediticias.
Este proyecto tiene como objetivo aplicar métodos de análisis de datos y técnicas de machine learning para predecir transacciones fraudulentas utilizando un conjunto de
datos detallado de transacciones con tarjetas de crédito. El dataset analizado contiene 555,719 transacciones, proporcionando un campo de pruebas amplio y variado para
el análisis de datos. Compuesto por 22 atributos, el conjunto ofrece una mezcla de variables categóricas y numéricas que describen detalladamente cada transacción.
Los atributos van desde información básica de transacción, como fecha y monto, hasta datos demográficos y geográficos del titular de la tarjeta.
Además, se incluye una marca binaria que indica si la transacción fue fraudulenta, lo que ofrece una variable objetivo clara para la construcción de modelos predictivos.
Un aspecto destacable del dataset es su integridad, estando libre de valores nulos, lo que facilita un análisis robusto sin la necesidad de extensas etapas de limpieza de datos.
Esta característica permite concentrarse en la exploración y modelización de datos para identificar posibles indicadores de fraude.


2. **Preguntas e Hipótesis**:
Preguntas de análisis:
¿Cuáles son las características comunes de las transacciones fraudulentas? (E.g., monto de la transacción, ubicación del comerciante, categoría de la transacción). (Para esta primera entrega voy a trabajar esta)
¿Existen diferencias significativas en el comportamiento de compra entre géneros?
¿Cómo varían las transacciones fraudulentas a lo largo del tiempo? (E.g., patrones diarios, mensuales o estacionales).
¿Hay correlación entre la ubicación del comerciante y la frecuencia de transacciones fraudulentas?
¿Cómo afecta la población de la ciudad al volumen y tipo de transacciones?

Hipótesis para probar ***A desarrollar para el proyecto final:
Las transacciones de montos más altos tienen una mayor probabilidad de ser fraudulentas.
Las transacciones en ciertas categorías (como cuidado personal) son más susceptibles al fraude que otras.
Los clientes de ciudades con poblaciones menores experimentan una tasa más alta de transacciones fraudulentas debido a menores medidas de seguridad.
Las transacciones realizadas durante ciertos períodos del día son más propensas a ser fraudulentas.
Los datos demográficos, como la edad y el género del titular de la tarjeta, influyen en la probabilidad de fraude.

