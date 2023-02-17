En HTML, CSS y JavaScript, las "queries" son consultas que se realizan para seleccionar elementos y manipular su estilo o comportamiento.

En CSS, las "media queries" son una técnica para aplicar estilos CSS en función del tamaño de la pantalla o de otras características del dispositivo de visualización. Por ejemplo, puedes usar una media query para aplicar un estilo diferente en un dispositivo móvil que en un ordenador de escritorio. Aquí tienes un ejemplo:

CSS:

/* Estilo para pantallas grandes */
@media (min-width: 992px) {
  body {
    background-color: lightblue;
  }
}

/* Estilo para pantallas pequeñas */
@media (max-width: 991px) {
  body {
    background-color: lightgreen;
  }
}


En JavaScript, las "queries" también se pueden usar para seleccionar elementos del DOM (Document Object Model) y manipularlos. Por ejemplo, puedes usar una query para seleccionar todos los elementos de una clase y cambiar su contenido:

javascript:

// Selecciona todos los elementos con la clase "mi-clase"
const elementos = document.querySelectorAll('.mi-clase');

// Cambia el contenido de cada elemento
elementos.forEach(elemento => {
  elemento.textContent = 'Nuevo contenido';
});

En resumen, las queries son una herramienta poderosa para manipular elementos y aplicar estilos o comportamientos en función de ciertas condiciones.

Además de las media queries en CSS y las queries para seleccionar elementos en JavaScript, también existen otras formas de hacer queries en el desarrollo web. Por ejemplo:

En SQL, las queries se utilizan para recuperar y manipular datos en una base de datos. Por ejemplo, puedes usar una query para recuperar todos los registros de una tabla:

sql:

SELECT * FROM mi_tabla;

En GraphQL, las queries se utilizan para solicitar datos de una API de manera más eficiente y flexible que con REST. Por ejemplo, puedes usar una query GraphQL para recuperar información sobre un usuario y sus publicaciones:

javascript:

query {
  usuario(id: 123) {
    nombre
    publicaciones {
      titulo
      contenido
    }
  }
}

En cualquier caso, la idea fundamental detrás de las queries es la de hacer una consulta para seleccionar y manipular datos o elementos de acuerdo a ciertas condiciones.