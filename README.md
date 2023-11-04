# Consumo de energia de la ciudad de Tetuan 💡

## Introduccion 
Cada dia es mas importante desde el campo de la sostenibilidad y la produccion las maneras en como se mueve el mercado energetico en nuestro entorno, por lo que es necesario conocer sobre que variables que pueden influir en gran medida en el uso de energia en las grandes ciudades. Dentro de estas condiciones se ha considerado abordar desde el area de data los elementos que afectan en el consumo de este recurso y en que medida se puede predecir para suplir esta demanda constante. Esta evaluacion se realizo con un dataset del 2017 en el que se encuentran las variables climaticas de temperatura, Humedad, Velocidad del viento y los flujos difusos en 3 diferentes zonas de la ciudad. Finalmente con esta informacion se busca poder utilizar modelos que finalmente puedan ser replicables en los ambitos de otras grandes ciudades como en el caso de Medellin y su gran potencial con la captura de informacion que realiza el SIATA.

Tetuán, situada en el norte de Marruecos, experimenta un clima mediterráneo con veranos cálidos e inviernos suaves y húmedos. La ciudad está influenciada por su proximidad al mar Mediterráneo, lo que modera las temperaturas a lo largo del año, Las temperaturas estivales suelen rondar los 30°C, mientras que en invierno se mantienen en un rango más moderado, alrededor de los 10-15°C. La proximidad al mar Mediterráneo tiene un impacto significativo en el clima de Tetuán, contribuyendo a una moderación térmica y a la presencia de una humedad relativa más alta. En cuanto a la población, Tetuán es una ciudad de tamaño medio, con una comunidad diversa que refleja la rica historia cultural de la región.

En términos de consumo energético, Tetuán, como muchas ciudades en Marruecos, enfrenta desafíos relacionados con la sostenibilidad y la eficiencia energética. El crecimiento urbano y la modernización pueden aumentar la demanda de energía, pero Marruecos ha estado trabajando en iniciativas para promover fuentes de energía renovable y mejorar la eficiencia energética en sus ciudades. Tetuán, al ser parte de este esfuerzo nacional, ha buscado reducir su huella de carbono y avanzar hacia un futuro más sostenible, aprovechando posiblemente la abundancia de recursos renovables, como la energía solar.

El clima mediterráneo con veranos cálidos e inviernos suaves comparado al clima Ecuaorial de Medellín, que experimenta un clima templado a cálido. Ambas ciudades comparten un interés en la sostenibilidad, evidenciado por iniciativas para reducir la huella de carbono y promover prácticas más sostenibles en la planificación urbana y el consumo energético. Ambos lugares reconocen la importancia de abordar los desafíos ambientales para crear entornos más habitables y ecoamigables. Este caso de estudio nos permite apoyarnos en profundizar en la condición local de Medellin y sus retos en cuanto a su consumo energetico. Este conjunto de datos está relacionado con el consumo de energía de tres redes de distribución diferentes de la ciudad de Tetuán, ubicada en el norte de Marruecos.

## Objetivos
Analizar el consumo de energía en tres redes de distribución distintas en la ciudad de Tetuán, Marruecos, que se encuentra en el norte del país y apartir de los datos recopilados realizar un analisis exploratorio que nos permita identificar en lineas de tiempo el consumo de energia dentro de la ciudad y como este se puede extrapolar en otras ciudades.

- Crear un modelo predictivo para establecer y realcionas los momentos de mayor consumo de energia.

- Crear un portafolio que nos permita determinar la prediccion de demanda y consumos con relacion a la importancia de estas predicciones dentro de un modelo de negocio.

- Justificar de que manera este analisis puede impactar positivamente y su viabilidad como un modelo replicable en otras ciudades.

- Implementar de la mejor manera posible las tecnologias y conociemitos dentro del modelo del proyecto.

## Instalacion
Para instalar este proyecto, te recomendamos seguir estos pasos:
* `pip install virtualenv`
* `python -m pip intall --upgrade pip`
* `python -m venv .venv`
* `source .venv/Scripts/activate`
* `pip install -r requirements.txt`
* `pip freeze > requirements.txt`