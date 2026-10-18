# Loto de gestos

Un loto rosa dentro de una jaula verde, hecho con partículas (Three.js + bloom).
La cámara detecta tu mano (MediaPipe) y cada gesto lo transforma en otra cosa.

| Gesto | Forma |
|---|---|
| Mano abierta (5 dedos) | Loto (la forma original) |
| Puño | Galaxia |
| 1 dedo | Corazón latiendo |
| 2 dedos | Mariposa aleteando |
| 3 dedos | ADN |
| 4 dedos (pulgar doblado) | Saturno |

Mover la mano gira y desplaza la figura. Con dos manos, separarlas la agranda.
Sin cámara: teclas 1–6, o clic en los botones de arriba. `H` oculta el panel de código.

## Cómo abrirlo en Visual Studio Code

1. Abre la carpeta `loto-gestos`.
2. Instala la extensión **Live Server**.
3. Clic derecho en `index.html` → *Open with Live Server*.
4. Pulsa "Activar cámara" y acepta el permiso.

Necesita internet (carga Three.js y MediaPipe desde un CDN) y un navegador con WebGL (Chrome o Edge).
