# js20_quote-generator
Quote generator from "JS 20 projects course"

Live project: https://jlaguilargomez.github.io/vanilla_js20_quote-generator/

-----
# Quote generator

### A tener en cuenta ...

- Fondos de pantalla curiosos
- Base config para CSS
- CORS!
- Botón curiosete
- Manage DOM link

### GitHub

[jlaguilargomez/js20_quote-generator](https://github.com/jlaguilargomez/js20_quote-generator)

## Project

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/49097d00-e570-4ec9-a88d-6d7287cf3143/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/49097d00-e570-4ec9-a88d-6d7287cf3143/Untitled.png)

Para el fondo de la página, usamos la siguiente web:

[Hero Patterns](https://www.heropatterns.com/)

**NOTA: en todos los proyectos se comienza con el siguiente estilo de base:**

```css
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  background-color: #ffffff;
}
```

Así estilamos el botón:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2b863874-bf0d-4d39-b32c-cce6adfc0be2/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2b863874-bf0d-4d39-b32c-cce6adfc0be2/Untitled.png)

Para obtener las "*quotes*", usamos:

[Quotes and expressions. The most inspiring expressions of mankind.](https://forismatic.com/en/api/)

En este proyecto volvemos a usar la **API Cors-Anywhere**:

[](https://cors-anywhere.herokuapp.com/)

**¿POR QUÉ?: cuando hacemos una llamada a una API pública desde un sitio externo, se nos suele bloquear para prevenir problemas de seguridad.**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b322f02c-8c90-4fd0-a26b-90e72a2c4777/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b322f02c-8c90-4fd0-a26b-90e72a2c4777/Untitled.png)

Necesitamos "*pasar*" previamente por un **PROXY** que nos permite llamar a través de él a la API que necesitamos.

Se incluye el siguiente recurso en el proyecto ***(manejar el DOM con Vanilla JS)***:

[Manage HTML DOM with vanilla JavaScript](https://htmldom.dev/)
