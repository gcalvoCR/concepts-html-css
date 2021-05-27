## preprocesadores de CSS

extienden las funcionalidades de CSS común, permiten:
- tener variables, 
- funciones,
- mixins,
- reutilización de código, 
- flexibilidad en el desarrollo, 
- etc.

Preprocesador se escribe con sintaxis especial
Debe compilarse a CSS para ser comprendido por el navegador.


## Preprocessors mas conocidos
- LESS   --> http://lesscss.org/
- SASS   --> https://sass-lang.com/guide
- Stylus --> http://stylus-lang.com/

https://github.com/teffcode/sass-workshop


# Para instalar SASS 
- `npm install -g sass`

# Para correr el proyecto
- `sass --watch path/styles.scss path/index.css`


## SASS 
- Variables
- Herencia
- Anidamiento
- Operadores


```
$color_main: #FF4d3d !default;
$color_secondary: #c1310e !default;
p {
    color: $color_main;
}
```

Herencia
```
.flex {
    display: flex;
    align-items: center;

}


.header {
    @extend .flex;
    width: 100%;
    height: 80px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

Mixin --> para reutilizar codigo
```
@mixin btn-simple{
    width: 200px;
    border-radius: 1.5em;
    border: 1px solid grey;
}

.btn-modal {
    background-clor: #FF4D3D;
    @include btn-simple;
    color: white;

    :hover{
        background-color: #c1310e;
    }
}
```
