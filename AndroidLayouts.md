# Diseños(layouts) comunes en andrdoid

## Linear layout
Un diseño que ordena las vistas (elementos de diseño) horizontalmente en una sola columna o verticalmente en una sola fila.

#### Atributos principales

| Atributo | Valor | Finalidad
|-------------|--------------------------| ---------------------------------------|
|  `android:orientation ` |  `vertical, horzontal`  |Establecer la dirección en la que se organizan los elementos. |
|  `android:gravity ` |  `top, bottom,left,right,center,center_horizontal, center_vertical`  |Define cómo se alinean los elementos hijos dentro de **Linear Layout**.|


## Relative layout
Es un grupo de vistas(view group) que muestra vistas secundarias en posiciones relativas. La posición de cada vista puede especificarse como relativa a elementos del mismo nivel (como a la izquierda de otra vista o por debaje de ella) o en posiciones relativas al área superior (como alineada a la parte inferior, izquierda o central).

## Constraint layout
Constraint Layout te permite crear diseños grandes y complejos con una jerarquía de vistas plana, sin grupos de vistas anidadas. Es similar a **Relative Layout** en el sentido de que todas las vistas se presentan de acuerdo con las relaciones entre las vistas del mismo nivel y el diseño de nivel superior, pero es más flexible que RelativeLayout y más fácil de usar con el editor de diseño de android studio.