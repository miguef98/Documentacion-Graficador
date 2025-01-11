---
sidebar_position: 10
---

# color

*String / list[String] / dict[String -> String]*

Color para el Scatter. Hay tres tipos de inputs posibles:
- *String*: Valor hexadecimal del color. Si tenemos multiples series, todas van a tener el mismo color.
```js
"color": "#abcdef"
```
- *list[String]*: Lista de colores hexadecimales. El orden es el de aparición en el dataset.
```js
"color": ["#abcdef", "#123456"]
```
- *dict[String -> String]*: Diccionario que asigna colores hexadecimales a cada serie.
```js
"color": { "Bienes": "#abcdef", "Servicios": "#123456"}
```

Si no se elige ningún color, se usa la escala default de [Apache ECharts](https://echarts.apache.org/en/option.html#color).
