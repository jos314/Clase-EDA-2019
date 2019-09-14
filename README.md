# Repositorio Estructura de Datos Avanzadas

La carpeta de tareas contiene la descripción de cada tarea conforme se vaya asignando. Asegúrense de actualizar su copia del repositorio después de cada aviso de tarea.

La carpeta de datos tiene los datos necesarios para realizar las tareas que así lo requieran.

## Preguntas

Cualquier pregunta por favor a mi correo
fernando.esponda@itam.mx
no al de comunidad.

## GIT
Las tareas se asignarán y entreagarán a través de Github. Ver el documento de Ejercicios.

Para lo que vamos a hacer sólo se necesitan los comandos básicos para copiar repositorios y subir información. No es necesario hacer branches, merges, etc....
Para un primer tutorial vean <https://www.youtube.com/watch?v=SWYqp7iY_Tc>
Pero hay muchos.
Una vez que tengan su cuenta de GIT y GitHub registrense a la clase con esta liga (ahi debe aparecer su clave única)
https://classroom.github.com/a/aUmcscHv

## JSON

# Formato Json
Aquí esta la especificación del lenguaje <https://www.json.org/>.
Para leer Jsons de manera fácil recomiendo instalar alguna librería. En el folder librerías incluyo una sugerencia.

Un par de ejemplos de Json para establecimientos y reseñas
## Establecimentos
```Json
Ejemplo 1

{
  "business_id": "1SWheh84yJXfytovILXOAQ",
  "name": "Arizona Biltmore Golf Club",
  "address": "2818 E Camino Acequia Drive",
  "city": "Phoenix",
  "state": "AZ",
  "postal_code": "85016",
  "latitude": 33.5221425,
  "longitude": -112.0184807,
  "stars": 3,
  "review_count": 5,
  "is_open": 0,
  "attributes": {
    "GoodForKids": "False"
  },
  "categories": "Golf, Active Life",
  "hours": null
}
Ejemplo 2
{
  "business_id": "QXAEGFB4oINsVuTFxEYKFQ",
  "name": "Emerald Chinese Restaurant",
  "address": "30 Eglinton Avenue W",
  "city": "Mississauga",
  "state": "ON",
  "postal_code": "L5R 3E7",
  "latitude": 43.6054989743,
  "longitude": -79.652288909,
  "stars": 2.5,
  "review_count": 128,
  "is_open": 1,
  "attributes": {
    "RestaurantsReservations": "True",
    "GoodForMeal": "{'dessert': False, 'latenight': False, 'lunch': True, 'dinner': True, 'brunch': False, 'breakfast': False}",
    "BusinessParking": "{'garage': False, 'street': False, 'validated': False, 'lot': True, 'valet': False}",
    "Caters": "True",
    "NoiseLevel": "u'loud'",
    "RestaurantsTableService": "True",
    "RestaurantsTakeOut": "True",
    "RestaurantsPriceRange2": "2",
    "OutdoorSeating": "False",
    "BikeParking": "False",
    "Ambience": "{'romantic': False, 'intimate': False, 'classy': False, 'hipster': False, 'divey': False, 'touristy': False, 'trendy': False, 'upscale': False, 'casual': True}",
    "HasTV": "False",
    "WiFi": "u'no'",
    "GoodForKids": "True",
    "Alcohol": "u'full_bar'",
    "RestaurantsAttire": "u'casual'",
    "RestaurantsGoodForGroups": "True",
    "RestaurantsDelivery": "False"
  },
  "categories": "Specialty Food, Restaurants, Dim Sum, Imported Food, Food, Chinese, Ethnic Food, Seafood",
  "hours": {
    "Monday": "9:0-0:0",
    "Tuesday": "9:0-0:0",
    "Wednesday": "9:0-0:0",
    "Thursday": "9:0-0:0",
    "Friday": "9:0-1:0",
    "Saturday": "9:0-1:0",
    "Sunday": "9:0-0:0"
  }
}
```
