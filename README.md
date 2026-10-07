# Juego de la Vida

Aplicación web interactiva del Juego de la Vida de Conway, hecha con HTML, CSS y JavaScript (sin frameworks, sin backend).

**Para quién:** personas que quieren explorar cómo unas reglas simples producen patrones que se mueven y se repiten.

## Qué hace
- Clic en el tablero: da vida o quita la vida a una celda.
- Botones (y atajos): Iniciar/Pausar (Espacio), Un paso (N), Aleatorio (G), Limpiar (C), Patrón (P) y selector de velocidad.
- Caja de comandos: `iniciar`, `pausa`, `paso 10`, `azar`, `limpiar`, `patron sapo`, `velocidad rapida`, `ayuda`.
- Patrones de ejemplo (osciladores): parpadeador, sapo, baliza y púlsar.

## Decisión de comportamiento
Los bordes del tablero son muros: no hay vida fuera del tablero (no da la vuelta al otro lado).

## Cómo abrirla
Abre `index.html` en el navegador.

## Créditos
Basada en el Juego de la Vida original de John Conway (1970). Versión web adaptada de mi programa en Python (pygame), construida con ayuda de IA.
