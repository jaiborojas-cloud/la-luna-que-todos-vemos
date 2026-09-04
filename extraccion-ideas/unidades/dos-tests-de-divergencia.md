---
titulo: Los dos tests de divergencia (artefacto de carta vs. curvatura real)
estado: en desarrollo
primera_aparicion: notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
apariciones:
  - notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
pensadores_relacionados: [Tullio Levi-Civita (transporte paralelo), Élie Cartan, Bernhard Riemann, Shun'ichi Amari (geometría de la información), Michael Berry (fase geométrica)]
resumen: >
  Resuelve la ambigüedad que arruinaba el criterio de la nota 08. La divergencia entre
  cartas vecinas podía significar dos cosas opuestas —(a) estructura real no capturada
  por el atlas, o (b) una carta rompiéndose— y el desacuerdo por sí solo no las
  distinguía. La resolución no añade un criterio: **nota que «vecinas» significa dos
  cosas distintas, con dos tests distintos**. *Test A (mismo punto, dos cartas):* si el
  gradiente de relevancia es un covector genuino, su expresión en una carta se obtiene
  de la otra vía el jacobiano de la transición, **exactamente**; si el pullback no
  coincide más allá del ruido numérico, hay un objeto o una carta rota — no hay señal.
  *Test B (puntos distintos y cercanos):* comparar covectores en puntos distintos exige
  una conexión, y la divergencia **residual después de transportar bien** es la
  holonomía: curvatura real, señal genuina. Los casos (a) y (b) no compiten por el
  mismo test.
---

Es la reparación del [[desacuerdo-entre-cartas-vecinas]], y una reparación de la clase
más limpia: **no parchea, disuelve**. El criterio de la nota 08 era «la divergencia
entre vecinas es la alarma»; el problema es que una alarma que suena por dos causas
opuestas —el mundo cambió / mi instrumento se rompió— no es una alarma, es ruido. Al
separar los dos sentidos de «vecindad» (misma posición en distinta coordenada vs.
posiciones distintas), cada causa cae en un test propio y el diagnóstico se vuelve
determinado.

**Consecuencia inesperada y valiosa: el Test A no es una señal, es un test unitario.**
«Nunca debería divergir en un atlas bien construido» lo convierte en control de
integridad del propio aparato, no en información sobre el mundo. Eso reasigna la mitad
del criterio original de la nota 08 —la mitad ambigua— a la categoría de *depuración*.
Es una pérdida aparente que es una ganancia real: lo que queda como señal (Test B) es
inequívoco.

**Rehabilitación parcial de la holonomía.** El Test B *es* la holonomía que la nota 08
había degradado a analogía en [[holonomia-y-memoria-como-torsion]] — pero ahora con lo
que allí faltaba: una conexión de verdad, heredada de la métrica (ver
[[metrica-de-fisher-espacio-de-perspectivas]]). El ciclo del corpus queda cerrado:
intuición (08) → refutación honesta (08) → objeto matemático real (09). Vale la pena
notar que la versión que vuelve es **más modesta y más útil** que la original: ya no
pretende derivarse de la irreducibilidad computacional, solo mide lo que mide.

**La escala de vecindad deja de ser un parámetro libre** (§3 de la nota). El radio
válido para el Test B es aquel donde la aproximación de primer orden del transporte
paralelo sigue siendo confiable: radio de inyectividad / escala de curvatura local. No
se tunea, se deriva. Esto salda directamente el flanco que
[[desacuerdo-entre-cartas-vecinas]] había dejado abierto («qué cuenta como vecina»).

**Cautela epistémica (regla de oro).**
- *Demostrable (geometría diferencial estándar):* que un covector se transforma por el
  jacobiano de la transición; que comparar vectores en puntos distintos exige una
  conexión; que la holonomía de un lazo mide curvatura. Nada de esto es tesis propia —
  es maquinaria conocida, correctamente aplicada. **Ese es justamente su valor:** el
  proyecto pasa de vocabulario prestado a uso legítimo.
- *Tesis:* que el objeto regulatorio relevante (el gradiente de relevancia) **sea** un
  campo covectorial. Es un supuesto fuerte y explícito — ver
  [[relevancia-como-gradiente-local]], que la nota 09 actualiza.
- *Precisión menor:* la escala útil está acotada por el **mínimo** entre el radio de
  inyectividad y el radio de curvatura ‖R‖^(−1/2); la nota los menciona como
  alternativas, y conviene fijar cuál manda.
- **Deuda nueva, y es seria — el costo de la señal.** El atractivo del criterio en la
  nota 08 era que fuera *barato y local*: unas cartas burdas y una comparación. El Test
  B es más caro: exige la conexión, es decir, estimar la métrica y sus derivadas.
  Sigue siendo local (la información de Fisher es estimable localmente), pero la
  curvatura pide **segundas derivadas** de la métrica, y eso se paga. Como todo el
  edificio descansa en un presupuesto finito (L2), **hay que mostrar que la señal vale
  su precio** — que el sistema puede costear el instrumento con el que detecta que su
  descripción se degrada. Si no puede, la geometría es correcta y el regulador
  igualmente ciego. Esta pregunta no está resuelta y es la más importante que abre la
  nota 09.

**Veredicto de recurrencia**: ocurrencia única (nota 09), pero es la pieza que convierte
la capa regulatoria en la capa **geométrica** del corpus.
