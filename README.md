# MindAR & A-Frame Tutorials - UOC

Este repositorio contiene los ejemplos de código y recursos (assets 3D, texturas e imágenes) utilizados en los tutoriales de **A-Frame** y **MindAR (WebAR)**.

La documentación completa y las guías paso a paso están disponibles en la [Wiki del proyecto](https://github.com/hannibalov/mindar/wiki).

## Estructura del repositorio

```
.
├── aframe/                # Ejemplos HTML y recursos del tutorial de A-Frame
│   ├── 1_environment.html # 1. Escena básica con entorno
│   ├── 2_box.html         # Escena con cubo interactivo
│   ├── 3_assets.html      # 2. Incorporar recursos y texturas
│   ├── 4_animation.html   # 3. Animar objetos
│   ├── 5_cursor.html      # 4. Interacción con cursor (gaze)
│   ├── 7_link.html        # 6. Portales y navegación entre escenas
│   ├── 8_iframe.html      # 7. Integración de escenas con iframe
│   ├── monkey03.html      # 5. Importar objetos 3D externos (.obj, .mtl)
│   ├── monkey03.blend     # Archivo fuente en Blender
│   ├── monkey03.obj       # Geometría 3D de Suzanne (mono de Blender)
│   ├── monkey03.mtl       # Definición de materiales
│   ├── granit.jpg         # Textura de granito
│   ├── oxid.png           # Textura de óxido
│   └── toMonkey.png       # Imagen para el portal de enlace
│
└── assets/                # Recursos compartidos (texturas y modelos 3D)
    ├── granit.jpg
    ├── monkey03.blend
    ├── monkey03.mtl
    ├── monkey03.obj
    ├── oxid.png
    └── toMonkey.png
```

## Cómo ejecutar los ejemplos localmente

1. Abre esta carpeta en **Visual Studio Code**.
2. Instala la extensión **Live Server** (por Ritwick Dey).
3. Haz clic derecho sobre cualquiera de los archivos `.html` dentro de `aframe/` y selecciona **"Open with Live Server"**.
4. Tu navegador web se abrirá automáticamente en `http://127.0.0.1:5500/aframe/...` mostrando la escena en 3D/VR.

## Tutoriales y Documentación

Para seguir las guías paso a paso en español, catalán e inglés, visita la [Wiki](https://github.com/hannibalov/mindar/wiki):
- **Tutorial 1: A-Frame** (Entorno, Escena, Assets, Animación, Interacción, Entidades, Links, Iframe, Publicación).
- **Tutorial 2: MindAR** (Rastreo de Imágenes, Rastreo Facial, Interactividad y Animación).
- **Artículos Teóricos** sobre el continuo de la realidad mixta y tecnologías inmersivas.
