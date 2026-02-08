# GenArt Studio by VilBeer

> *"Donde la lógica binaria se encuentra con la evolución orgánica."*

**GenArt Studio** es una colección de algoritmos de arte generativo que exploran la belleza de las matemáticas, la física y el caos controlado. Desarrollado con tecnologías web modernas, este estudio presenta una serie de experiencias visuales interactivas que simulan fenómenos naturales y abstractos.

## 🌟 Características Principales

- **6 Algoritmos Únicos:** Desde simulaciones gravitatorias hasta crecimiento orgánico vegetal.
- **Interactividad Total:** Cada obra permite al usuario modificar parámetros en tiempo real (gravedad, fricción, densidad, etc.).
- **Estética Premium:** Diseño de interfaz moderno con estilo "Glassmorphism", tipografía cuidada y modo oscuro inmersivo.
- **Base Teórica:** Cada pieza incluye una explicación detallada de los principios matemáticos y físicos que la rigen.
- **Localización Completa:** Todo el contenido está meticulosamente traducido al español.
- **Responsive:** Diseño adaptable que funciona en escritorio y dispositivos móviles.

## 🎨 Las Obras (The Art)

### 1. Falling Circles (Círculos en Caída)

Una simulación de física newtoniana que explora la masa, la gravedad y la memoria visual. Las partículas caen dejando rastros efímeros, creando composiciones verticales que recuerdan a la lluvia o cascadas de pintura.

### 2. Cosmic Orbits (Órbitas Cósmicas)

Un sistema de N-Cuerpos que visualiza la belleza caótica de la mecánica orbital. Las partículas se atraen mutuamente generando patrones espirales complejos y trayectorias impredecibles.

### 3. Flow Fields (Campos de Flujo)

Navegación de partículas a través de "ríos invisibles" generados por Ruido de Perlin. Visualiza cómo el viento o el agua fluyen alrededor de obstáculos invisibles en un campo vectorial.

### 4. Organic Growth (Crecimiento Orgánico)

Simulación biológica de vegetación que busca la luz (fototropismo). Utiliza Cadenas de Markov y funciones sinusoidales para emular el crecimiento de la hierba bajo la influencia del viento.

### 5. Cubisms (Cubismos Urbanos)

Una abstracción geométrica de una ciudad futurista. Flujos de luz ("vehículos") navegan una malla ortogonal estricta. Incluye lógica de tráfico y **fricción energética**: cuando dos flujos se cruzan, aumentan su brillo y grosor, pero reducen su velocidad.

### 6. Water Explosion (Explosión de Agua)

Un estudio sobre la entropía y la tensión superficial. Simula una gota central que explota violentamente y luego, desafiando la expansión, se vuelve a cohesionar por atracción gravitatoria, simulando un ciclo eterno de caos y orden en un entorno cerrado.

---

## 🛠️ Tech Stack

Este proyecto ha sido construido utilizando estándares web modernos y ligeros, sin dependencias pesadas de compilación.

- **Lenguaje:** JavaScript (ES6+)
- **Renderizado:** [p5.js](https://p5js.org/) (v1.9.0 via CDN)
- **Estructura:** HTML5 Semántico
- **Estilos:** CSS3 (Variables, Flexbox, Grid, Backdrop-filter)
- **Tipografía:** Google Fonts (Poppins & Lora)

## 🚀 Instalación y Uso Local

No se requiere instalación de paquetes npm ni configuraciones complejas.

### Prerrequisitos

- Un navegador web moderno (Chrome, Firefox, Safari, Edge).
- Un servidor local ligero (Recomendado para evitar problemas de CORS con módulos, aunque este proyecto usa scripts planos).

### Pasos

1. **Clonar el repositorio:**

    ```bash
    git clone https://github.com/tu-usuario/GenArt.git
    cd GenArt
    ```

2. **Ejecutar:**
    - Opción A (VS Code): Instala la extensión "Live Server", haz clic derecho en `index.html` y selecciona "Open with Live Server".
    - Opción B (Python):

        ```bash
        python -m http.server 8000
        ```

    - Opción C (Node/npx):

        ```bash
        npx serve .
        ```

3. **Explorar:**
    Abre tu navegador en `http://localhost:8000` (o el puerto que corresponda).

## 📂 Estructura del Proyecto

```
GenArt/
├── index.html              # Página principal (Galería y presentación)
├── README.md               # Documentación del proyecto
├── art/                    # Directorio de obras generativas
│   ├── falling_circles.html
│   ├── cosmic_orbits.html
│   ├── flow_fields.html
│   ├── organic_growth.html
│   ├── cubisms.html
│   └── water_explosion.html
└── (assets/css/js)         # Estilos y scripts están contenidos en los HTML para simplicidad de portabilidad
```

## 🌐 Despliegue (Deployment)

Este proyecto está optimizado para **GitHub Pages**.

1. Sube el código a un repositorio de GitHub.
2. Ve a `Settings` > `Pages`.
3. En "Source", selecciona `Deploy from a branch`.
4. Selecciona la rama `main` (o `master`) y la carpeta `/root`.
5. Guarda. En unos minutos tu galería estará online.

---

**Autor:** VilBeer
**Licencia:** MIT
