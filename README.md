<div align="center">

# RizoLab

**Diseña y genera G-code para impresión 3D en modo jarrón — sin slicer.**

Un generador paramétrico de trayectorias en espiral continua, para crear jarrones, lámparas, macetas y piezas decorativas de pared fina. Todo funciona en el navegador: nada se instala, nada se sube a ningún servidor.

[Probar RizoLab](#) · [Cómo funciona](#cómo-funciona) · [Galería](#galería) · [Apoya el proyecto](#apoya-el-proyecto)

</div>

---

## Qué es

RizoLab es una herramienta que crea **G-code directamente por contorno**, sin pasar por un slicer tradicional. Diseñas la forma de tu pieza —su silueta, su textura, sus patrones— y descargas el archivo listo para imprimir en tu impresora FDM.

Está pensado para piezas de **pared fina impresas en espiral (vase mode)**: la boquilla sube en un solo hilo continuo, sin capas separadas ni relleno. Es la técnica ideal para jarrones y luminarias, donde la luz atraviesa la pared y la textura cobra vida.

## Características

- **Editor de silueta** con puntos arrastrables, dibujo a mano alzada y presets (cilindro, jarrón, cono, diábolo).
- **Cinco modos de patrón**: bandas aéreas, puntadas, columnas, olas y superficie.
- **Biblioteca de patrones de superficie** organizados por familias: ondas, geométricos, relieve, orgánicos.
- **Superposición de patrones** y **gradiente por altura** (base lisa, corona intrincada).
- **Apilado por pisos** configurable: repite una curva varias capas y luego rota, para efectos escalonados tipo cerámica.
- **Sección transversal** ajustable: círculo, cuadrado, polígono, estrella, superfórmula, con torsión.
- **Niveles por altura**: distintos patrones a distintas alturas de la misma pieza.
- **Nervios de refuerzo**, máscara por zonas e inspección de voladizos.
- **Perfiles de impresora**: presets para modelos populares (Ender, Prusa, Bambu, Artillery, Voron y más) o medidas personalizadas.
- **Selector de boquilla** (0.2 a 1.0 mm) que ajusta ancho de línea y altura de capa automáticamente.
- **Simulador de construcción** capa a capa y estadísticas de filamento y tiempo.
- **Modo claro / oscuro**.

Todo en un **único archivo HTML**, sin dependencias que instalar más allá de una librería de render 3D que se carga sola.

## Cómo funciona

1. **Elige la silueta** en la sección Perfil: un preset o dibuja la tuya.
2. **Aplica un patrón** desde la barra de modos y la sección Patrón.
3. **Refina los detalles**: adherencia, niveles por altura, nervios, boquilla.
4. **Exporta el G-code** o guarda tu perfil en JSON para seguir después.

Consejo: imprime en vase mode, con pared fina, velocidad baja y buena ventilación.

## Uso

No requiere instalación. Puedes:

- **Usarlo online**: abre la versión publicada (enlace arriba).
- **Usarlo localmente**: descarga `rizolab.html` y ábrelo con cualquier navegador moderno.

## Galería

*(Añade aquí fotos de tus impresiones reales — son lo que más convence.)*

## Apoya el proyecto

RizoLab es libre y gratuito, sin anuncios ni límites. Si te resulta útil y quieres apoyar su desarrollo, puedes hacer un aporte voluntario:

☕ **[Ko-fi](https://ko-fi.com/darwinenriquez)**

Cada aporte, por pequeño que sea, ayuda a mantener y mejorar la herramienta.

## Contribuir

Las ideas, reportes de errores y mejoras son bienvenidos. Abre un *issue* para comentar un problema o proponer una función, o envía un *pull request* si quieres aportar código.

## Licencia

Este proyecto está bajo licencia **GPL-3.0**. Puedes usarlo, modificarlo y distribuirlo libremente, siempre que los trabajos derivados se mantengan también bajo la misma licencia abierta. Ver el archivo [LICENSE](LICENSE) para el texto completo.

## Autor

Creado por **Darwin** · RizoLab 3D · Conocoto, Quito, Ecuador.

---

<div align="center">
<sub>Hecho con paciencia, iteración y muchas impresiones de prueba.</sub>
</div>
