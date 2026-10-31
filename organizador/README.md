# Organizador de escritorio · Guía de taller

Web para el alumnado de **1.º ESO (Tecnología y Digitalización)** que acompaña la construcción del organizador de escritorio del kit **OPITEC 122.979**.

Funciona en cualquier navegador, en ordenador y en móvil. Toda la web está en un único archivo: `index.html`.

## Qué incluye

- **Guía paso a paso** (15 pasos): dibujos a color ampliables, instrucciones numeradas, avisos de seguridad, trucos, vocabulario y casillas de comprobación en cada paso.
- **Diario de taller**: una entrada por sesión, con fecha, pasos trabajados, qué se hizo, problemas, soluciones, reparto de tareas y valoración.
- **Memoria técnica**: guion de 11 apartados. Se rellena en parte sola con la guía, el diario y la autoevaluación. Se puede imprimir o guardar en PDF, descargar para editar en Word y copiar como texto.
- **Evaluación**:
  - **Autoevaluación**: cada alumno valora su trabajo con una escala de 1 a 4 y responde «lo que mejor he hecho» y «lo que tengo que mejorar».
  - **Coevaluación**: cada alumno valora a cada compañero del grupo y deja un comentario positivo y un consejo. Al guardarla, las respuestas dejan de verse en pantalla.
- **Idiomas**: por defecto se ve en **español con el inglés debajo**, para aprender el vocabulario. En Ajustes se puede elegir solo español o solo inglés.
- **Ajustes**: tamaño del texto (4 niveles), modo claro u oscuro, 5 combinaciones de colores (incluida una de alto contraste) y texto más espaciado para facilitar la lectura.
- **Panel del profesor**: para cambiar los textos, ver los resultados de la evaluación y publicar los cambios.

## Publicarlo con GitHub Pages

1. En [github.com](https://github.com), pulsa **New repository**. Ponle un nombre (por ejemplo `organizador-taller`), márcalo como **Public** y pulsa **Create repository**.
2. En el repositorio nuevo, pulsa **uploading an existing file**. Arrastra `index.html` y `README.md`, y pulsa **Commit changes**.
3. Ve a **Settings → Pages**. En **Branch**, elige `main` y la carpeta `/ (root)`, y pulsa **Save**.
4. Espera uno o dos minutos. La web quedará en `https://TU-USUARIO.github.io/organizador-taller/`.

### Enlaces directos

Añade al final de la dirección:

- `#paso-5` abre el paso 5 (de `#paso-0` a `#paso-14`).
- `#diario`, `#memoria` y `#evaluacion` abren esas pestañas.
- `#profesor` abre el **panel del profesor**. No aparece en los menús del alumnado.

## Panel del profesor: cambiar textos

Abre `https://TU-USUARIO.github.io/organizador-taller/#profesor`.

En **Editar textos** puedes cambiar:

- Cualquier texto de los 15 pasos: título, entradilla, instrucciones, avisos, trucos, palabras clave y casillas. Puedes añadir, quitar y reordenar elementos.
- Las normas de seguridad, las tablas, los nombres de las herramientas y los textos del diario, la memoria y la evaluación, incluidos los criterios.
- Los textos que aparecen dentro de los dibujos, con una vista previa que cambia mientras escribes. Los dibujos en sí no se pueden modificar.

Puedes editar en español y en inglés por separado. Para resaltar texto, escribe `**negrita**` o `` `45 mm` `` (aparece como una medida).

### Cómo llegan los cambios al alumnado

Lo que cambias se guarda como **borrador**, solo en tu navegador. Mientras haya un borrador, verás un aviso amarillo en la web. Para publicarlo:

1. En el panel, ve a **Publicar los cambios** y pulsa **Descargar textos.json**.
2. En tu repositorio, pulsa **Add file → Upload files**, arrastra `textos.json` (en la misma carpeta que `index.html`) y pulsa **Commit changes**.
3. En uno o dos minutos, el alumnado verá los textos nuevos. Después pulsa **Descartar el borrador** para ver la web igual que ellos.

Con `textos.json` aparte, si más adelante subes una versión nueva de `index.html`, tus textos se mantienen.

**Otra opción:** **Descargar index.html con los textos dentro** genera un único archivo con tus textos incluidos. Sirve para Google Sites o para usarlo sin internet. Si en el repositorio también hay un `textos.json`, mandan los textos de ese archivo.

En el mismo apartado puedes elegir el **idioma inicial** con el que se abre la web para el alumnado.

## Panel del profesor: resultados de la evaluación

En **Evaluación de los grupos** verás, para cada alumno, la media de su autoevaluación, la media de la coevaluación que ha recibido y cuántos compañeros le han evaluado. En «Detalle» verás cada criterio y los comentarios de sus compañeros, con su nombre.

- Aparecen los datos del grupo que ha trabajado en ese ordenador.
- Para ver otros grupos, pide a cada grupo su copia de seguridad (**Guardar copia (archivo)**, por ejemplo entregada por Classroom) y cárgalas todas a la vez con **Cargar copias de grupos**. Estos archivos solo se leen: no se guardan en el navegador.
- **Descargar resultados para Excel** genera un `.csv` con todos los alumnos, todos los criterios y los comentarios.

Escala por defecto: 1 = Todavía no · 2 = A veces · 3 = Casi siempre · 4 = Siempre.

## Dónde se guardan los datos del alumnado

No hay servidor ni cuentas de usuario. El diario, la memoria, la evaluación, las fotos, las casillas y los ajustes se guardan **solo en el navegador del ordenador que se está usando**.

- Si un grupo cambia de ordenador, o los ordenadores del aula se borran al apagarse, debe pulsar **Guardar copia (archivo)** al acabar la sesión y **Cargar copia** en la siguiente.
- Si dos grupos usan el mismo ordenador y el mismo navegador, comparten los datos.
- **Privacidad de la coevaluación:** al guardarla, las respuestas dejan de verse. Pero, como todo está en el mismo ordenador, un compañero que pulse «Cambiar mis respuestas» con el nombre de otro podría verlas. No es un sistema seguro: para coevaluaciones delicadas, conviene que cada alumno la haga en un momento en que el resto no esté delante.
- El panel del profesor no tiene contraseña: solo está escondido. Si un alumno entra en `#profesor` y cambia textos, solo afecta a su navegador.

## Imprimir la memoria y guardarla en PDF

En **Memoria técnica**, pulsa **Imprimir o guardar en PDF** y elige «Guardar como PDF» como impresora. El archivo **Word (.doc)** sirve para seguir editando el texto, pero no incluye los dibujos.

## Notas sobre el contenido

- Los dibujos de las piezas A y B son **orientativos**. Las medidas exactas son las de las plantillas en papel del kit (páginas 5, 7 y 9), que no se incluyen.
- La guía no pide usar el móvil en clase. Para colocar el tope 3c se usa un cartón del tamaño de un móvil (unos 7 × 15 cm).
- Detalles que las instrucciones originales no aclaran: la guía usa dos listones de 250 mm; dice «lima triangular» donde la lista del kit pone «lija triangular»; la muesca de 2a y 2b va en el extremo que queda fuera.

## Créditos

Guía adaptada a partir de las instrucciones de montaje del kit OPITEC 122.979. OPITEC es una marca de su propietario; esta web no es un producto oficial de OPITEC.
