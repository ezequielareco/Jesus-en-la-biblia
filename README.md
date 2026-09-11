# Jesús en la Biblia

Catálogo interactivo de todos los títulos, nombres y representaciones tipológicas de Jesucristo a lo largo de la Biblia completa (Génesis–Apocalipsis). El proyecto conecta cada título con su término original en hebreo o griego, su número Strong, el texto bíblico correspondiente y una red de referencias cruzadas entre pasajes relacionados.

**Ver el prototipo en vivo:** _(pegá acá el link de GitHub Pages cuando lo actives)_

## Qué incluye

- **733 entradas** catalogadas a lo largo de todo el canon, Antiguo y Nuevo Testamento.
- **Término original** (hebreo/griego), transliteración y número Strong para cada título.
- **Texto bíblico** en RVR1960 embebido en cada entrada.
- **Referencias cruzadas**: más de 5.000 conexiones entre pasajes, extraídas de las notas marginales de RVR1995 y RVR1960.
- **15 categorías temáticas**: Deidad y naturaleza divina, Realeza y reino, Sacerdocio y mediación, Redención y salvación, Sufrimiento y pasión, Pastoral y cuidado, Sabiduría y enseñanza, Juicio y justicia, Profecía y revelación, Filiación y relación personal, Creación y sustento del universo, Resurrección y vida eterna, Escatología y segunda venida, Humildad y servicio (Kénosis), Nombres compuestos de YHWH.

## Criterios de catalogación

- **Título directo vs. tipológico**: se distingue entre títulos léxicos explícitos del pasaje y lecturas tipológicas o interpretativas (marcadas como [TIPOLOGIA] en las notas). Una lectura tipológica no implica que el título sea menos válido, solo que su conexión con Cristo depende de una interpretación posterior (generalmente del Nuevo Testamento) y no de un término presente en el propio versículo.
- **Rigor léxico**: el término original registrado debe aparecer efectivamente en el versículo citado y dar origen al título en español. Cuando esto no puede verificarse, la entrada se marca [REVISAR] en vez de forzar un dato aproximado.
- **Estilo de título**: se prefieren frases nominales concisas sobre construcciones descriptivas largas tipo "El que...".

## Cómo navegar el prototipo

- **Red (D3.js)**: visualización de fuerza dirigida que muestra las conexiones entre títulos.
- **Índice**: listado completo con buscador de texto.
- **Lectura (lectio)**: modo de lectura secuencial por libro.
- **Nube de palabras**: vista arrastrable de los títulos agrupados.
- El estado de vista y los enlaces promovidos se guardan localmente en el navegador de cada visitante (no se comparten entre usuarios).

## Fuentes

- Texto bíblico: **Reina-Valera 1960** (RVR1960), vía módulo e-Sword.
- Referencias cruzadas: notas marginales de RVR1995 y RVR1960 (e-Sword).
- Léxico hebreo/griego: diccionario **Strong-Plus** (glosa y frecuencia).
- Verificación de Strong del NT: interlinear griego **TAGNT**.

## Estado del proyecto

Dataset en versión v23. Trabajo en curso: normalización de títulos a estilo nominal (en progreso desde Génesis hasta Jeremías), verificación de Strong hebreos del AT contra un interlinear hebreo etiquetado, y revisión de una cola de curación (títulos tipológicos sin conexión curada, verificaciones dudosas, referencias cruzadas ruidosas).

## Autor

Proyecto personal de estudio teológico. Ideado a partir de una instalación mural vista en redes sociales, desarrollado como catálogo digital interconectado con salida dual: prototipo web interactivo y póster imprimible.
