# 🏎️ NEO F1 GP - FORMULA HYPER DRIFT ARCADE 🏁

**NEO F1 GP** es un videojuego de carreras arcade completo, pulido y 100% original que fusiona la adrenalina de los monoplazas de **Fórmula 1** (alerones gigantes con DRS, halo de protección, pontones aerodinámicos, aleta de tiburón, triángulos de suspensión expuestos, neumáticos slick ultra-anchos y luz de lluvia trasera) con la diversión arcade de objetos, derrapes con chispas de mini-turbo y circuitos temáticos espectaculares.

Desarrollado en un **único archivo autocontenido** (`index.html`) con **Three.js** y sintetizadores de sonido en tiempo real con **Web Audio API**. No requiere servidor, descargas adicionales ni pasos de compilación: solo haz doble clic en `index.html` para jugar en cualquier navegador moderno.

---

## 🎮 Controles de Conducción (Solo Teclado)

| Tecla | Acción |
| :--- | :--- |
| **W** o **↑** | Acelerar a fondo |
| **S** o **↓** | Frenar / Marcha atrás |
| **A** o **←** | Girar a la izquierda |
| **D** o **→** | Girar a la derecha |
| **ESPACIO** | Salto / Iniciar Derrape / Acrobacia aérea en rampas |
| **E** o **CTRL** | Usar objeto / Mantener presionado para escudo trasero |
| **Q** | Mirar hacia atrás (Cámara trasera) |
| **ESC** | Pausa (Reanudar, Reiniciar, Salir al Menú) |

---

## 🚀 Mecánicas Avanzadas de Conducción

1. **Derrape con Mini-Turbo de 3 Fases**:
   - Pulsa **Espacio** mientras giras para fijar el derrape y contravolantear.
   - **Nivel 1 (0.8s - Chispas Azules)**: Mini-Turbo corto.
   - **Nivel 2 (1.8s - Chispas Naranjas)**: Super Mini-Turbo medio.
   - **Nivel 3 (3.0s - Chispas Moradas)**: Ultra Mini-Turbo máximo de larga duración.
   - Suelta el salto para desatar la propulsión de fuego por los tubos de escape.

2. **Turbo de Salida (Rocket Start)**:
   - Durante la cuenta atrás (3... 2... 1... ¡YA!), mantén el acelerador a fondo cuando el contador marque entre **2 y 1**.
   - Si aceleras antes de tiempo (en el 3), el motor se **calará** y perderás unos segundos valiosos con humo de escape.

3. **Rebufo (Slipstream)**:
   - Sitúate justo detrás de un rival durante 1.8 segundos: la estela de viento activará un acelerón automático para adelantarlo.

4. **Acrobacias en Rampas (Stunt Jump)**:
   - Al salir despegado por una rampa de salto, pulsa **Espacio en el aire** para ejecutar una pirueta acrobática 360º. Al aterrizar recibirás un turbo extra.

5. **Aero-Bot (Dron de Rescate)**:
   - Si caes al vacío o a los fosos de lava, un dron cuadricóptero te rescatará mediante un rayo tractor para devolverte sano y salvo al trazado.

6. **Escudo Protector Trasero**:
   - Mantén pulsado **E** o **Ctrl** con proyectiles o aceite para llevarlos a remolque detrás del kart: absorberán proyectiles rivales que intenten alcanzarte por la espalda.

---

## 👥 Los 8 Pilotos Originales

| Piloto | Clase | Color | Velocidad | Aceleración | Peso | Manejo | Rasgo Especial |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :--- |
| **Rex Bolt** | Ligero | Verde Neón | 72% | 90% | 45% | 92% | Aceleración explosiva en salidas y curvas lentas. |
| **Kira Sparks** | Ligero | Rosa Magenta | 70% | 88% | 50% | 95% | Máximo control en derrapes cerrados. |
| **Capitán Turbo** | Medio | Rojo Pasión | 80% | 80% | 70% | 80% | El veterano legendario: equilibrio absoluto. |
| **Zack Nova** | Medio | Azul Zafiro | 83% | 78% | 68% | 82% | Alta velocidad punta y excelente aerodinámica. |
| **T-VEX 9000** | Medio | Amarillo Titanio | 82% | 82% | 75% | 78% | Androide de titanio con gran tracción. |
| **Berta Búfalo** | Pesado | Naranja Fuego | 92% | 62% | 95% | 60% | Imparable en choques cuerpo a cuerpo. |
| **Gorgón Titán** | Pesado | Púrpura Oscuro | 94% | 58% | 98% | 55% | Bestia blindada con la mayor velocidad máxima. |
| **Dr. Cosmos** | Ligero | Violeta Cósmico | 75% | 94% | 42% | 90% | Kart antigravitatorio con turbo sostenido. |

---

## 🌐 Los 4 Circuitos de la Copa Hipervelocidad

1. 🌴 **Playa Tropical**: Pista costera bajo el sol, palmeras, puente de madera sobre la bahía y cocos gigantes rodantes como obstáculo dinámico.
2. ❄️ **Cumbre Nevada**: Carretera de hielo y nieve en alta montaña con curvas rápidas y rocas nevadas rodantes.
3. 🌋 **Fortaleza Volcánica**: Fuerte de basalto y ríos de magma hirviendo, geysers de fuego y un atajo arriesgado sobre el foso de lava.
4. 🌆 **Metrópolis Neón**: Autopista flotante nocturna entre rascacielos cibernéticos con arcos hiper-turbo y barreras láser móviles.

---

## 🎈 Modo Batalla (Arena de Combate)

- **Escenario cerrado exclusivo**: estadio circular de dos niveles con cajas de objetos repartidas.
- Cada kart lleva **3 globos flotantes**. Cada impacto de objeto o colisión te hace perder un globo.
- ¡Gana el último piloto que quede en pie o el que conserve más globos tras 3 minutos de combate!

---

## 📦 Los 8 Objetos Originales

1. 🛢️ **Aceite Resbaladizo**: Trampa que se suelta atrás y hace trompicar al que la pise.
2. 🟢 **Bólido Verde**: Proyectil de energía directo que rebota contra los límites y vallas.
3. 🔴 **Bólido Rastreador**: Proyectil teledirigido con alerones que persigue al rival de delante.
4. 💠 **Cometa Astral**: Estrella celestial que asciende al cielo y cae en picado provocando una explosión masiva sobre el 1º puesto.
5. ⚡ **Turbo Cósmico x3**: 3 cargas de propulsión hiperespacial a demanda.
6. ⭐ **Escudo Estelar**: Invencibilidad temporal con colores arcoíris, máxima velocidad y empuje total a rivales.
7. 🌀 **Pulso Gravitatorio**: Ataque global que encoge y ralentiza a todos los rivales de la pista.
8. 💣 **Bomba Éter**: Se lanza hacia delante o se suelta, explotando tras unos segundos con gran radio de impacto.

---

## 🎵 Motor de Audio Sintetizado (Web Audio API)

- **Cero archivos MP3 ni WAV**: todo el sonido y la música se sintetizan por software en tiempo real.
- Bandas sonoras procedurales originales compuestas para el Menú, Playa, Nieve, Volcán, Neón, Batalla y Podio.
- ¡Aceleración de tempo (1.2x) durante la **última vuelta**!
- Sonido dinámico del motor por RPM y velocidad, chirrido de derrapes, chispas de mini-turbo, impactos y explosiones.

---

## 💻 Cómo Ejecutar el Juego

Solo necesitas un navegador moderno (Chrome, Edge, Firefox, Brave, Safari, etc.):

1. Abre la carpeta del proyecto en tu ordenador.
2. Haz **doble clic en `index.html`** (o arrástralo a una pestaña del navegador).
3. ¡A correr!

---

## 🐙 Subir a GitHub

Para subir el proyecto a tu cuenta de GitHub (`Javiantonc`):

1. Crea un nuevo repositorio en GitHub llamado **`neokart-gp`** (o el nombre que prefieras).
2. Abre la terminal en esta carpeta y ejecuta:
```bash
git remote add origin https://github.com/Javiantonc/neokart-gp.git
git branch -M main
git push -u origin main
```
*(Si usas GitHub Desktop o VS Code, también puedes pulsar directamente "Publish Repository" / "Publicar rama")*.
