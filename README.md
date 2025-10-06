# MiPrimerEscenarioUnity
Escenario Creado para la Materia de Desarrollo de Videojuegos
# Proyecto Unity: Movimiento de Cámara con W/A/S/D

Este proyecto es un prototipo en Unity que permite mover la cámara en la escena usando las teclas **W, A, S, D** y rotar la vista con el **ratón**, simulando un control tipo FPS.

---

## Contenido del Repositorio

- `Assets/` → Carpeta principal con todos los assets, scripts y escenas.  
- `Scenes/` → Contiene la escena principal (`MainScene.unity`).  
- `Scripts/` → Script `CameraMovement.cs` que controla la cámara.

---

## Requisitos

- Unity 2021.3 LTS o superior.  
- Sistema operativo: Windows, macOS o Linux compatible con Unity.  

---

## Cómo ejecutar

1. **Abrir el proyecto en Unity Hub**:
   - Selecciona **Add** y navega hasta la carpeta del repositorio.
   - Abre el proyecto con la versión de Unity indicada.

2. **Abrir la escena principal**:
   - En el panel `Project`, ve a `Assets/Scenes/`.
   - Haz doble clic en `MainScene.unity`.

3. **Iniciar el modo de juego**:
   - Haz clic en el botón **Play** en la parte superior del editor.

---

## Controles de navegación

- **W** → Avanzar  
- **S** → Retroceder  
- **A** → Mover a la izquierda  
- **D** → Mover a la derecha  
- **Ratón** → Rotar la cámara (mirar alrededor)

> Nota: Asegúrate de que la cámara sea hija del objeto `Player` y que el script `CameraMovement.cs` esté asignado al Player para que los controles funcionen correctamente.

---

## Créditos

- Desarrollo: Pablo Vargas  
- Unity: [https://unity.com](https://unity.com)

---

## Posibles mejoras

- Añadir salto con `Space`.  
- Agregar colisiones con objetos de la escena.  
- Implementar límites de movimiento dentro de la escena.
