# Mis estilos para SASS

Archivos base para mis proyectos con SASS

## Mixins

- **Flexbox:**
  - **flex:** Este mixin se refiere a las propiedades de flexbox y se puede agrupar con otros mixins relacionados con flexbox, como flex-wrap, justify-content, align-items, etc.


- **Grid:**
  - **grid:** Este mixin se relaciona con las propiedades de la cuadrícula CSS y se puede agrupar con otros mixins relacionados con cuadrículas, como grid-template-rows, grid-template-areas, etc.

- **Dimensiones:**
  - **fullv:** Este mixin se utiliza para establecer el ancho y alto al 100% de la ventana del navegador.
  - **full:** Este mixin se utiliza para establecer el ancho y alto al 100% del elemento contenedor.

- **Estilos de elementos:**
  - **input:** Este mixin se utiliza para aplicar estilos a los elementos de entrada (inputs).
  - **button:** Este mixin se utiliza para aplicar estilos a los botones.
    radiusTop y radiusBottom: Estos mixins se utilizan para aplicar bordes redondeados en las esquinas superiores o inferiores.

- **Estilos visuales:**
  - **scrollbar:** Este mixin se utiliza para personalizar las barras de desplazamiento en navegadores webkit.
  - **gradient:** Este mixin se utiliza para generar gradientes lineales entre dos colores.
  - **text-shadow:** Este mixin se utiliza para aplicar sombras a los elementos de texto.
  - **animation:** Este mixin se utiliza para agregar animaciones a los elementos.
  - **box-shadow:** Este mixin se utiliza para aplicar sombras a las cajas.
  - **transition:** Este mixin se utiliza para aplicar transiciones suaves a las propiedades.

- **Posicionamiento absoluto:**
  - **pAbsolte:** Este mixin se utiliza para posicionar un elemento de manera absoluta.
  - **centerAbsolute:** Este mixin se utiliza para centrar un elemento absolutamente posicionado horizontalmente.
- **Descontinuados:**
  - center
  - rowCenter
  - columCenter
  - column
  - row

## Componentes

| Dispositivo | Página principal | Barra de navegación |
| ----------- | ---------------- | ------------------- |
| Desktop     | Home             | Navbar              |
| Tablet      | Home             | Navbar              |
| Teléfono    | Home             | Navbar              |

## Settings

### Screens

| Dispositivo | Tamaño |
| ----------- | ------ |
| Computadora |        |
| Grande      | 1200px |
| Mediana     | 991px  |
| Tablet      |        |
|             | 767px  |
| Teléfono    |        |
|             | 480px  |

## Configuracion basica

```SASS
@import "./mixins";

*{
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    height: 100vh;
    width: 100%;
    font-size: 10px;
}

/* Para React */
#root{
    height: 100vh;
    .Routers{
        height: 100%;
        display: flex;
        flex-direction: column;
    }
}

a{
  text-decoration: none;
  color: white;
}

.hide{
    display: none;
}
.displayBlock{
    display: block;
}
.displayFlex{
    display: Flex;
}
```

