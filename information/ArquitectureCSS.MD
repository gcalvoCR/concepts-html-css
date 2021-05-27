# Arquitectura CSS

Los objetivos son:

- `Predecible` > Escribir reglas claras.
- `Reutilizable` > No escribir codigo redundante.
- `Mantenible` > Que sea facil de leer y adaptarnos a los estandares.
- `Escalable` > Que pueda crecer facilmente pero sin afectar el rendimiento.

Buenas practicas

- Establecer reglas para que el equipo se entienda.
- Explicar la estructura base o dar los fundamentos del proyecto a un nuevo integrante.
- Evitar hojas de estilo muy extensas
- Tener una buena documentación explicando ciertos aspectos del codigo.


# OOCSS, BEM, SMACSS, ITCSS y Atomic Design

### OOCSS (Object Oriented CSS)
Lo que se quiere es abstraer las clases y reutilizarlas

```
<style>

        .globalwidth{
            width: 100%;
        }
        .header{
            background-color: #21C08B;
        }
        .footer {
            background-color: #788998;
        }
    </style>
<header class="header globalwidth">Header</header>
<footer class="footer globalwidth">Footer</footer>
```

### BEM (Block element modify)
El separa los bloques, los elementos y los modificadores
```
    <header class="header">
        <button class="header__button--red">RED</button>
        <button class="header__button--yellow">YELLOW</button>
    </header>
```

### SMACSS (arquitectura de CSS escalable y Modular)
Scalable and Modular Arquitecture for CSS. Arquitectura de css escalable y modular. PAra eso se realizan cinco pasos

Dividir nuestro css en componentes base
Definir Layout. Elementos que se utilizan solo una vez. ej. Footer, Header
Definir Modulos. Componentes que se usan mas de una vez
Definir Estados. Estos estados definen los cambios que existen en nuestros elementos/componentes. ej. Cambio de color cuando hacen hover
Definir Temas. Separar los temas y sus cambios. Si tuvieras temas

Base --> Componented base, Botones
layoyt --> elementos que se usan una sola vez
Module --> elementos que usamos mas de una vez
Estado --> de los elementos
Temas --> Cuando cambian los temas cambiamos colores y estilo

### ITCSS (Inverted triangle of CSS)
Inverted Triangle CSS. Triangulo Invertido de CSS. Lo que nos indica esta metodologia es poder dividir todos nuestros archivos de css en ciertas partes para que no se mezclen.
Triangulo invertido, desde arriba hacia abajo:

Ajustes
Herramientas
Generico
Elementos
Objetos
Componentes
Utilidades

Dividimos
- ajustes
- herramientas
- genericos
- elementos
- objetos
- componentes
- utilidades


### Atomic Design
- Atomos
- Moleculas
- Organismos
- Templates
- Paginas