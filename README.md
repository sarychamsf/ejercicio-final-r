# Caso Práctico R

Se dispone del siguiente archivo CSV con información sobre los Air Bnb de la ciudad de Milán en 2019. En el dataset, solamente aparecen apartamentos completos.

El dataset original y la explicación de todas las columnas está disponible en el siguiente enlace: https://www.kaggle.com/antoniokaggle/milan-airbnb-open-data-only-entire-apartments 

## Procesos de analítica a realizar

1. Cargar el archivo “Airbnb_Milan.csv” como dataframe.
2. Crear un nuevo dataframe que contenga únicamente las siguientes columnas:
  * “host_is_superhost”
  * “host_identity_verified”
  * “bathrooms”
  * “bedrooms”
  * “daily_price”
  * “security_deposit”
  * “minimum_nights”
  * “number_of_reviews”
  * “review_scores_rating”
3. Cambiar los factores de la variable “host_is_superhost” de 0, 1 a: “SI” y, “NO”. (investigar la función recode).
4. Cambiar los factores de la variable “host_identity_verified” de 0, 1 a: “VERIFICA” y “NO VERIFICA”.
5. Mostrar un resumen estadístico de los datos.
6. Filtrar el dataset por apartamentos cuyo mínimo de noches sea igual o menor que siete.
7. ¿Cuál es el precio medio por día de una habitación en función de si el anfitrión tiene verificado o no su perfil?
8. Quién tiene más número de reseñas, ¿un super host o no super host?
9. Sobre la estadística anterior ¿quién tiene la puntuación media más alta?
10. Crea un vector categórico llamado “CATEGORÍA”, en función de que, si para la puntuación de las reseñas tiene de 0 a 49, sea “NO ACONSEJABLE”; de 50 a 75 sea “ESTÁNDAR”; y de 76 a 100 sea “TOP”.
11. Mostrar las frecuencias de la variable CATEGORÍA.
12. Obtener el histograma del precio por día.
13. Estudiar la relación entre los dormitorios y baños de forma gráfica.
14. Mostrar un histograma del número de reseñas en función de si es un usuario verificado o no.
15. Mostrar un histograma por cada valor de “CATEGORÍA” en el que se enseñe la cuantía del depósito de seguridad en función de si el anfitrión es super host o no.

## Se pide

1. OBLIGATORIO: realizar ambos casos prácticos en formato notebook (Python .ipynb, R .RMD).
2. OBLIGATORIO: la entrega se realizará desde un mismo archivo (incluir ambas soluciones en una carpeta comprimida. No se admitirán los ejercicios por separado).
3. OPCIONAL: de forma opcional, puede hacerse entrega de los notebooks como HTML.
