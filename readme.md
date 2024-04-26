# BEM Y SUITCSS

## BEM (Block Element Modifier)

BEM es una metodología de desarrollo web que se centra en la modularidad y reutilización del código CSS. Utiliza una convención de nomenclatura clara y estructurada que divide los estilos en bloques, elementos y modificadores.

## Convención de Nomenclatura BEM:

**Bloque (Block)**:Representa un componente autónomo y reutilizable en la interfaz de usuario.

Ejemplo en HTML:

```

<div class="block"></div>

```

Dentro de este bloque se pueden definir elementos y modificadores utilizando misma convención.

**Elemento (Element)**:Una parte interna y específica de un bloque en la metodología BEM, que no tiene un propósito fuera de ese bloque. Ayuda a organizar y modularizar el código CSS.

Ejemplo en HTML:

```

<img class="block__img" src="img/bem imagen.png" alt="">

<p class="block__paragraph"></p>

```

**Modificador (Modifier)**:Es una entidad que define la apariencia, estado o comportamiento de un bloque o elemento.

Ejemplo en HTML:

```

<button class="button button--large">Enviar</button>

```

## SUITCSS

SUITCSS es otra metología de desarrollo web que se basa en la creación de estilos modulares y reutilizables. También utiliza una convención de nomenclatura clara pero se enfoca en componentes más que en bloques,elementos y modificadores.

## Convención de Nomenclatura SUITCSS:

**Componentes (Component)**:Representa un componente autónomo y reutilizable en la interfaz del usuario.

Ejemplo en HTML:

```

<div class="component">

```

**item (item)**:Partes individuales de un componente que realizan una función específica.

Ejemplo en HTML:

```

<img class="component-items" src="img/SUITCSS.png" alt="">

```

SUITCSS utiliza " - " para mantener una sintaxis más simple y legible.

**Modificador (Modifier)**:Variaciones o ajustes aplicados a un componente o item para cambiar su apariencia 

Ejemplo en HTML:

```

<button class="button button--boton">Enviar</button>

```









