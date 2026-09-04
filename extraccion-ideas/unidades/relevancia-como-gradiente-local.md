---
titulo: La relevancia no se decide, se realiza (gradiente local del pago)
estado: en desarrollo
primera_aparicion: notas-crudas/nota-08-curvatura-sin-metrica-perspectividad-dinamica.md (2026-09-04)
apariciones:
  - notas-crudas/nota-08-curvatura-sin-metrica-perspectividad-dinamica.md (2026-09-04)
  - notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
pensadores_relacionados: [Daniel Dennett (frame problem), John McCarthy y Patrick Hayes, John Vervaeke (relevance realization), Herbert Simon (satisficing), Karl Friston, W. Ross Ashby, Naftali Tishby (information bottleneck)]
resumen: >
  Cierra el hueco que abre la perspectividad dinámica. Si el sistema debe desplazar su
  perspectiva, ¿cómo elige hacia dónde? La respuesta obvia —evaluar globalmente sobre
  D qué es relevante— **repetiría el atajo prohibido**: exigiría la vista completa que
  la incompletud ya declaró imposible, y genera una regresión del tipo *frame problem*
  (para decidir qué es relevante habría que evaluar todo, y decidir qué evaluar es ya
  el problema). Solución propuesta: **la relevancia no se decide, se realiza** — es el
  gradiente local del pago sobre la carta actual. No es una elección hecha desde
  fuera, es un efecto del propio funcionamiento local del sistema.
---

Es la pieza que impide que la [[perspectividad-dinamica]] se derrumbe en el mismo
error que denuncia. Un sistema que eligiera su próxima perspectiva comparando todas
las perspectivas posibles necesitaría *ya* estar en la vista desde ningún lugar. El
movimiento —bajar la relevancia de *decisión deliberativa* a *gradiente local*— es
formalmente el mismo que la evolución hace con el diseño y el mercado con la
asignación: nadie evalúa el espacio completo; la estructura local hace el trabajo.

Enlaza con el [[conocimiento-distribuido]] (Hayek: ningún nodo evalúa el todo, y no
hace falta) y con los [[patrones-de-autorregulacion]]. Se apoya en el
[[espacio-de-descripciones-y-geodesicas]]: sin la noción de pago no hay gradiente que
seguir.

**Por qué esta unidad tiene dientes (Proyecto A).** Aplicando el antídoto del Camino
E, **prohíbe algo concreto y verificable**: prohíbe cualquier arquitectura regulatoria
que requiera evaluación global del espacio de hipótesis como paso de su ciclo normal
de operación. Es una restricción de diseño, no una interpretación. Predice que todo
sistema que lo intente pagará una explosión combinatoria o hará trampa (usando una
heurística local disfrazada de evaluación global). Eso es un compromiso falsable, y
del tipo que el Camino E echaba de menos en el lote 04–07.

**Cautela epistémica (regla de oro).**
- *Demostrable / establecido:* el frame problem y su regresión son un resultado clásico
  y bien documentado de la IA simbólica (McCarthy & Hayes 1969; Dennett 1984). Que la
  evaluación global sea intratable no es tesis propia.
- *Tesis argumentada:* que el gradiente **local** del pago baste para realizar la
  relevancia. Esto es una apuesta, y tiene un flanco conocido: **los gradientes locales
  se quedan atrapados en óptimos locales**. Un sistema que solo siga el descenso local
  puede quedar clavado en una carta mediocre sin señal de que existe otra mejor lejos.
  Es la vieja tensión exploración/explotación —la misma que la nota 07 nombró como
  [[neguentropia-exploracion-y-compresion]]— y esta unidad **no la resuelve**: la
  hereda. Reconocerlo es parte del rigor; el [[desacuerdo-entre-cartas-vecinas]] es
  precisamente un intento de comprar algo de exploración barata sin pagar vista global.
- *Vecindario a declarar (Camino G):* Vervaeke tiene ya un programa completo con este
  nombre (*relevance realization*), y el verbo «realizar» en vez de «decidir» es suyo.
  Hay que citarlo como fuente, no como coincidencia, y decir en qué se separa el
  proyecto: aquí la relevancia se realiza **sobre un espacio de descripciones con
  costo termodinámico explícito**, no sobre un espacio cognitivo genérico.

**Reapariciones**
- *nota-09*: le impone una **condición formal fuerte** que aquí no estaba: el gradiente
  de relevancia debe ser un **campo covectorial genuino** (una sección del fibrado
  cotangente), no cualquier objeto que se comporte como una flecha. La razón es
  operativa, no estética: sin ese supuesto, dos descripciones «desde aquí» y «desde
  allá» pueden diferir por ser meras coordenadas distintas del mismo punto, y toda la
  alarma de divergencia se dispararía con artefactos de carta en vez de con
  inadecuación real ([[dos-tests-de-divergencia]], Test A). La consistencia exigida es
  concreta: las expresiones locales del mismo covector deben coincidir bajo el
  jacobiano de la transición. La nota lo resume bien — **«de metáfora a ecuación»**.
  Es el paso donde «gradiente local» deja de ser una imagen tomada del descenso por
  gradiente y pasa a ser un objeto con reglas de transformación.
  *Contrapartida:* al fijar el espacio muestral en compresión y no en predicción
  ([[compresion-con-perdida-y-tasa-distorsion]]), la nota 09 deja la **relevancia misma
  fuera del formalismo** — hay geometría para el gradiente, pero nada dice todavía de
  qué es gradiente. El *information bottleneck* es el candidato señalado para cerrarlo,
  y por eso pasa a ser una pieza necesaria y no un adorno futuro.

**Veredicto de recurrencia**: recurrente (notas 08 y 09). Junto con
[[perspectividad-dinamica]] y [[desacuerdo-entre-cartas-vecinas]], forma el trío que
lleva la incompletud desde el resultado negativo hacia un modelo de regulación.
