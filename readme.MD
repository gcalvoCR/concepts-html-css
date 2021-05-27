# Useful tips

# Validacion de HTML
- Usar servicio WWW3C --> `https://validator.w3.org`
- Instalar VS plugin --> HTMLHint de mkaufman.htmlhint para analisis de errores en tiempo real

# colores
- explorar `https://colorhunt.co/palettes`

# Notas
- Explorar los pseudo-classes y pseudo-elements de Mozilla Firefox
- Si uno quiere que el tamaño de la caja este dado por el padding añadir:
```
.attribute {
   box-sizing: border-box; 
}
```

## Flexbox

https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://flexboxfroggy.com/


## Grid
https://css-tricks.com/snippets/css/complete-guide-grid/
https://labs.jensimmons.com/
https://cssgridgarden.com




## Topics
- DOM
- CCSOM
- RenderTree
- Box Model
  - width/height, padding, border, margin
- medidas absolutas
  - cm, in, mm, px, pt, pc
- medidas relativas 
  - vmax, em, ch, ex, vmin, vh, vw
- Displays en CSS
  - `Block`: Como cuando escribimos, de izquierda a derecha
  - `Inline`: Linea donde escribimos
  - `Inline-Block`: igual a inline pero respeta width y height que se le asigne
  - `None`: Para ocultar elementos del DOM
  - `Table`: para elementos table
  - `Flex`: para alinear elementos
    - flex siempre necesita el display:flex y otras propiedades --> justify-content y align-items
  - `Grid`: en el elemento contenedor o padre

- Posicionamiento en CSS
  - `position:absolute`: --> `div { position: absolute: right: 0px; }`
  - `position:relative`: --> en relacion a su posicion normal
  - `position:fixed`: --> en relacion con la ventana del navegador
  - `position:sticky`: --> se posiciona en funcion de la posicion de desplazamiento del usuario
  - `position:static`: --> elementos son estaticos por defecto
  - `position:initial`: --> ubica el elemento en la posicion que tiene de forma predeterminada
  - `position:inherital`: --> el valor hereda esta propiedad de su elemento padre



Color

https://colorhunt.co/
 
Font-family

https://fonts.google.com/
 
Transition

https://www.w3schools.com/css/css3_transitions.asp

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

https://css-tricks.com/almanac/properties/t/transition/
 
Animation

https://www.w3schools.com/css/css3_animations.asp

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations

https://css-tricks.com/almanac/properties/a/animation/

