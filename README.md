# TerrainExercise – Escena de terreno en Unity

Proyecto de Unity que contiene una escena de paisaje natural creada con las herramientas de terreno (Terrain Tools) del editor.

**Autor:** Gregory Jimenez
**Materia:** Desarrollo De Videojuegos
## Descripción de la escena

La escena `SampleScene` muestra un paisaje formado por varios terrenos contiguos e incluye:

- **Montañas** con cumbres nevadas, modeladas con los pinceles de elevación del terreno.
- **Un río y un lago** de agua color turquesa que atraviesan el valle.
- **Orillas de arena** alrededor del agua, pintadas con capas de textura (Terrain Layers).
- **Praderas y bosques**, con árboles colocados con la herramienta Paint Trees.
- **Un castillo/pueblo amurallado** con torres y edificaciones en la pradera (objetos `Pueblo`).

## Requisitos

- Unity Hub
- Unity 6 – versión del editor **6000.4.4f1** (se recomienda usar la misma versión para evitar errores de importación)
- Windows con DirectX 11

## Cómo ejecutar el proyecto

1. Abrir **Unity Hub** e iniciar sesión.
2. Ir a **Projects** y abrir el proyecto **TerrainExercise**:
   - Si se comparte desde la nube: **Add > Add from repository** y seleccionar `TerrainExercise`.
   - Si se descarga como carpeta: **Add > Add project from disk** y seleccionar la carpeta del proyecto.
3. Si Unity Hub indica que falta la versión del editor, instalar la **6000.4.4f1**.
4. Abrir el proyecto. La primera vez puede tardar varios minutos mientras Unity importa los assets.
5. En la ventana **Project**, ir a `Assets/Scenes` y hacer doble clic en **SampleScene**.
6. La escena se visualiza en la pestaña **Scene**. Para verla desde la cámara principal, presionar el botón **Play** (▶).

## Cómo navegar por la escena

La escena se recorre desde la pestaña **Scene** del editor con los siguientes controles:

| Acción | Control |
|---|---|
| Vuelo libre (recomendado) | Mantener **clic derecho** + **W A S D** |
| Subir / bajar | Mantener **clic derecho** + **E** / **Q** |
| Moverse más rápido | Mantener **Shift** mientras se vuela |
| Mirar alrededor | Mantener **clic derecho** y mover el ratón |
| Orbitar | **Alt** + **clic izquierdo** y arrastrar |
| Desplazar la vista | **Clic central** (rueda) y arrastrar |
| Acercar / alejar | **Rueda del ratón** |
| Enfocar un objeto | Seleccionarlo en **Hierarchy** y presionar **F** |

### Puntos de interés

- **Castillo / pueblo:** seleccionar `Pueblo` en la ventana Hierarchy y presionar **F** para ir directamente a él.
- **Río y lago:** seleccionar `water` en Hierarchy y presionar **F**.
- **Montañas nevadas:** se encuentran al fondo del valle, detrás del lago.

## Estructura del proyecto

- `Assets/Scenes/SampleScene` – escena principal.
- `Assets/TerrainSampleAssets` – texturas, árboles y recursos del terreno.
- `Assets/Houidisoft technology/Simple water` y `Assets/Procedural Water Shader` – recursos para el agua.
- `Assets/Advance Studios` – modelos del castillo/pueblo.

## Notas

- En la consola puede aparecer una advertencia sobre el shader de los árboles (`Nature/Soft Occlusion`). No afecta la ejecución de la escena.

URL VIDEO: https://www.youtube.com/watch?v=72oZ99Kw68A