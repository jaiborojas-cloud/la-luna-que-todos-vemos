---
titulo: El espacio de descripciones D (atlas sin mapa único) y las geodésicas de pago
estado: semilla
primera_aparicion: notas-crudas/nota-08-curvatura-sin-metrica-perspectividad-dinamica.md (2026-09-04)
apariciones:
  - notas-crudas/nota-08-curvatura-sin-metrica-perspectividad-dinamica.md (2026-09-04)
  - notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
pensadores_relacionados: [Rolf Landauer, Jorma Rissanen (MDL), Karl Friston, Bernhard Riemann, Henri Poincaré, Carlo Rovelli, Ronald Fisher, Shun'ichi Amari, Claude Shannon (tasa-distorsión)]
resumen: >
  Escenario formal propuesto para la perspectividad dinámica. D = espacio de las
  descripciones posibles que un sistema S puede sostener de sí mismo y de aquello de
  lo que depende. Tres rasgos: (1) **no tiene punto privilegiado** — su estructura es
  de *atlas* (muchas cartas locales que se solapan), no de mapa único; (2) cada
  perspectiva es **auto-referida**: incluye una representación de S modelándose;
  (3) toda transición entre cartas **cuesta** (pago disipativo, tipo Landauer). De ahí
  la definición de **geodésica de perspectiva**: la trayectoria que minimiza el pago
  acumulado por unidad de residuo resuelto. No converge: es asintótica.
---

Es el escenario que necesita la [[perspectividad-dinamica]] para dejar de ser una
consigna («muévete») y volverse un problema tratable («muévete *cómo*, pagando
*cuánto*»). El atlas es la traducción geométrica exacta del resultado del Camino A:
si no hay carta global, solo quedan cartas locales y sus solapes — y la pregunta
regulatoria se convierte en **cómo se transita entre ellas**.

Hereda de la [[entropia-como-variable-relacional]] su pieza más dura: el *pago*. Y
extiende la [[topologia-forma-de-la-relacion]] de lo espacial-estático (la
incompletud como propiedad de la forma) a lo dinámico (la incompletud como propiedad
del *recorrido*). El criterio «pago por unidad de residuo resuelto» es primo
declarado de MDL (Rissanen) y de la energía libre variacional (Friston): ganancia
regulatoria por unidad de complejidad.

**Cautela epistémica (regla de oro).** Esta unidad es, hoy, **andamiaje formal sin
formalizar**. Tres deudas concretas, que conviene dejar escritas antes de que la
elegancia las tape:

1. **D no tiene métrica ni conexión definidas.** Sin métrica no hay «geodésica» en
   sentido matemático: hay *trayectoria de costo mínimo* en un grafo de transiciones,
   que es un objeto más pobre y más honesto. Es la misma autocrítica registrada en
   [[holonomia-y-memoria-como-torsion]]. **Estatuto actual: analógico.**
2. **«Residuo» no está definido.** Todo el criterio depende de él, igual que la nota
   07 dependía de un `R(t)` sin definir (y allí el propio interlocutor lo señaló como
   *el* problema matemático). Candidato razonable: residuo = error de predicción no
   absorbido por la carta actual sobre las variables esenciales. Mientras no se fije,
   «minimizar pago por unidad de residuo» es una intuición, no un funcional.
3. **Landauer acota el *borrado*, no toda computación.** El principio fija un costo
   mínimo (kT·ln2 por bit) para operaciones **lógicamente irreversibles**; la
   computación reversible puede, en principio, ser arbitrariamente barata. Que «toda
   transición cuesta» exige por tanto la premisa extra de que cambiar de carta
   **descarta información** (la carta vieja se abandona). Es una premisa defendible
   —y de hecho refuerza el punto—, pero es una premisa: hay que enunciarla, no
   apoyarse en «Landauer» como comodín.

**Falsador / criterio de contraste.** Si se exhibiera un régimen de transición entre
descripciones que sea (a) informacionalmente reversible y (b) útil para regular, el
costo de la transición dejaría de ser estructural y la geodésica perdería su motor.

**Reapariciones**
- *nota-09*: **paga dos de las tres deudas de arriba, en una sola nota.**
  - *Deuda 1 (sin métrica ni conexión):* saldada en candidatura — se propone la
    **métrica de Fisher** sobre el espacio de descripciones, que trae conexión y escala
    de curvatura no arbitraria ([[metrica-de-fisher-espacio-de-perspectivas]]).
    «Geodésica» empieza a ser un término legítimo y no un préstamo. Queda por fijar
    **cuál** conexión (la trampa de las α-conexiones) y por decidir la parametrización
    ([[parametrizacion-de-t-blanda-vs-grassmanniana]]).
  - *Deuda 2 («residuo» sin definir):* saldada o casi — la nota fija el espacio muestral
    (un canal con pérdida p(t | x; θ) que comprime el estado de la red en lo que el
    observador finito puede sostener), y con eso **residuo = distorsión D**. «Pago por
    unidad de residuo resuelto» se vuelve una relación entre R(D) y D, es decir, la
    curva de tasa-distorsión. Ver [[compresion-con-perdida-y-tasa-distorsion]].
  - *Deuda 3 (Landauer acota el borrado):* **queda mejor que saldada** — una compresión
    con pérdida *es* descarte de información por definición, así que la premisa que en
    la nota 08 había que pedir prestada, aquí se cumple sola.
  - *Y una deuda nueva:* la nota deja fuera del formalismo la **relevancia** (al elegir
    compresión y no predicción, nada dice qué vale la pena conservar). El
    *information bottleneck* queda señalado como el lugar donde entraría.

**Veredicto de recurrencia**: recurrente (notas 08 y 09). Estatuto: pasa de **programa
de formalización abierto** a **formalización en curso con candidatos concretos** — el
avance más rápido de cualquier unidad del corpus (dos notas, el mismo día).
