# Práctica: Web "AlmagaraBooks"

Hola, aquí te dejo la práctica de la web de la librería. La idea ha sido pasar el dibujo que tenía en Figma a una web de verdad, intentando que quede igualita y que funcione bien.

## 🛠️ ¿Cómo lo he hecho?

Para que la web se parezca al diseño original, me he apoyado un poco en la Inteligencia Artificial, pero usándola para "traducir" lo que yo veía en la imagen a código.

Básicamente, le iba pasando capturas de pantalla a una IA (**Antigravity**) para que me ayudara a sacar los colores exactos y a ver dónde fallaban los tamaños. Si veía que la portada no se parecía a mi foto, le decía "oye, esto no cuadra", y lo íbamos arreglando paso a paso. También he usado un autocompletador (**Windsurf**) para escribir el código más rápido.

Pero ojo, **que hay mucho curro mío detrás**. La IA te da una base, pero yo he estado ahí ajustando los márgenes al milímetro, cambiando cosas que no me gustaban y asegurándome de que todo funcionara como yo quería, he cambiado colores que me dijiste que se veian mal

---

## 💻 Lo que he hecho

He intentado cumplir con todo lo que pedías en el ejercicio:

### 1. Código ordenado

He usado las etiquetas que tocan (`<header>`, `<nav>`, `<main>`...) para que no sea un lío de "divs" sin sentido. El diseño (CSS) está en su propio archivo y todo bien separado.

### 2. Diseño chulo

He usado sistemas modernos (Flexbox y Grid) para colocar las cajas y las columnas en su sitio.

- **Fuentes**: He puesto dos tipos de letra distintos (una fuerte para títulos y otra normal para leer).
- **Detalles**: He cuidado que quede bonito con sombras suaves, bordes redondeados en las tarjetas y los colores rojo/marrón que tocaban.

### 3. Las partes de la web

- **Menú de arriba**: Se queda fijo cuando bajas para que siempre lo tengas a mano. He juntado el buscador y los botones en una especie de cápsula en el centro que queda muy moderna.
- **Portada (Index)**:
  - **Bienvenida**: El título grande centrado y abajo el texto y la foto.
  - **Carrusel de Libros**: Esto tiene su historia. Es una fila de libros que se mueve sola todo el rato, pero si pasas el ratón o tocas, se para para que puedas mirar bien.
  - **Mapa**: He puesto dónde están las tiendas.
- **Tienda**: He dividido la pantalla en dos trozos. A la izquierda los filtros (con botones rojos) y a la derecha todos los libros colocados en rejilla, todos iguales.
- **Pie de página**: iconos de redes sociales, los enlaces de privacidad y mi nombre.