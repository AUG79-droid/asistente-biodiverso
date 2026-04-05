# Buscador de dudas sobre biodiversidad

Versión simplificada para GitHub Pages.

## Qué es
Una web estática con:
- lupa
- campo de búsqueda
- botón de buscar
- respuesta clara debajo
- preguntas sugeridas
- enlaces a recursos de Biodiverso

## Cómo subirla a GitHub
1. Crea un repositorio nuevo, por ejemplo: `buscador-dudas-biodiverso`
2. Sube el archivo `index.html`
3. Ve a `Settings > Pages`
4. En `Build and deployment`, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda
6. Espera a que GitHub genere la URL pública

## Cómo usarla en el Hub
Pon un bloque o botón con un texto parecido a:
- Buscador de dudas sobre biodiversidad
- ¿Tienes una duda? Escríbela aquí
- Consulta rápida sobre biodiversidad en Airbus

## Qué hace esta versión
Esta versión no usa una IA real ni backend.
Funciona con una base de preguntas frecuentes ya cargadas en el propio `index.html`.

## Cómo ampliarla
Para añadir nuevas dudas, busca en `index.html` el bloque:
`const knowledgeBase = [...]`

y añade nuevas entradas siguiendo el mismo formato.
