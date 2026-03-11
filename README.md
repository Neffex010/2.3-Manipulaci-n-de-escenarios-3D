# 🎮 Three.js Interactive Demos

Visualización y exploración de entornos tridimensionales mediante diferentes sistemas de control y navegación.

[![Three.js](https://img.shields.io/badge/Three.js-Black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

Este proyecto es una galería interactiva diseñada para experimentar con las capacidades de **Three.js**. Desde la generación de terrenos procedurales hasta controles de cámara avanzados, esta aplicación sirve como un panel de control para diversas implementaciones de gráficos 3D en la web.

---

## 🧩 Demos Incluidas

| Demo | Descripción | Controles Clave |
| :--- | :--- | :--- |
| **🧊 Minecraft** | Generación de terreno tipo voxel con ruido procedural y texturas optimizadas. | `WASD` + `Mouse` |
| **🗺️ Map Controls** | Navegación aérea optimizada para visualización de mapas o layouts arquitectónicos. | `Click Izquierdo` (Paneo) / `Zoom` |
| **🪐 Orbit Controls** | Cámara orbital ideal para inspeccionar objetos específicos desde cualquier ángulo. | `Rotación` / `Dolly` |
| **🎮 Pointer Lock** | Experiencia de movimiento en primera persona (FPS) con bloqueo de puntero. | `WASD` + `Space` (Salto) |

---

## 🚀 Tecnologías y Herramientas

* **Core:** [Three.js](https://threejs.org/) (ES Modules)
* **Frontend:** HTML5, CSS3, [Bootstrap 5](https://getbootstrap.com/)
* **Componentes:** [UIverse](https://uiverse.io/) para estilos de botones y tarjetas.
* **Assets:** Texturas de atlas para el terreno voxel y módulos de control locales.

---

## 📂 Estructura del Repositorio

```bash
ThreeJS-Demos/
├── index.html          # Dashboard principal
├── minecraft.html      # Demo de terreno voxel
├── map.html            # Demo de controles de mapa
├── orbit.html          # Demo de controles orbitales
├── pointerlock.html    # Demo de controles FPS
├── css/
│   └── styles.css      # Estilos personalizados
└── assets/             # Recursos locales (Three.js libs & textures)
    ├── build/
    ├── jsm/
    └── textures/

## 🔗 Referencias

Este proyecto utiliza implementaciones basadas en los ejemplos oficiales de la documentación de Three.js:

* [WebGL Geometry Minecraft](https://threejs.org/examples/#webgl_geometry_minecraft)
* [Controls Map](https://threejs.org/examples/#misc_controls_map)
* [Controls Orbit](https://threejs.org/examples/#misc_controls_orbit)
* [Controls PointerLock](https://threejs.org/examples/#misc_controls_pointerlock)

---

## 👨‍💻 Autor

**Luis Enrique Cabrera García**

* 🎓 Estudiante de **Ingeniería en Tecnologías de la Información y Comunicaciones (ITICS)**
* 🏛️ **Instituto Tecnológico de Pachuca**
* 💼 Áreas de interés: Desarrollo Web, Inteligencia Artificial y Sistemas Expertos.

---

### 📝 Roadmap

* [ ] Implementar soporte para dispositivos móviles (Touch controls).
* [ ] Agregar shaders personalizados para el agua en la demo de Minecraft.
* [ ] Integrar un selector de texturas en tiempo real mediante dat.GUI.
