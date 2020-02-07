# Ejercicio arquitectura

Eligiendo una de las estrategias descritas anteriormente (Clean, Capas, Hexagonal, DDD) elaborar el landing page
 de una pagina que debe mostrar reseñas de películas.

Requisitos:

## Primera parte:
```
- Equipos maximo de 3 personas.
- Deben hacer fork a este repositorio.
- Deben incluir en el md la descripción y justificación de las decisiones de arquitectura que tomaron junto a la lista de los integrantes.
- La fuente de datos debe ser derivada del dump adjunto en este repositorio.
- El front debe ser simple (No se va a tomar en cuenta el diseño mas allá de que sea legible).
- Tiempo límite: 3 horas.
- PHP, con libertad de elección del framework.
- Deben simplificar su diseño de tal forma que pueda ser realizado en el tiempo estipulado.
```


## Segunda parte:

Basados en el resultado de la primera iteración, Ahora deben desconectar su fuente de datos local y 
conectar la fuente al api themoviedb themoviedb.

```
- El front cambiará, ya no es un html sino un JSON.
- Deben consumir el endpoint https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&language=es&api_key=<api_key>
- Solicitar el api_key.
- Deben describir los cambios que hicieron (justificar) en el md
- Tienen 1 hora.
- URL para la obtención de las imagenes: http://image.tmdb.org/t/p/w500
```
