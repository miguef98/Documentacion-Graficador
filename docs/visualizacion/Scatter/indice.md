---
sidebar_position: 3
---

# indice

*String*

Llamamos indice al nombre de la columna de los datos que distingue entre distintos Scatter. Por ejemplo, si tenemos los datos:

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

En este caso, queremos visualizar dos nubes de puntos distintas: "Bienes" y "Servicios".

```js
"indice": "grupo"
```

En caso de no tener múltiples Scatters, se puede obviar el campo.