+++
title = "Uso del Markdown"
+++

Markdown es un lenguaje de marca que de una forma sencilla agrega formato a textos en la web y
funciona incorporando algunos caracteres a nuestro contenido.

Podemos ver tres secciones de markdown difernetes:

- [Markdown básico](./basico/)
- [Markdown de gráficos](./graficos/)
- [Markdown extendido](./extendido/)

### Markdown en HUGO

Markdown es el formato de contenido predeterminado de Hugo.  
Hugo renderiza nativamente Markdown a HTML usando Goldmark. Goldmark es rápido y se ajusta a las especificaciones 
de CommonMark y GitHub Flavored Markdown. Puedes configurar Goldmark en la configuración de tu sitio.  

Hugo proporciona características personalizadas de Markdown que incluyen:

- **Atributos**  
  Aplica atributos HTML como clase e id a las imágenes de Markdown y a los elementos 
  de bloque, incluyendo citas, bloques de código delimitados, encabezados, reglas 
  horizontales, listas, párrafos y tablas.

- **Extensiones**  
  Aprovecha las extensiones integradas de Markdown para crear tablas,
  listas de definiciones, notas al pie, listas de tareas, texto insertado,
  texto resaltado, subíndices, superíndices y más.

- **Matemáticas**  
  Incluye ecuaciones y expresiones matemáticas en Markdown 
  usando la sintaxis de tipografía LaTeX o TeX.

- **Ganchos de renderizado**  
  Sobrescribe la conversión de Markdown a HTML al renderizar bloques de código delimitados, 
  encabezados, imágenes y enlaces. Por ejemplo, renderiza cada imagen independiente 
  como un elemento HTML.








