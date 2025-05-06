# Creado por: Joel Antonio Jaquez López - 23369

# Temporizador con React (useRef, useEffect y useState)

Este proyecto es un cronómetro funcional construido con **React usando CDN**, que utiliza los hooks `useRef`, `useState` y `useEffect` para manejar el tiempo, controlar la ejecución y registrar sesiones de forma eficiente.

---

## Objetivos del proyecto

- Aplicar `useState` para manejar:
  - El tiempo (`time`)
  - El estado de ejecución (`isRunning`)
  - La lista de sesiones (`sessions`)
- Utilizar `useRef` para guardar el **ID del intervalo** sin causar re-render.
- Controlar el inicio y limpieza del temporizador con `useEffect`.
- Permitir guardar múltiples sesiones con su tiempo registrado.

---

## Tecnologías utilizadas

- React 18 vía CDN
- ReactDOM 18 vía CDN
- Babel vía CDN para procesar JSX

---

## Funcionalidades

- **Iniciar / Pausar** el temporizador
- **Reiniciar** el cronómetro a 0
- **Guardar sesiones** con el tiempo actual
- Mostrar la lista completa de sesiones guardadas

---

## Estructura del código

- `useState` para los valores dinámicos (`time`, `isRunning`, `sessions`)
- `useRef` para guardar el ID del `setInterval`
- `useEffect` que:
  - Inicia el contador al activar `isRunning`
  - Detiene el contador si se pausa o se reinicia
  - Limpia siempre el intervalo al desmontar o al cambiar `isRunning`

---

## Cómo usar

1. Cloná el repositorio o descargá el archivo `index.html`.
2. Abrí `index.html` en tu navegador.
3. Accediendo directamente a la ruta del servidor: http://awita.site/usuarios/jaq23369/React%20Hooks%20%28useRef%29%20CDN/React%20Hooks%20%28useRef%29%20CDN/




