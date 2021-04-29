Proyecto: Platzi VIdeo.
Curso: Curso de Frontend Developer.

-----------------------------------


DOM - Document Object Model
    TRasformacion de html a objetos entendibles por el navegador.
CSSOM - Representación de objetos también pero de CSS.
RENDER TREE - Junta el DOM y el CSSOM.

Procesos:
- Procesa HTML y construye el DOM.
- Procesa CSS y construye el CSSOM.
- DOM + CSSOM = Render Tree.
- Ejecuta el diseño en el reder tree
- Pinta el Nodo en la pantalla.

-----------------------------------

Conceptos iniciales HTML.

Anidamiento. Un elemento dentro de otro.
Elementos vacíos. Como img necesitan de unos atributos especiales.
    src: recurso.
    alt: descripción de la imagen.

-----------------------------------

**Anatomia de un Documento HTML**
- <!DOCTYPE html>
    Se define que se utilizara bajo el estándar HTML 5
- <html lang = "en"></html>
    Representa la raíz de nuestro documento HTML. 
    Todos los demás elementos deber ser descendientes de este elemento
- <head></head>
    En el head siempre vamos a encontrar los metadatos
    (que se escriben con la etiqueta vacía <meta>) del documento
    que vamos a escribir, incluyendo también enlaces (que por lo general
    son de nuestro archivo de estilos, tipografías)
- <meta>
    Deine los metadatos que no pueden ser definidos usando otro elemento HTML,
    como por ejemplo el tipo de codificació; UTF-8.
- <title></title>
    Aquí definimos el título de nuestro documento, sólo puede contener texto
    y se muestra en la pestañita de la página.
- <body></body>
    Es la única etiqueta body que debe aparecer en nuestro documento y representa
    todo el contenido principal. Aquí es donde escribimos las etiquetas div,
    footer, h1, p, main, etc.

-----------------------------------

**Código Semántico**

Es importante tenerlo para distribución y organización.
Nos sirve en el SEO.

-----------------------------------

**CSS**

Da estilos a nuestro HTML.

*  Selector universal.
Tipo - todo el elemento.
Clases - Selección un grupo en específico de elementos.
    Pseudo-clases. Selectores en específico dentro de un clase.
ID - Selección de un elemento específico

-----------------------------------

**Modelo de caja**

1. Contenido.
2. Padding.
3. Border.
4. Margin.

**Valores absolutos**

Relativos.
Ansolutos.