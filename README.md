# Actividad 2 — Registro en pruebas cerradas y retroalimentación de aplicaciones móviles

<p align="center">
  <b>Instituto Politécnico Nacional</b><br>
  <b>Escuela Superior de Cómputo (ESCOM)</b><br>
  Ingeniería en Sistemas Computacionales — Plan 2020<br>
  Unidad de aprendizaje: <b>Desarrollo de aplicaciones móviles nativas</b>
</p>

| Dato | Valor |
|---|---|
| **Nombre completo** | `[Tu nombre completo]` |
| **Boleta** | `[Tu boleta]` |
| **Grupo** | `[Tu grupo]` |
| **Fecha** | `[DD/MM/2026]` |
| **Dispositivo de prueba** | `[Marca y modelo, ej. Samsung Galaxy A54]` |
| **Versión de Android** | `[ej. Android 14]` |

---

## Índice

1. [Objetivo](#1-objetivo)
2. [Metodología de prueba](#2-metodología-de-prueba)
3. [Parte 1 — Aplicación 1: Five Nights at ESCOM](#3-parte-1--aplicación-1-five-nights-at-escom)
4. [Parte 1 — Aplicación 2: Salones](#4-parte-1--aplicación-2-salones)
5. [Parte 2 — Evaluación de AUTECH](#5-parte-2--evaluación-de-autech)
6. [Resumen de pruebas](#6-resumen-de-pruebas)
7. [Conclusiones](#7-conclusiones)

---

## 1. Objetivo

Participar como persona probadora (*tester*) en dos aplicaciones distribuidas mediante pruebas cerradas de Google Play, documentar su instalación y funcionamiento con evidencias reales, y posteriormente evaluar la aplicación **AUTECH** mediante observaciones positivas, negativas y el formulario de retroalimentación solicitado.

## 2. Metodología de prueba

Para cada aplicación se siguió el mismo procedimiento:

1. **Inscripción:** abrir el enlace de prueba cerrada con la cuenta de Google autorizada como *tester* y aceptar la participación.
2. **Instalación:** desde la ficha de Google Play, instalar la aplicación en el dispositivo Android.
3. **Ejecución:** abrir la aplicación y verificar que inicia correctamente.
4. **Pruebas funcionales:** explorar las funciones principales y registrar el resultado de cada prueba (✅ correcto / ⚠️ con observaciones / ❌ falla).
5. **Evidencias:** capturas de pantalla tomadas en el propio dispositivo.

> Las capturas se guardan en la carpeta `capturas/` del repositorio.

---

## 3. Parte 1 — Aplicación 1: Five Nights at ESCOM

| Campo | Información |
|---|---|
| **Paquete** | `ovh.gabrielhuav.fivenightsatescom` |
| **Inscripción a prueba cerrada** | https://play.google.com/apps/testing/ovh.gabrielhuav.fivenightsatescom |
| **Ficha de Google Play** | https://play.google.com/store/apps/details?id=ovh.gabrielhuav.fivenightsatescom |

### 3.1 Inscripción a la prueba cerrada

Se abrió el enlace de inscripción con la cuenta de Google autorizada y se aceptó la participación como *tester*.

<p align="center">
  <img src="capturas/fnae_01_inscripcion.png" alt="Inscripción Five Nights at ESCOM" width="300">
  <br><i>Figura 1. Confirmación de inscripción a la prueba cerrada de Five Nights at ESCOM.</i>
</p>

### 3.2 Instalación y ejecución

Desde la ficha de Google Play se instaló la aplicación y se abrió en el dispositivo.

<p align="center">
  <img src="capturas/fnae_02_instalada.png" alt="Five Nights at ESCOM instalada" width="300">
  &nbsp;&nbsp;
  <img src="capturas/fnae_03_abierta.png" alt="Five Nights at ESCOM en ejecución" width="300">
  <br><i>Figura 2. Aplicación instalada desde Google Play. Figura 3. Aplicación abierta y en ejecución.</i>
</p>

### 3.3 Pruebas realizadas

| # | Función probada | Pasos | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|---|
| P1 | Inicio de la aplicación | Abrir la app desde el ícono | Carga la pantalla principal sin cerrarse | `[Describe lo que pasó]` | `[✅/⚠️/❌]` |
| P2 | Menú principal / navegación | Tocar las opciones del menú | Cada opción abre su pantalla | `[...]` | `[...]` |
| P3 | Iniciar una partida | Seleccionar "Jugar" / nueva noche | Comienza el juego | `[...]` | `[...]` |
| P4 | Controles en juego (cámaras, puertas, etc.) | Usar los controles durante la partida | Responden al toque | `[...]` | `[...]` |
| P5 | Sonido / audio | Jugar con volumen activado | Se escucha música y efectos | `[...]` | `[...]` |
| P6 | Salir y volver a entrar | Minimizar y regresar a la app | Conserva el estado o regresa al menú | `[...]` | `[...]` |

<p align="center">
  <img src="capturas/fnae_04_funcion.png" alt="Prueba de función" width="300">
  <br><i>Figura 4. Evidencia de la función probada en Five Nights at ESCOM.</i>
</p>

### 3.4 Observación

> **Observación:** `[Escribe aquí al menos una observación concreta. Ejemplo de formato: "Al iniciar la noche 1, las cámaras cambian correctamente, pero el botón de la puerta derecha tarda en responder cuando se toca repetidamente."]`

---

## 4. Parte 1 — Aplicación 2: Salones

| Campo | Información |
|---|---|
| **Paquete** | `ovh.gabrielhuav.salones` |
| **Inscripción a prueba cerrada** | https://play.google.com/apps/testing/ovh.gabrielhuav.salones |
| **Ficha de Google Play** | https://play.google.com/store/apps/details?id=ovh.gabrielhuav.salones |

### 4.1 Inscripción a la prueba cerrada

<p align="center">
  <img src="capturas/salones_01_inscripcion.png" alt="Inscripción Salones" width="300">
  <br><i>Figura 5. Confirmación de inscripción a la prueba cerrada de Salones.</i>
</p>

### 4.2 Instalación y ejecución

<p align="center">
  <img src="capturas/salones_02_instalada.png" alt="Salones instalada" width="300">
  &nbsp;&nbsp;
  <img src="capturas/salones_03_abierta.png" alt="Salones en ejecución" width="300">
  <br><i>Figura 6. Aplicación instalada desde Google Play. Figura 7. Aplicación abierta y en ejecución.</i>
</p>

### 4.3 Pruebas realizadas

| # | Función probada | Pasos | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|---|
| P1 | Inicio de la aplicación | Abrir la app desde el ícono | Muestra la pantalla principal | `[...]` | `[...]` |
| P2 | Consulta / búsqueda de salones | Buscar o seleccionar un salón | Muestra la información del salón | `[...]` | `[...]` |
| P3 | Visualización de la información (mapa, edificio, horario, etc.) | Abrir el detalle de un salón | Datos legibles y correctos | `[...]` | `[...]` |
| P4 | Navegación entre pantallas | Usar botón atrás y menús | Regresa a la pantalla anterior | `[...]` | `[...]` |
| P5 | Rotación de pantalla | Girar el dispositivo | La interfaz se adapta sin perder datos | `[...]` | `[...]` |

<p align="center">
  <img src="capturas/salones_04_funcion.png" alt="Prueba de función" width="300">
  <br><i>Figura 8. Evidencia de la función probada en Salones.</i>
</p>

### 4.4 Observación

> **Observación:** `[Escribe aquí al menos una observación concreta: función probada, resultado o error encontrado.]`

---

## 5. Parte 2 — Evaluación de AUTECH

| Campo | Información |
|---|---|
| **Enlace de inscripción** | `[Enlace proporcionado por el docente]` |
| **Ficha de Google Play** | `[Enlace proporcionado por el docente]` |

### 5.1 Registro, instalación y uso

<p align="center">
  <img src="capturas/autech_01_inscripcion.png" alt="Inscripción AUTECH" width="250">
  &nbsp;
  <img src="capturas/autech_02_abierta.png" alt="AUTECH en ejecución" width="250">
  &nbsp;
  <img src="capturas/autech_03_funcion.png" alt="Función de AUTECH" width="250">
  <br><i>Figura 9. Inscripción. Figura 10. AUTECH en ejecución. Figura 11. Uso de una función principal.</i>
</p>

### 5.2 Pruebas realizadas

| # | Función probada | Pasos | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|---|
| P1 | Inicio de la aplicación | Abrir la app | Carga correctamente | `[...]` | `[...]` |
| P2 | `[Función principal 1]` | `[...]` | `[...]` | `[...]` | `[...]` |
| P3 | `[Función principal 2]` | `[...]` | `[...]` | `[...]` | `[...]` |
| P4 | `[Función principal 3]` | `[...]` | `[...]` | `[...]` | `[...]` |

### 5.3 Aspectos positivos

| # | Aspecto | Descripción |
|---|---|---|
| 1 | `[ej. Navegación]` | `[Explica brevemente la fortaleza observada]` |
| 2 | `[ej. Utilidad]` | `[...]` |
| 3 | `[ej. Rendimiento / claridad]` | `[...]` |

### 5.4 Aspectos negativos

| # | Problema / limitación | Contexto en que se presenta | Sugerencia de mejora |
|---|---|---|---|
| 1 | `[...]` | `[Pantalla o acción donde ocurre]` | `[...]` |
| 2 | `[...]` | `[...]` | `[...]` |
| 3 | `[...]` | `[...]` | `[...]` |

### 5.5 Formulario de retroalimentación

Se respondió el formulario de retroalimentación solicitado por el docente.

<p align="center">
  <img src="capturas/autech_04_formulario.png" alt="Confirmación del formulario" width="300">
  <br><i>Figura 12. Confirmación de envío del formulario (sin datos personales visibles).</i>
</p>

---

## 6. Resumen de pruebas

| Aplicación | Inscripción | Instalación | Ejecución | Pruebas OK | Observaciones |
|---|---|---|---|---|---|
| Five Nights at ESCOM | `[✅/❌]` | `[✅/❌]` | `[✅/❌]` | `[x / 6]` | `[Resumen en una línea]` |
| Salones | `[✅/❌]` | `[✅/❌]` | `[✅/❌]` | `[x / 5]` | `[...]` |
| AUTECH | `[✅/❌]` | `[✅/❌]` | `[✅/❌]` | `[x / 4]` | `[...]` |

> **Incidencias:** `[Si alguna prueba cerrada no permitió inscribirse o instalar, describe el mensaje mostrado, incluye su captura y anota que se comunicó al docente. Si no hubo, escribe "Sin incidencias".]`

---

## 7. Conclusiones

`[Redacta un párrafo breve sobre lo aprendido: cómo funcionan las pruebas cerradas en Google Play, la importancia de la retroalimentación de los testers antes de publicar una app, y qué aplicación tuvo mejor experiencia y por qué.]`

---

## Estructura del repositorio

```
.
├── README.md
└── capturas/
    ├── fnae_01_inscripcion.png
    ├── fnae_02_instalada.png
    ├── fnae_03_abierta.png
    ├── fnae_04_funcion.png
    ├── salones_01_inscripcion.png
    ├── salones_02_instalada.png
    ├── salones_03_abierta.png
    ├── salones_04_funcion.png
    ├── autech_01_inscripcion.png
    ├── autech_02_abierta.png
    ├── autech_03_funcion.png
    └── autech_04_formulario.png
```
