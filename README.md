# Actividad 2 — Registro en pruebas cerradas y retroalimentación de aplicaciones móviles

<p align="center">
  <b>Instituto Politécnico Nacional</b><br>
  <b>Escuela Superior de Cómputo (ESCOM)</b><br>
  Ingeniería en Sistemas Computacionales — Plan 2020<br>
  Unidad de aprendizaje: <b>Desarrollo de aplicaciones móviles nativas</b>
  <b>Alumno:</b> Caballero Pérez Julio César<br>
  <b>Grupo:</b> 7CV4<br>
</p>



## Índice

1. [Objetivo](#1-objetivo)
2. [Metodología de prueba](#2-metodología-de-prueba)
3. [Parte 1 — Aplicación 1: Five Nights at ESCOM](#3-parte-1--aplicación-1-five-nights-at-escom)
4. [Parte 2 — Aplicación 2: Salones](#4-parte-2--aplicación-2-salones)
5. [Parte 3 — Evaluación de AUTECH](#5-parte-3--evaluación-de-autech)
6. [Resumen de pruebas](#6-resumen-de-pruebas)
7. [Conclusiones](#7-conclusiones)

---

## 1. Objetivo

Participar como persona probadora (*tester*) en dos aplicaciones distribuidas mediante pruebas cerradas de Google Play, documentar su instalación y funcionamiento con evidencias reales, y posteriormente evaluar la aplicación **AUTECH** mediante observaciones positivas, negativas y el formulario de retroalimentación solicitado.

## 2. Metodología de prueba

Para cada aplicación se siguió el mismo procedimiento:

1. **Inscripción:** Abrir el enlace de prueba cerrada con la cuenta de Google autorizada como *tester* y aceptar la participación.
2. **Instalación:** Desde la ficha de Google Play, instalar la aplicación en el dispositivo Android.
3. **Ejecución:** Abrir la aplicación y verificar que inicia correctamente.
4. **Pruebas funcionales:** Explorar las funciones principales y registrar el resultado de cada prueba (✅ correcto / ⚠️ con observaciones / ❌ falla).
5. **Evidencias:** Capturas de pantalla tomadas en el propio dispositivo.



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
  <img src="capturas/Inscripcion_FNAF.png" alt="Inscripción Five Nights at ESCOM" width="300">
  <br><i>Figura 1. Confirmación de inscripción a la prueba cerrada de Five Nights at ESCOM.</i>
</p>

### 3.2 Instalación y ejecución

Desde la ficha de Google Play se instaló la aplicación y se abrió en el dispositivo.

<p align="center">
  <img src="capturas/PlayStore_FNAE.jpeg" alt="Five Nights at ESCOM instalada" width="300">
  &nbsp;&nbsp;
   <br><i>Figura 2. Aplicación instalada desde Google Play.
   </i>

</p>
<p align="center">
  <img src="capturas/Ejecuccion_FNAE.jpeg" alt="Five Nights at ESCOM instalada" width="300">
  &nbsp;&nbsp;
   <br><i>FFigura 3. Aplicación abierta y en ejecución.</i>
</p>

### 3.3 Pruebas realizadas

| # | Función probada | Pasos | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|---|
| P1 | Inicio de la aplicación | Abrir la app desde el ícono | Carga la pantalla principal sin cerrarse | `Se abrio la aplicación sin ningún problema, mostrando correctamente el menú del juego.` | `✅` |
| P2 | Menú principal / navegación | Tocar las opciones del menú | Cada opción abre su pantalla | `Se probaron todas las opciónes en el menú principal, donde se muestra la opción de "Nueva partida" y "Salir"` | `✅` |
| P3 | Iniciar una partida | Seleccionar "Jugar" / nueva noche | Comienza el juego | `Se selecciono la opción de "Nueva partida" y empezo correctamente la introducción al juego y posteriormente se puede empezar a jugar la primera noche. Algo que me llamo la atención es que al momento de seleccionar "Nueva partida" despliega un submenu mostrando las opciónes "Continuar", "Opciones", "Extras" cuando estas deberian de mostrar una vez se finalize la primera noche o al principio del menu principal aún sin iniciar la primera noche.` | `⚠️` |
| P4 | Controles en juego (cámaras, puertas, etc.) | Usar los controles durante la partida | Responden al toque | `Todos los controles funcionan correctamente y reaccionan de manera correcta a la interacción del usuario.` | `✅` |
| P5 | Sonido / audio | Jugar con volumen activado | Se escucha música y efectos | `Se escucha algo bajo el volumen al estar dentro del juego.` | `⚠️` |
| P6 | Salir y volver a entrar | Minimizar y regresar a la app | Conserva el estado o regresa al menú | `Al momento de Salir del juego y volver a entrar se queda correctamente en el estado en donde se quedo y la hora.` | `✅` |

<p align="center">
  <img src="capturas/Funcionamiento_FNAE.jpeg" alt="Prueba de función" width="300">
  <br><i>Figura 4. Evidencia de la función probada en Five Nights at ESCOM.</i>
</p>

### 3.4 Observación

> **Observación:** `Todo el juego funciona correctamente , exceptuando la parte de la musica que se escucha bajo, el menú principal que despliega las opciones y se llega observar que aparecen despues de seleccionar la opción de "Nueva partida".`

---

## 4. Parte 2 — Aplicación 2: Salones

| Campo | Información |
|---|---|
| **Paquete** | `ovh.gabrielhuav.salones` |
| **Inscripción a prueba cerrada** | https://play.google.com/apps/testing/ovh.gabrielhuav.salones |
| **Ficha de Google Play** | https://play.google.com/store/apps/details?id=ovh.gabrielhuav.salones |

### 4.1 Inscripción a la prueba cerrada

<p align="center">
  <img src="capturas/Inscripcion_Salones_UAM.png" alt="Inscripción Salones" width="300">
  <br><i>Figura 5. Confirmación de inscripción a la prueba cerrada de Salones.</i>
</p>

### 4.2 Instalación y ejecución

<p align="center">
  <img src="capturas/PlayStore_UAM.jpeg" alt="Salones instalada" width="300"><br><i>Figura 6. Aplicación instalada desde Google Play.</i>
  &nbsp;&nbsp;
  <img src="capturas/Funcionamiento_UAM.jpeg" alt="Salones en ejecución" width="300">
  <br><i>Figura 7. Aplicación abierta y en ejecución.</i>
</p>

### 4.3 Pruebas realizadas

| # | Función probada | Pasos | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|---|
| P1 | Inicio de la aplicación | Abrir la app desde el ícono | Muestra la pantalla principal | `Al momento de presionar el icono de la app la abre correctamente y muestra el mapa de la UAM` | `✅` |
| P2 | Consulta / búsqueda de salones | Buscar o seleccionar un salón | Muestra la información del salón | `Al presionar el boton "Ruta" despliega correctamente  el destino y el origen para poder ubicar el salón.` | `✅` |
| P3 | Visualización de la información (mapa, edificio, etc.) | Abrir el detalle de un salón | Datos legibles y correctos | `En mi caso no pude abrir los detalles del salón,lo unico que me muestra es el tiempo que me hago de mi destino al edificio, lo cual cumple con el objetivo de la aplicación.` | `✅` |
| P4 | Navegación entre pantallas | Usar botón atrás y menús | Regresa a la pantalla anterior | `Todos los botones funcionan correctamente, cumpliendo su objetivo.` | `✅` |
| P5 | Rotación de pantalla | Girar el dispositivo | La interfaz se adapta sin perder datos | `La implementación de la rotación a mi parecer no es del todo comoda para el usuario ya que es algo distinta a las demás aplicaciones que usan la rotación para un mapa, se podria mejorar un poco, pero en general si funciona .` | `⚠️` |

<p align="center">
  <img src="capturas/Funcion_salones_UAM.jpeg" alt="Prueba de función" width="300">
  <br><i>Figura 8. Evidencia de la función probada en Salones.</i>
</p>

### 4.4 Observación

> **Observación:** `Todo funciona correctamente con la aplicación.`

---

## 5. Parte 3 — Evaluación de AUTECH

| Campo | Información |
|---|---|
| **Enlace de inscripción** | `QR  - Proporcionado por los alumnos del profesor` |


### 5.1 Registro, instalación y uso

<div align="center">

  <img src="capturas/Inscripción_AUTECH.jpeg"
       alt="Inscripción AUTECH"
       width="300">

  <p><strong>Figura 9.</strong> Inscripción a la aplicación AUTECH.</p>

</div>

<div align="center">

  <img src="capturas/Funcionamiento_AUTECH.jpeg"
       alt="AUTECH en ejecución"
       width="300">

  <p><strong>Figura 10.</strong> AUTECH en ejecución.</p>

</div>

<div align="center">

  <img src="capturas/Herramienta_probada_AUTECH.jpeg"
       alt="Herramienta probada en AUTECH"
       width="300">

  <p><strong>Figura 11.</strong> Uso de una función principal de AUTECH.</p>

</div>
### 5.2 Módulo: Construcción de autómatas y Expresiones Regulares
 
Se probó el lienzo de construcción y la conversión de una expresión regular a AFD. Con la expresión `abc` y el botón **Generar AFD**, la app generó un **AFD mínimo de 5 estados**. También mostró la simulación paso a paso de la cadena `abc`, que terminó en **ACEPTADA**, y casos de prueba: `abc` ✓, `ε` ✗, `ab` ✗, `abcc` ✗. La pestaña Regex → AFD incluye expresiones de ejemplo listas para usar (`a*b`, `(a|b)*`, `a(b|c)*`, `(ab)+`, `a?b*c`, `(a|b)*abb`).
 
<p align="center">
  <img src="capturas/autech_03_regex_construir.jpeg" alt="Construir autómata" width="250">
  &nbsp;
  <img src="capturas/autech_04_regex_afd_abc.jpeg" alt="Regex abc a AFD" width="250">
  &nbsp;
  <img src="capturas/autech_05_regex_ejemplos.jpeg" alt="Ejemplos de regex" width="250">
  <br><i>Figura 11. Lienzo de construcción. Figura 12. AFD mínimo generado para <code>abc</code> y simulación aceptada. Figura 13. Expresiones de ejemplo.</i>
</p>

### 5.3 Módulo: Autómatas y Lenguajes
 
Se revisaron sus tres pestañas. **AFN → AFD** tiene un lienzo para dibujar el autómata y un campo para probar una o varias cadenas. **Operaciones** permite definir varios lenguajes (L1, L2) con un teclado de símbolos y aplicar unión, concatenación, cierre de Kleene, intersección, complemento, diferencia, reversa, homomorfismo y cociente. **Simplificación** obtiene el AFD con el mínimo número de estados.
 
<p align="center">
  <img src="capturas/autech_06_afn_afd.jpeg" alt="AFN a AFD" width="250">
  &nbsp;
  <img src="capturas/autech_07_operaciones.jpeg" alt="Operaciones con lenguajes" width="250">
  &nbsp;
  <img src="capturas/autech_08_simplificacion.jpeg" alt="Simplificación" width="250">
  <br><i>Figura 14. AFN → AFD. Figura 15. Operaciones entre lenguajes. Figura 16. Simplificación de AFD.</i>
</p>

### 5.4 Módulo: Autómata de Pila (PDA)
 
Se definió un PDA con estados `q0,q1,q2`, alfabeto `a,b`, alfabeto de pila `A,Z`, estado inicial `q0`, símbolo inicial de pila `Z`, estado de aceptación `q2` y **5 transiciones**. Corresponde al lenguaje aⁿbⁿ. También se revisaron las pestañas **Simular** (opciones *Grafo + pila* y *Pila + transiciones*) y **CFG** (conversión a gramática libre de contexto, que funciona sin conexión al servidor).
 
<p align="center">
  <img src="capturas/autech_09_pda_definir.jpeg" alt="Definir PDA" width="250">
  &nbsp;
  <img src="capturas/autech_10_pda_simular.jpeg" alt="Simular PDA" width="250">
  &nbsp;
  <img src="capturas/autech_11_pda_cfg.jpeg" alt="PDA a CFG" width="250">
  <br><i>Figura 17. Definición del PDA. Figura 18. Pestaña de simulación. Figura 19. Conversión a CFG.</i>
</p>

### 5.5 Módulo: Máquina de Turing
 
Se definió una MT con estados `q0,q1,q2,q3,qf`, estado inicial `q0`, estado de aceptación `qf`, **11 transiciones** en formato `estado,leer -> nuevo_estado,escribir,dirección` y cinta inicial `aabb`. Reconoce aⁿbⁿ marcando con `X` y `Y`. La pestaña **Grafo** dibujó correctamente el diagrama de estados, con su leyenda (inicial, aceptación, actual, normal) y controles de zoom.
 
<p align="center">
  <img src="capturas/autech_12_mt_definicion.jpeg" alt="Definición MT" width="250">
  &nbsp;
  <img src="capturas/autech_13_mt_simulacion.jpeg" alt="Simulación MT" width="250">
  &nbsp;
  <img src="capturas/autech_14_mt_grafo.jpeg" alt="Grafo MT" width="250">
  <br><i>Figura 20. Definición de la MT. Figura 21. Pestaña de simulación. Figura 22. Grafo generado de la MT.</i>
</p>

### 5.6 Pruebas realizadas
 
| # | Función probada | Pasos | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|---|
| P1 | Pantalla de acceso | Abrir la app | Muestra opciones de inicio de sesión | Muestra login, crear cuenta, modo invitado y registro de profesor | ✅ |
| P2 | Menú de herramientas | Entrar a la app | Lista de módulos disponibles | Muestra los 4 módulos con descripción y etiquetas | ✅ |
| P3 | Regex → AFD | Escribir `abc` y presionar *Generar AFD* | Genera un AFD equivalente | Genera un AFD mínimo de 5 estados con su grafo | ✅ |
| P4 | Simulación de cadena | Simular `abc` en el AFD generado | La cadena es aceptada | Animación paso a paso (3/3) y resultado **ACEPTADA** | ✅ |
| P5 | Casos de prueba | Revisar cadenas `ε`, `ab`, `abcc` | Se rechazan | Se marcan como rechazadas (✗) | ✅ |
| P6 | Operaciones entre lenguajes | Abrir pestaña *Operaciones* | Muestra las operaciones disponibles | Muestra L1/L2, teclado de símbolos y 9 operaciones | ✅ |
| P7 | Definición de PDA | Capturar estados, alfabetos y 5 transiciones | Se registran sin errores | Tabla de transiciones capturada correctamente | ✅ |
| P8 | Simulación de PDA | Ir a la pestaña *Simular* | Permite simular el PDA definido | Pide validar la definición antes de mostrar el grafo | ⚠️ |
| P9 | Definición de MT | Capturar 11 transiciones y cinta `aabb` | Se acepta la definición | Definición capturada en modo texto | ✅ |
| P10 | Grafo de MT | Abrir pestaña *Grafo* | Dibuja el diagrama de estados | Grafo generado con leyenda y zoom | ✅ |
| P11 | Simulación de MT | Abrir pestaña *Simulación* | Muestra la simulación | Pide configurar e iniciar desde *Definición* primero | ⚠️ |
 
### 5.7 Aspectos positivos
 
| # | Aspecto | Descripción |
|---|---|---|
| 1 | **Organización y navegación** | Cada herramienta tiene pestañas claras (Definir / Simular / Grafo o CFG) y el menú principal describe cada módulo con etiquetas (NFA→DFA, PDA, CFG, etc.), por lo que se encuentra rápido lo que se busca. |
| 2 | **Visualización y simulación paso a paso** | La conversión de `abc` a AFD mínimo dibujó el grafo y animó la lectura de la cadena símbolo por símbolo hasta indicar "ACEPTADA". Esto ayuda mucho a entender cómo funciona el autómata. |
| 3 | **Utilidad y ejemplos incluidos** | Tiene expresiones regulares de ejemplo listas para usar, casos de prueba automáticos (cadenas aceptadas y rechazadas), varias operaciones entre lenguajes y conversión PDA → CFG que funciona sin conexión. |
 
### 5.8 Aspectos negativos
 
| # | Problema / limitación | Contexto en que se presenta | Sugerencia de mejora |
|---|---|---|---|
| 1 | **Línea gris sobre los botones de la barra de herramientas** | En los lienzos de *Construir* y *AFN → AFD* (Figuras 11, 14 y 16), una línea horizontal atraviesa los botones "Estado" y "Transición" y parece que el texto está tachado. | Revisar el *layout* de esa barra para que el separador o indicador no se encime sobre los botones. |
| 2 | **Textos recortados** | El título "Autómata de Pila (PD..." aparece truncado en la barra superior. En *AFN → AFD* la ayuda de uso se corta ("transiciones vacías" queda incompleto). | Usar un título corto (por ejemplo, "PDA") o permitir dos líneas, y hacer que el cuadro de ayuda crezca o pueda expandirse. |
| 3 | **Flujo de simulación poco directo** | En la MT y el PDA, la pestaña *Simulación* aparece vacía aunque la definición ya esté capturada. Hay que regresar a *Definición* y presionar "Iniciar Simulación" o "Validar definición". Además, en el grafo de la MT (zoom 61%) las etiquetas de las transiciones se leen muy pequeñas. | Validar automáticamente al cambiar de pestaña o poner un botón "Simular" directamente ahí, y ajustar el zoom inicial o el tamaño de las etiquetas del grafo. |
 
### 5.9 Formulario de retroalimentación
 
Se respondió el formulario de retroalimentación solicitado por el docente.
 
<p align="center">
  <img src="capturas/autech_15_formulario.png" alt="Confirmación del formulario" width="300">
  <br><i>Figura 23. Confirmación de envío del formulario (sin datos personales visibles).</i>
</p>
---
 
## 6. Resumen de pruebas
 
| Aplicación | Inscripción | Instalación | Ejecución | Pruebas OK | Observaciones |
|---|---|---|---|---|---|
| Five Nights at ESCOM | `[✅/❌]` | `[✅/❌]` | `[✅/❌]` | `[x / 6]` | `[Resumen en una línea]` |
| Salones | `[✅/❌]` | `[✅/❌]` | `[✅/❌]` | `[x / 5]` | `[...]` |
| AUTECH | ✅ | ✅ | ✅ | 9 / 11 (2 con observaciones) | Funciona bien; detalles de interfaz y flujo de simulación |
 
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
    ├── autech_01_inicio_sesion.jpeg
    ├── autech_02_herramientas.jpeg
    ├── autech_03_regex_construir.jpeg
    ├── autech_04_regex_afd_abc.jpeg
    ├── autech_05_regex_ejemplos.jpeg
    ├── autech_06_afn_afd.jpeg
    ├── autech_07_operaciones.jpeg
    ├── autech_08_simplificacion.jpeg
    ├── autech_09_pda_definir.jpeg
    ├── autech_10_pda_simular.jpeg
    ├── autech_11_pda_cfg.jpeg
    ├── autech_12_mt_definicion.jpeg
    ├── autech_13_mt_simulacion.jpeg
    ├── autech_14_mt_grafo.jpeg
    └── autech_15_formulario.png
```