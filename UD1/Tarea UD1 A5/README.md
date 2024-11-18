## 1. Características propias del lenguaje XML
- Extensible, autodefinido, legible por humanos y máquinas.
- Sensible a mayúsculas, multiplataforma y estructurado.

## 2. Estructura y reglas sintácticas de un documento XML
- **Declaración XML**: `<?xml version="1.0" encoding="UTF-8"?>`
- **Elemento raíz**: Contiene todos los demás elementos.
- **Elementos**: Con etiquetas de apertura y cierre.
- **Atributos**: Información adicional en comillas.
- Regla: Solo un nodo raíz, etiquetas correctamente cerradas, no superposición.

## 3. ¿Qué es un nodo raíz?
El elemento que contiene todos los demás elementos en un documento XML. Ejemplo: `<libros>`.

## 4. ¿Qué es un elemento vacío? Ejemplos
Un elemento sin contenido, ejemplo: `<elemento />` o `<elemento></elemento>`.

## 5. ¿Por qué crear XML bien formado?
- Asegura interoperabilidad y facilita su procesamiento.

## 6. Espacio de nombres y ventajas
Un espacio de nombre diferencia elementos con el mismo nombre. Ventajas: evitar colisiones y modularidad.

<doc xmlns:ns="http://ejemplo.com">
     <ns:persona>Juan</ns:persona>


## 7. Entidades en XML
Caracteres especiales como &lt; (<), &gt; (>), etc.

xml
Copiar código
<mensaje>Bienvenido &lt;XML&gt;</mensaje>
8. Comentarios en XML
xml
Copiar código
<!-- Ejemplo con entidades -->
<mensaje>Usamos &lt;entidades&gt; y &amp;.</mensaje>