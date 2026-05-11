**Contexto y Rol**
Actúa como un diseñador y desarrollador senior de videojuegos arcade con experiencia en mecánicas innovadoras, diseño para móviles y creación de experiencias altamente adictivas. Tu objetivo es crear un juego original que capture la esencia de los arcades clásicos, pero con una mecánica novedosa nunca antes vista.

---

**Consulta / Tarea**
Diseña y desarrolla un juego arcade original para móviles llamado **“Pulse Grid”**.

El jugador controla una **onda de energía** que se desplaza automáticamente por una cuadrícula (grid) dinámica. El objetivo es sobrevivir el mayor tiempo posible mientras activa nodos, evita colapsos del sistema y gestiona el ritmo del juego mediante pulsaciones táctiles.

---

**Concepto de Juego (Mecánica Única)**

* El jugador no controla libremente un personaje, sino el **ritmo y dirección de una onda energética**.

* El movimiento ocurre en una **rejilla (grid)** donde la onda avanza automáticamente.

* El jugador puede:

  * Cambiar dirección en intersecciones (toque).
  * Emitir un “pulso” que activa nodos cercanos.

* Cada nodo activado genera puntos, pero también **aumenta la inestabilidad del sistema**.

---

**Sistema de Riesgo/Recompensa (Core Loop)**

* Cuantos más nodos actives seguidos:

  * Mayor puntuación.
  * Mayor velocidad del juego.
  * Mayor probabilidad de colapso del grid.

* Si el sistema colapsa:

  * Se generan zonas bloqueadas.
  * Aparecen “fallos” que persiguen la onda.

---

**Enemigos / Amenazas**

* “Glitches”: entidades que nacen en zonas inestables y siguen la onda.
* “Cortes de energía”: partes del mapa que desaparecen temporalmente.
* “Nodos corruptos”: parecen seguros pero penalizan al jugador.

---

**Sistema de Puntuación**

* Puntos por:

  * Activar nodos.
  * Encadenar combos (sin fallos).
  * Mantener la velocidad alta.

* Multiplicador dinámico basado en precisión y ritmo.

---

**Progresión y Niveles**

* Sistema de niveles infinito (endless runner arcade).

* Aumento progresivo de:

  * Velocidad.
  * Densidad de nodos.
  * Frecuencia de glitches.

* Fases especiales cada ciertos niveles (ej: modo caos, gravedad invertida).

---

**Controles (Mobile First)**

* Toque simple para cambiar dirección.
* Pulsación larga para emitir pulso energético.
* Gestos simples, sin botones complejos.

---

**Experiencia Visual (Arcade 80s + Futurista)**

* Estética neon minimalista:

  * Fondo oscuro
  * Líneas brillantes
  * Efectos de glitch

* Animaciones fluidas tipo “flujo eléctrico”.

---

**Sonido y Feedback**

* Música dinámica que se acelera con el ritmo del juego.
* Sonidos clave:

  * Activación de nodos (feedback positivo).
  * Alerta de colapso.
  * Presencia de enemigos.
  * Sonido rítmico sincronizado con el movimiento.

---

**Requisitos Técnicos**

* Optimizado para móviles (Android/iOS).
* Alto rendimiento (mínimo consumo de batería).
* Código modular y escalable.
* Posible implementación en Unity, Godot o Web (Canvas/WebGL).

---

**Criterios de Calidad**

* Mecánica original clara y fácil de aprender, difícil de dominar.
* Sensación de “flow” continuo.
* Feedback audiovisual satisfactorio.
* Alto potencial adictivo y rejugabilidad.

---

**Cómo debe ser la respuesta**

* Proporciona:

  * Arquitectura del juego.
  * Explicación clara de la mecánica central.
  * Pseudocódigo del sistema de movimiento y generación de grid.
  * Diseño de niveles/progresión.
  * Ideas de expansión futura (modos, skins, power-ups).

---

**Objetivo Final**
Crear un juego arcade moderno con alma retro que genere una experiencia hipnótica, basada en ritmo, precisión y toma de decisiones constante.
