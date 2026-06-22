# NEON PAC

> 🇪🇸 Español · [🇬🇧 English below](#-english)

Un arcade de laberintos con estética **synthwave/neón**, hecho en un único archivo HTML autocontenido. Cómete los puntos, esquiva a los seis fantasmas y sobrevive a 100 niveles de aventura. Para uno o dos jugadores.

**▶️ Jugar:** **[kico1603.github.io/NeonPac](https://kico1603.github.io/NeonPac/)**

---

## ✨ Características

- **Un solo archivo HTML**, sin instalación ni dependencias que descargar. Se abre en cualquier navegador moderno.
- **Modo 1 jugador** contra una CPU con 6 niveles de dificultad (de PASEO a PESADILLA).
- **Modo Aventura**: 100 niveles repartidos en 10 mundos, con dificultad creciente (más fantasmas, mapas más grandes, menos aberturas) y progreso guardado en tu dispositivo.
- **Multijugador online** para 2 personas mediante código de sala (usa Firebase como relay, funciona entre redes distintas).
- **11 modos de juego** en la aventura (ver más abajo).
- **9 power-ups** distintos: misil, zapatillas, onda, bomba, imán, freeze, vida extra, teletransporte y glitch.
- **8 idiomas** con detección automática del idioma del sistema: español, inglés, francés, portugués, alemán, chino, hindi y árabe (con soporte RTL).
- **Compatible con mando** (Gamepad API) además de teclado y táctil, con controles totalmente reconfigurables.
- **Manual integrado**, menú de opciones (volúmenes, idioma, controles) y un fondo animado interactivo.

---

## 🎮 Cómo jugar

| Acción | Teclado | Mando | Táctil |
|--------|---------|-------|--------|
| Moverse | Flechas o `W A S D` | Stick / cruceta | Deslizar el dedo o D-pad en pantalla |
| Usar power-up | `Espacio` | Botón A (configurable) | Botón de acción |

- Cómete todas las **bolas** del laberinto y evita a los fantasmas.
- Las **bolas de poder** (las grandes) te permiten comerte a los fantasmas durante unos segundos.
- Recoge **power-ups** para conseguir ventajas. Solo puedes llevar uno a la vez.
- En el modo aventura, cada nivel tiene su propio **objetivo** y **efecto especial**, que se explican antes de empezar.

Todos los controles se pueden personalizar en **Opciones → Controles**.

---

## 🗺️ Modos de la Aventura

La aventura tiene 100 niveles (10 mundos de 10, donde el nivel 10 de cada mundo es un **boss**). Estos son los 11 modos que van rotando:

- **Clásico** — Cómete todas las bolas.
- **Caza** — Elimina a todos los fantasmas con las bolas de poder. No reaparecen.
- **Entrenamiento** — Aprende a usar un power-up nuevo usándolo varias veces.
- **Boss** — Duelo contra el jefe del mundo (cada uno con su sprite): consigue más puntos que él.
- **Invisibles** — Los fantasmas no se ven.
- **Apagón** — Solo ves la zona alrededor de tu personaje.
- **Contrarreloj** — Cómete todo antes de que el tiempo llegue a cero. Cada bola da medio segundo.
- **Muros móviles** — Hay puertas que se abren y se cierran solas.
- **Portales** — Teletransportadores que cambian de destino cada 15 segundos.
- **Horda** — Sobrevive mientras aparece un fantasma nuevo cada 15 segundos.
- **Eres el fantasma** — Inversión de roles: controlas un fantasma y cazas a los pacs de la CPU.

---

## 🤖 Hecho con IA

Este juego ha sido desarrollado por **Francisco José Ponce** con la ayuda de inteligencia artificial (asistente de IA de Anthropic, modelo Claude). El proceso fue **iterativo**: yo aportaba las ideas, el diseño de los modos, los ajustes de jugabilidad y las decisiones, y la IA ayudaba a implementarlas y refinarlas en código a lo largo de muchas iteraciones de prueba y mejora.

Lo comparto de forma transparente porque creo que es interesante mostrar lo que se puede construir con este tipo de colaboración.

---

## 🛠️ Tecnología

- HTML5, CSS y JavaScript puro (sin frameworks ni librerías de terceros, salvo Firebase para el multijugador).
- Renderizado con Canvas 2D.
- **Firebase Realtime Database** como relay para el modo online.

> **Nota sobre el multijugador:** usa el plan gratuito de Firebase, que admite unas 100 conexiones simultáneas en total (≈50 parejas a la vez a nivel global). Suficiente para uso normal; si alguna vez está lleno, el juego avisa.

---

## 💛 Apoyar al proyecto

Si te gusta el juego y quieres ayudar a ampliarlo (más modos, más power-ups, mejores servidores), puedes apoyar al creador en Ko-fi:

**☕ [ko-fi.com/neonpac](https://ko-fi.com/neonpac)**

---

## 📄 Licencia

Este proyecto está bajo la licencia **GNU Affero General Public License v3.0 (AGPL-3.0)**. Eres libre de usar, estudiar, modificar y compartir el código, pero cualquier versión derivada —incluso si solo se ofrece a través de una web— debe publicar su código fuente bajo la misma licencia. Consulta el archivo [`LICENSE`](LICENSE) para los detalles.

---
---

## 🇬🇧 English

A maze arcade game with a **synthwave/neon** aesthetic, built as a single self-contained HTML file. Eat the dots, dodge the six ghosts, and survive 100 adventure levels. For one or two players.

**▶️ Play:** **[kico1603.github.io/NeonPac](https://kico1603.github.io/NeonPac/)**

### ✨ Features

- **Single HTML file**, no installation or downloads. Opens in any modern browser.
- **1-player mode** against a CPU with 6 difficulty levels.
- **Adventure mode**: 100 levels across 10 worlds, with rising difficulty and progress saved on your device.
- **Online multiplayer** for 2 players via room code (uses Firebase as a relay; works across different networks).
- **11 game modes** in the adventure.
- **9 power-ups**: missile, sneakers, wave, bomb, magnet, freeze, extra life, teleport and glitch.
- **8 languages** with automatic system-language detection: Spanish, English, French, Portuguese, German, Chinese, Hindi and Arabic (with RTL support).
- **Gamepad support** (Gamepad API) plus keyboard and touch, with fully remappable controls.
- **Built-in manual**, options menu (volumes, language, controls) and an animated interactive background.

### 🎮 How to play

| Action | Keyboard | Gamepad | Touch |
|--------|----------|---------|-------|
| Move | Arrows or `W A S D` | Stick / D-pad | Swipe or on-screen D-pad |
| Use power-up | `Space` | A button (configurable) | Action button |

- Eat all the **dots** in the maze and avoid the ghosts.
- **Power dots** (the big ones) let you eat the ghosts for a few seconds.
- Pick up **power-ups** for an edge. You can only carry one at a time.
- In adventure mode, each level has its own **goal** and **special effect**, explained before you start.

All controls can be customized in **Options → Controls**.

### 🗺️ Adventure modes

100 levels (10 worlds of 10, where level 10 of each world is a **boss**). The 11 rotating modes: Classic, Hunt, Training, Boss, Invisible, Blackout, Time Trial, Moving Walls, Portals, Horde, and Be the Ghost.

### 🤖 Made with AI

This game was developed by **Francisco José Ponce** with the help of artificial intelligence (Anthropic's AI assistant, Claude model). The process was **iterative**: I provided the ideas, mode design, gameplay tuning and decisions, and the AI helped implement and refine them in code across many rounds of testing and improvement.

I'm sharing this openly because I think it's interesting to show what can be built through this kind of collaboration.

### 🛠️ Tech

- Pure HTML5, CSS and JavaScript (no frameworks or third-party libraries, except Firebase for multiplayer).
- Canvas 2D rendering.
- **Firebase Realtime Database** as the relay for online mode.

> **Multiplayer note:** it uses Firebase's free tier, which allows about 100 simultaneous connections total (~50 pairs at once globally). Plenty for normal use; if it's ever full, the game lets you know.

### 💛 Support the project

If you enjoy the game and want to help expand it (more modes, more power-ups, better servers), you can support the creator on Ko-fi:

**☕ [ko-fi.com/neonpac](https://ko-fi.com/neonpac)**

### 📄 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. You are free to use, study, modify and share the code, but any derivative version —even if only offered through a website— must publish its source code under the same license. See the [`LICENSE`](LICENSE) file for details.
