<div align="center">

  <img src="https://vercel.app" alt="NZP-Mobile Banner" width="100%"/>

  <h3>Adaptación WebGL Multiplataforma con Controles Táctiles Nativos en Pantalla</h3>

  <!-- ETIQUETAS PRINCIPALES DE PLATAFORMAS -->
  <p>
    <img src="https://shields.io" alt="Web"/>
    <img src="https://shields.io" alt="All"/>
    <img src="https://shields.io" alt="Multiplataforma"/>
  </p>

  <!-- ETIQUETAS DE SISTEMAS OPERATIVOS Y DISPOSITIVOS -->
  <p>
    <img src="https://shields.io" alt="Android"/>
    <img src="https://shields.io" alt="iOS"/>
    <img src="https://shields.io" alt="iPad"/>
    <img src="https://shields.io" alt="Tablet"/>
    <img src="https://shields.io" alt="PC"/>
  </p>

  <!-- ETIQUETAS TÉCNICAS -->
  <p>
    <img src="https://shields.io" alt="Engine"/>
    <img src="https://shields.io" alt="Controls"/>
    <img src="https://shields.io" alt="Zero Install"/>
    <img src="https://shields.io" alt="Status"/>
  </p>

</div>

---

## 📖 Índice de Contenidos

1. [¿Qué es NZP-Mobile?](#-qué-es-nzp-mobile)
2. [Características Principales](#-características-principales)
3. [Compatibilidad Multiplataforma Detallada](#-compatibilidad-multiplataforma-detallada)
4. [Tutorial Paso a Paso: Cómo Activar la Cámara y Jugar](#-tutorial-paso-a-paso-cómo-activar-la-cámara-y-jugar)
5. [Guía Completa de Controles en Pantalla](#-guía-completa-de-controles-en-pantalla)
6. [Mecánicas de Juego y Sistema de Supervivencia](#-mecánicas-de-juego-y-sistema-de-supervivencia)
7. [Mapas y Escenarios](#-mapas-y-escenarios)
8. [Armamento, Caja Misteriosa y Mejoras](#-armamento-caja-misteriosa-y-mejoras)
9. [Máquinas de Ventajas (Perks)](#-máquinas-de-ventajas-perks)
10. [Estrategias Avanzadas para Rondas Altas](#-estrategias-avanzadas-para-rondas-altas)
11. [Despliegue Local y Desarrollo](#-despliegue-local-y-desarrollo)
12. [Preguntas Frecuentes (FAQ)](#-preguntas-frecuentes-faq)
13. [Créditos y Agradecimientos](#-créditos-y-agradecimientos)

---

## 🎮 ¿Qué es NZP-Mobile?

**NZP-Mobile** es un *fork* / adaptación enfocada en dispositivos móviles del clásico modo de supervivencia por oleadas ejecutado mediante tecnología **WebGL y WebAssembly (WASM)**. El objetivo principal de este proyecto es eliminar la barrera del teclado y el ratón físicos, permitiendo que cualquier persona pueda abrir su navegador web y disfrutar de una partida fluida directamente desde la pantalla táctil de su teléfono o tablet.

A diferencia de otras versiones web diseñadas exclusivamente para computadoras de escritorio, **NZP-Mobile** integra una capa personalizada en JavaScript y CSS (`touch.js`) que dibuja sobre el lienzo del juego un sistema completo de **doble joystick analógico virtual** y **botones de acción ergonómicos**, traduciendo cada toque en señales nativas que el motor gráfico entiende en tiempo real sin pérdida de rendimiento.

---

## ✨ Características Principales

* **100% Basado en Web:** No requiere descargar archivos APK, ni hacer *jailbreak*, ni instalar emuladores pesados. Todo corre dentro de una pestaña del navegador.
* **Doble Joystick Virtual (`touch.js`):** Control independiente para desplazamiento omnidireccional en la mano izquierda y rotación fluida de cámara en 360 grados en la mano derecha.
* **Botones de Acción Dedicados:** Acceso rápido e intuitivo para disparar, apuntar con precisión, saltar, recargar e interactuar con el entorno.
* **Arquitectura Ultra Ligera:** Todo el paquete del juego ocupa menos de 100 MB, lo que permite tiempos de carga muy rápidos incluso con datos móviles o conexiones modestas.
* **Soporte Híbrido (Táctil + Periféricos):** Si juegas en una laptop con pantalla táctil, en un iPad con teclado o en una PC convencional, puedes alternar libremente entre los controles en pantalla y tu teclado/ratón.
* **Fidelidad de Jugabilidad Clásica:** Conserva el sistema clásico de rondas infinitas, economía por puntos, reparación de barricadas, compra de armas en paredes, cajas aleatorias y máquinas de bebidas potenciadoras.

---

## 📱 Compatibilidad Multiplataforma Detallada

**NZP-Mobile** está diseñado bajo estándares abiertos de HTML5 y WebGL, logrando compatibilidad universal en prácticamente cualquier equipo moderno:

| Plataforma | Dispositivos Soportados | Navegadores Recomendados | Experiencia de Control |
| :--- | :--- | :--- | :--- |
| **Android** | Teléfonos de gama baja, media y alta | Google Chrome, Brave, Microsoft Edge, Opera | Controles táctiles Dual Joystick + Pantalla completa |
| **iOS** | iPhone (todas las generaciones modernas) | Safari, Google Chrome | Controles táctiles Dual Joystick + Toque directo |
| **iPadOS** | iPad, iPad Air, iPad Mini, iPad Pro | Safari, Google Chrome | Controles táctiles optimizados para pantalla amplia |
| **Tablets** | Tablets Android, Windows Surface | Chrome, Edge, Samsung Internet | Controles táctiles + Soporte opcional de teclado |
| **PC / Escritorio** | Windows 10/11, Linux, macOS, ChromeOS | Chrome, Firefox, Edge, Brave | Teclado (`WASD`) + Ratón o Pantalla Táctil |

---

## 🕹️ Tutorial Paso a Paso: Cómo Activar la Cámara y Jugar

Los navegadores móviles modernos (como Chrome en Android o Safari en iOS) cuentan con protecciones de seguridad que bloquean el movimiento continuo de cámara hasta que el usuario interactúa activamente con la página y activa el modo inmersivo.

Sigue exactamente estos pasos al entrar al juego para que el joystick derecho funcione a la perfección:

1. **Abre el enlace del juego:** Espera unos segundos a que terminen de cargarse los recursos WebAssembly en la barra de progreso.
2. **Inicia el motor:** Toca el botón o texto que dice **"Click To Begin!"** en el centro de la pantalla.
3. **Configura tu partida:** Navega por el menú principal y selecciona **Solo** para iniciar una partida individual en el mapa que prefieras.
4. **Activa el modo pantalla completa (Paso Clave):** Una vez que aparezcas dentro del mapa, **juega un par de segundos presionando los botones en pantalla** (toca **FIRE**, **JUMP** o toca directamente sobre el centro de la pantalla del juego). Esta interacción le indica al navegador que debe activar el bloqueo de puntero (*Pointer Lock*) y la pantalla completa.
5. **Usa el Joystick Derecho o el Táctil:** En cuanto el navegador entre en modo inmersivo, el **Joystick Derecho** responderá de inmediato para mover la cámara hacia arriba, abajo, izquierda y derecha. Adicionalmente, también puedes deslizar el dedo sobre la pantalla para ajustar la mira de forma táctil.

> **Consejo:** Se recomienda jugar con el teléfono en **posición horizontal (paisaje)** para tener una visión panorámica del mapa y mayor comodidad en ambos pulgares.

---

## 🎛️ Guía Completa de Controles en Pantalla

La interfaz táctil está distribuida estratégicamente para evitar que tus dedos tapen el centro de la mira:

| Control en Pantalla | Ubicación | Función en el Juego | Equivalente PC |
| :--- | :--- | :--- | :--- |
| **Joystick Izquierdo** | Esquina inferior izquierda | Mueve al personaje hacia adelante, atrás y los lados | Teclas `W`, `A`, `S`, `D` |
| **Joystick Derecho** | Esquina inferior derecha | Gira la cámara en 360° y permite apuntar a los enemigos | Movimiento del Ratón |
| **FIRE (Rojo)** | Derecha (botón grande) | Dispara el arma equipada o realiza ataque cuerpo a cuerpo | Clic Izquierdo |
| **ADS** | Encima de FIRE | Activa la mira de hierro / precisión del arma | Clic Derecho |
| **JUMP** | Zona media-derecha | Permite saltar obstáculos, barandillas y escalones | Barra Espaciadora |
| **USE (E) (Verde)** | Esquina media-derecha | Comprar armas de pared, abrir puertas, activar electricidad, usar la caja y reparar ventanas | Tecla `E` / `F` |
| **R** | Izquierda de FIRE | Recarga el cargador del arma actual | Tecla `R` |

---

## ⚙️ Mecánicas de Juego y Sistema de Supervivencia

El núcleo del juego se basa en resistir oleadas interminables de enemigos cuya velocidad, resistencia y agresividad aumentan progresivamente con cada ronda:

* **Sistema de Puntos (Economía):** Cada acción ofensiva o defensiva otorga puntos. Impactar disparos suma pequeños montos por bala, eliminar enemigos otorga una bonificación mayor (especialmente mediante disparos a la cabeza o ataques cuerpo a cuerpo) y reconstruir ventanas rotas genera ingresos constantes al inicio de cada ronda.
* **Progresión de Rondas:** Las primeras oleadas son lentas y permiten acumular capital. A partir de rondas intermedias, los enemigos comienzan a correr y aparecen en mayor número desde múltiples puntos de entrada simultáneos.
* **Gestión de Salud:** El personaje cuenta con regeneración automática de salud tras evitar recibir daño durante unos segundos. Si recibes varios golpes seguidos sin cobertura, la pantalla se teñirá de rojo indicando peligro crítico.
