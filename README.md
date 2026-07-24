# 👑 Queens

Un puzzle de lógica inspirado en el clásico juego de las N-reinas, jugable directamente en el navegador. Coloca una corona por fila, columna y región de color, sin que dos coronas se toquen entre sí (ni siquiera en diagonal).

🔗 **Jugar ahora:** https://litsoffthenet.github.io/queens-game/

## Cómo jugar

**Objetivo:** coloca una 👑 corona por fila, por columna y por región de color, sin que dos coronas se toquen entre sí, ni siquiera en diagonal.

**Reglas:**
1. Una corona por fila.
2. Una corona por columna.
3. Una corona por cada color/región.
4. Dos coronas nunca pueden tocarse (horizontal, vertical o diagonal).

**Controles:**
- Toca una casilla para ir pasando por sus estados: vacía → ✕ descartada → 👑 corona → vacía.
- **Doble toque:** coloca la corona directamente (y otro doble toque la borra).
- **Arrastra el dedo:** marca varias ✕ seguidas.

**Ayudas disponibles:**
- **Cruces automáticas:** marca con ✕ las casillas que una corona bloquea automáticamente.
- **Pistas:** si te atascas, puedes pedir ayuda (pista de corona o de descarte). Cada pista tiene un coste en tiempo que se suma a tu tiempo final.

## Multijugador

Un jugador crea la partida como **Anfitrión** y comparte un código de 6 dígitos. El resto de jugadores se une con ese código y todos resuelven exactamente los mismos tableros, cada uno por su cuenta. Al finalizar, se comparan los tiempos y las pistas utilizadas.

## Características

- Generación procedural de tableros de distintos tamaños
- Modo individual y modo multijugador (por código de partida)
- Sistema de pistas con penalización de tiempo
- Modo claro / oscuro
- Interfaz en español e inglés
- Diseño responsive, optimizado para móvil (soporte táctil completo)
- Cronómetro y estadísticas de la partida

## Tecnología

Proyecto **100% frontend**, construido con HTML, CSS y JavaScript vanilla, sin dependencias externas ni build steps.

## ¿Quieres jugar?

Visita **https://litsoffthenet.github.io/queens-game/**
