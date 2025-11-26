## ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero diseñado para ser fácil de leer y escribir. Convierte texto plano en HTML de forma sencilla. GitHub usa una extensión llamada *GitHub Flavored Markdown* (GFM) que añade funciones como tablas y listas de tareas.

---

## Uso básico (sintaxis)

## Negritas: Usa dos asteriscos o guiones bajos.
 *itálica* o _itálica_
**negrita** o __negrita__
***negrita e itálica***


## Listas Ordenadas: Se pueden crear listas ordenadas y desordenadas con números o guiones. Se crean con números seguidos de un punto

1. Primer elemento
2. Segundo elemento


## Listas No Ordenadas: Listas donde los elementos no llevan número, solo puntos o guiones
- Elemento
- Otro elemento


## Enlaces: Se pueden agregar enlaces con la sintaxis "[texto](enlace).
[Texto del enlace](https://url.com)


## Imagenes:  La misma sintaxis que los enlaces, pero con un ! antes del texto
![Foto de Adolfo](https://i.pinimg.com/236x/5f/2d/3a/5f2d3a86b3e3b551a536cdc67c04982c.jpg)


## Código en línea: Usa tildes invertidas para el código en línea
`código en línea`


## Encabezados: Se usan almohadillas (#) para los encabezados. Se pueden crear encabezados de varios niveles usando # (hasta 6 niveles)
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3


## Citas: Usas el símbolo > al inicio de la línea que sirven para resaltar un texto como si fuera una cita, comentario o nota importante, y doble >> para citas dentro de citas
> Esto es una cita
>> Citas anidadas


## Lineas horizontales: Usa tres o más: ---, ***, ___ que sirven para dividir secciones en un documento, como una separación visual
---


## Usa una sola comilla invertida: Usa una sola comilla invertida en las palabras del texto
Usa el comando `git status` para ver el estado.


## Tabla básica: Cada columna se separa con | . La segunda fila obligatoriamente lleva guiones. Puedes usar cualquier número de guiones, mientras estén ahí
| Nombre | Edad |
|--------|------|
| Ana    | 17   |
| Luis   | 19   |


## Tablas más avanzadas: Puedes alinear el texto dentro de cada columna usando dos puntos (:) en la fila de separación. Izquierda: :---  Centrado: :---:  Derecha: ---:

| Izquierda | Centrado | Derecha |
|:--------- |:-------: | ------: |
| a         | b        | c       |
| texto     | 123      | 45.6    |
