---
sidebar_position: 4
---

# instancia

*String*

La categoria instancia indica el nombre de la columna de los datos que distingue entre distintas instancias del mismo Scatter (establecido por la variable indice). Por ejemplo, si tenemos los datos:

| grupo | categoria | indicador | valor |
| ----- | --------- | --------- | ----- |
| "Bienes" | "Agro y pesca" | "Share sectorial" | 6.37078835279759 |
|"Bienes"|"Agro y pesca"|"Share VAB"|7.91809328091021|
| "Bienes" | "Petróleo y minería" |"Share sectorial" | 0.49304925036626 |
|"Bienes"|"Petróleo y minería"|"Share VAB"|4.24945668586465|
|"Servicios"|"Comercio"|"Share sectorial"|"17.7400342023681"|
|"Servicios"|"Comercio"|"Share VAB"|"19.5639147446179"|
|"Servicios"|"Hotelería y restaurantes"|"Share sectorial"|"3.0894917708572702"|
|"Servicios"|"Hotelería y restaurantes"|"Share VAB"|"2.18226948180529"|

En este caso, la columna "categoria" distingue los diferentes puntos: "Agro y pesca" / "Petróleo y minería" dentro del Scatter asociado a "Bienes". Y "Comercio" / "Hotelería y restaurantes" dentro del Scatter asociado a "Servicios".

```js
"instancia": "categoria"
```