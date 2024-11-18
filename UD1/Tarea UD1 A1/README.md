# Lenguajes de Marcas

## ¿Qué es un lenguaje de marcas?
Un lenguaje de marcas es un sistema de etiquetado que organiza y estructura datos en documentos. Utiliza etiquetas que delimitan el contenido, haciéndolo legible para humanos y máquinas.

## Características generales
1. Uso de etiquetas.
2. Legible por humanos y máquinas.
3. Estructura jerárquica.
4. No contiene lógica de programación.
5. Portabilidad entre plataformas.

## Clasificación
1. **Generales**: HTML, XML.
2. **Específicos**: Markdown, LaTeX.
3. **De estilo**: CSS.

## Ámbitos de aplicación
- Desarrollo web.
- Intercambio de datos.
- Documentación científica.
- Procesamiento de textos.
- Automatización de sistemas.

## Ejemplos de lenguajes

### 1. HTML
```
<!DOCTYPE html>
<html>
  <body>
    <h1>Título</h1>
  </body>
</html>
```
Navegadores web procesan HTML para crear páginas.

### 2. iCalendar
```
BEGIN:VCALENDAR
VERSION:2.0
BEGIN:VEVENT
UID:12345678
DTSTAMP:20211001T123000Z
DTSTART:20211002T090000Z
DTEND:20211002T100000Z
SUMMARY:Reunión con el equipo
END:VEVENT
END:VCALENDAR
```

* Estructura: iCalendar utiliza bloques BEGIN y END para definir eventos y otros datos del calendario, como fecha y hora (DTSTART, DTEND).
Aplicación asociada: Se procesa en aplicaciones de calendario como Google Calendar, Microsoft Outlook o Apple Calendar para compartir y gestionar eventos.


### 3. vCard
```
BEGIN:VCARD
VERSION:3.0
FN:Juan Pérez
TEL;TYPE=WORK,VOICE:+34 123 456 789
EMAIL:juan.perez@example.com
END:VCARD
```

* Estructura: vCard define contactos mediante campos como FN (nombre completo), TEL (teléfono) y EMAIL (correo electrónico). Cada tarjeta de contacto se encapsula entre BEGIN:VCARD y END:VCARD.
Aplicación asociada: Procesado por aplicaciones de gestión de contactos como Google Contacts, Apple Contacts y Microsoft Outlook.

### 4. KML (Keyhole Markup Language)
```
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Ubicación Ejemplo</name>
    <Point>
      <coordinates>-122.082203,37.422289,0</coordinates>
    </Point>
  </Placemark>
</kml>
```
* Estructura: KML es un lenguaje basado en XML que utiliza etiquetas como <Placemark> y <coordinates> para definir ubicaciones geográficas con coordenadas de longitud, latitud y altitud.
Aplicación asociada: Se utiliza principalmente en aplicaciones de mapas como Google Earth y Google Maps para representar datos geoespaciales.

### 5. RSS (Really Simple Syndication)
```
<?xml version="1.0" encoding="UTF-8" ?>
<rss version="2.0">
  <channel>
    <title>Ejemplo de RSS</title>
    <link>http://www.ejemplo.com</link>
    <description>Este es un ejemplo de canal RSS.</description>
    <item>
      <title>Artículo 1</title>
      <link>http://www.ejemplo.com/articulo1</link>
      <description>Descripción del primer artículo.</description>
    </item>
  </channel>
</rss>
```

* Estructura: RSS es un formato basado en XML que estructura información de contenido web en canales (<channel>) y artículos (<item>), con etiquetas para el título, enlace y descripción.
Aplicación asociada: Los lectores de RSS y agregadores de noticias (como Feedly o Inoreader) procesan los feeds RSS para mostrar actualizaciones de contenido web en tiempo real.
markdown
Copiar código

