[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/fGeLcsqO)
# A5-SOBRE-XML

## 1. Indica las características propias del lenguaje XML.
- **Extensible**: Permite definir etiquetas personalizadas.
- **Legible para humanos y máquinas**: XML es fácil de leer y comprender.
- **Estructura jerárquica**: Los datos se organizan en una estructura de árbol.
- **Autodescriptivo**: Las etiquetas describen el contenido.
- **Independiente de plataforma**: Se puede usar en cualquier sistema operativo o aplicación.
- **Validación mediante DTD o XML Schema**: Los documentos pueden ser validados para verificar su estructura.

## 2. Identifica la estructura de un documento XML y sus reglas sintácticas.
- Un documento XML debe tener un **nodo raíz**.
- Las etiquetas de apertura y cierre deben coincidir.
- Las etiquetas deben estar correctamente anidadas.
- Los atributos deben ir entre comillas.
- Se deben evitar caracteres reservados (e.g., `<`, `>`, `&`) a menos que estén codificados o en entidades.

## 3. En XML qué es un nodo raíz.
El **nodo raíz** es el elemento principal que engloba todos los demás elementos de un documento XML. Solo puede haber un nodo raíz por documento, y todos los demás elementos deben estar anidados dentro de él.

## 4. Indica qué es un elemento vacío. Ejemplos.
Un **elemento vacío** en XML es un elemento que no contiene contenido ni elementos anidados. Se puede escribir de dos maneras:
- `<elemento></elemento>`
- `<elemento/>`

## 5. Qué sentido tiene crear documentos XML bien formados.
Un documento **bien formado** sigue todas las reglas sintácticas de XML. El sentido de crear documentos bien formados es asegurar que puedan ser interpretados correctamente por cualquier analizador XML, garantizando la interoperabilidad entre diferentes sistemas y aplicaciones.

## 6. Qué es un espacio de nombres. Ventajas de uso.
Un **espacio de nombres** en XML es un mecanismo que permite evitar conflictos entre elementos con el mismo nombre en diferentes contextos, mediante la adición de prefijos que diferencian los elementos.

### Ventajas:
- Evita conflictos de nombres cuando se combinan documentos XML de distintas fuentes.
- Permite el uso de elementos de diferentes vocabularios en un mismo documento.
- Facilita la interoperabilidad entre diferentes sistemas XML.

## 7. Entidades en XML. Crea un XML con las entidades vistas en clase.
Las **entidades** en XML son representaciones de caracteres especiales o secuencias de caracteres que tienen un significado especial en XML.

## 8. Comentarios en XML. Muestra uno de los ejercicios anteriores con el enunciado dentro de un comentario.
Los **comentarios** en XML se introducen con `<!--` y se cierran con `-->`. No son procesados por los analizadores XML.

### Ejemplo con comentario:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<!-- Este es un comentario: Ejemplo de un nodo raíz con un título -->
<libro>
  <titulo>XML para principiantes</titulo>
  <autor>Juan Pérez</autor>
  <año>2023</año>
</libro>

Ejemplo pregunta 7:
Ejemplo con algunas entidades:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mensaje>
  ¡Bienvenido a XML &amp; Co!
  &lt;Este es un ejemplo de uso de entidades&gt;
</mensaje>
