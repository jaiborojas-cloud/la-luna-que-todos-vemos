# Hoja de ruta — Obra derivada (ontología relacional)

> **Para quien retome esto (tú o una sesión futura de Claude):** empieza por
> aquí. Este archivo dice en qué punto está la obra derivada, qué se decidió ya
> (para no re-discutirlo) y cuáles son los caminos naturales a seguir, en orden.
> El texto fundacional es `00-documento-puente.md`, en esta misma carpeta.

Última actualización: 2026-11-05.

---

## 1. Cómo retomar en 60 segundos

El proyecto tiene **tres piezas** dentro del repo `La-Luna-Que-Todos-Vemos`:

| Pieza | Dónde | Qué es |
|---|---|---|
| **Obra original** | `capitulos/`, `docs/`, `recursos/`, `CLAUDE_CONTEXT.md` | *La Luna Que Todos Vemos* / MENTEMONEDA. Neuro-poético-existencial. Ya escrita (parcial). |
| **Repo-herramienta** | `extraccion-ideas/` | Extracción de ideas que alimenta a las dos obras. NO es una obra. Ver sus `indice.md` (notas) e `indice-obra.md` (obra). |
| **Obra derivada** | `ontologia-relacional/` ← *estás aquí* | La obra "más rigurosa". Fundada en `00-documento-puente.md`. En estado embrionario. |

**Estado de la obra derivada:** existe su columna argumentativa (el documento-
puente, **v2**, con los caminos A y E integrados) y esta hoja de ruta. **No hay
capítulos, ni estructura de libro, ni prosa desarrollada todavía.** El siguiente
trabajo es I.0 del Camino I (§4).

---

## 2. Decisiones ya tomadas (NO re-litigar sin motivo)

1. **Son dos obras distintas, casi disjuntas.** En el cruce original (16
   unidades de notas vs. la obra) solo 4 aparecían en la obra; la separación de
   registros se mantiene como decisión de trabajo. La derivada es
   *sistémica/epistémica*; la original es *neuro-poético-existencial*.
2. **El puente entre ambas es la metáfora de la moneda**, con la precisión de E:
   abstracta en las notas (`mente-como-denominacion-moneda-cognitiva`), encarnada
   en la obra (`pago-metabolico-de-la-conciencia`); sirve para patologías de
   circulación, no para la singularidad.
3. **Registro de la obra derivada: filosófico riguroso.** Argumentación formal,
   citas reales, y la regla de oro (abajo).
4. **La obra derivada vive en carpeta propia** (`ontologia-relacional/`), separada
   del repo-herramienta de extracción.
5. **La extracción se reabre solo con material nuevo.** Estado actual: **9 notas**
   (las notas 04–07 la reabrieron el 2026-08-17; las notas 08–09 entraron el
   2026-09-04) → **36 unidades** (25 en el núcleo). Cerrada de nuevo hasta que
   llegue material fresco.

## 3. Reglas permanentes del proyecto

- **Regla de oro (rigor):** toda afirmación se marca como **literal** /
  **demostrable** / **tesis argumentada** / **analógica**. Ninguna puede citarse
  con el estatuto de otra. (Ver las tablas del §6 del documento-puente.)
- **La moneda ilumina, no demuestra.** Conserva valor para describir
  *patologías de circulación* (atesoramiento, concentración, bloqueo); se retira
  para la *singularidad* de la perspectiva, porque la fungibilidad del dinero
  contradice la tesis. Ver documento-puente §5.2.
- **Los commits los hace el usuario, a mano.** Claude no commitea salvo que se le
  pida explícitamente.
- **No proponer estructura de libro / capítulos** hasta que la columna
  argumentativa esté sólida y verificada (es decir, hasta cerrar buena parte del
  §4).
- **Verificar antes de publicar:** las referencias del documento-puente están
  **parcialmente cotejadas** (A/E, 2026-10-20); falta la pasada final de
  ediciones, páginas y formulación exacta antes de publicación.

---

## 4. Caminos naturales a seguir (en orden de prioridad)

Cada camino es independiente; pueden tomarse de a uno. El "criterio de hecho" dice
cuándo considerarlo terminado.

### Camino A — Formalizar la bisagra inferencia activa → "buen regulador" ✅ acotado (2026-10-20)
- **Resultado:** la ruta robusta **no** pasa por Conant-Ashby ni por el FEP: es
  **variedad + finitud (L1a + L2)**. L2 no es una obstrucción aparte: es la
  premisa que hace finito al sistema y habilita el conteo. El «buen regulador»
  queda como corroboración débil (homomorfismo con pérdida sobre el sistema
  externo); el FEP, como marco debatido.
- **C1 acotada:** lo abierto es (a) el **Paso 2** —deber regular un todo que
  incluye al agente— y (b) el refinamiento **L2 ⇒ finitud**.
- **Dónde toca:** documento-puente §2, §3 y §7.1; archivo
  `A-bisagra-inferencia-activa-buen-regulador.md`.
- **Criterio de hecho:** cumplido en su forma robusta; quedan las dos tesis
  nombradas.

### Camino B — Desarrollar el "nudo" como primer capítulo real
- **Qué:** convertir el §3 del documento-puente (micro y macro son el mismo
  límite: termodinámica ↔ lógica) en un capítulo completo y autónomo.
- **Por qué:** es el corazón conceptual y el mejor punto de entrada al libro;
  obliga a poner a prueba la claridad de la tesis central.
- **Dónde toca:** nuevo archivo `ontologia-relacional/01-el-nudo.md`.
- **Criterio de hecho:** un capítulo que un lector filosófico pueda leer solo y
  seguir el argumento sin haber leído las notas.
- **Depende de:** A ✅; conviene tener I.0/I.1 antes de escribir el capítulo.

### Camino C — Verificar y afinar las referencias ✅ quirúrgico (2026-08-17; ampliado 2026-10-20)
- **Qué:** cotejar con búsqueda web / fuentes las citas del documento-puente
  (ediciones, páginas, formulación exacta). Prioridad: **Conant-Ashby (1970)** y
  **el alcance real que Friston reclama** para el principio de energía libre
  (marco influyente pero debatido).
- **Por qué:** el rigor prometido exige que las fuentes resistan escrutinio.
- **Hecho:** Conant-Ashby (páginas 89–97, DOI y forma débil); Friston/FEP
  contestado; Virgo et al. 2025; Bruineberg et al. 2022; Colombo & Wright 2021;
  Wentworth 2021 (no arbitrado). Queda la pasada final de ediciones y páginas
  antes de publicación.
- **Dónde toca:** documento-puente, sección "Referencias" y nota de verificación.
- **Criterio de hecho:** cada referencia con edición/página confirmada y cada
  atribución con su formulación exacta. **Parcialmente cumplido:** las citas
  nuevas de A/E están cotejadas; falta la revisión final del resto.

### Camino D — Precisar "emergencia" de la realidad compartida
- **Qué:** dar un criterio operacional que distinga la realidad compartida
  emergente de un simple promedio estadístico de percepciones.
- **Por qué:** hoy "emergencia" hace trabajo pesado sin definición fuerte (§7.2).
- **Dónde toca:** documento-puente §4; unidad `conocimiento-distribuido`.
- **Criterio de hecho:** una definición que permita decir qué contaría como
  contraejemplo.

### Camino E — Poner a prueba la propia metáfora monetaria ✅ hecho (2026-08-17)
- **Resultado:** la metáfora tiene **dos usos**: sirve como vocabulario para
  *patologías de circulación* (atesoramiento, concentración, bloqueo); **no**
  sirve para la *singularidad* (la fungibilidad del dinero contradice los frutos
  únicos). Hallazgo fuerte: la **ontología relacional es marco, no tesis
  predictiva**; §3 no la usa, la relacionalidad interpreta río abajo.
- **Dónde toca:** documento-puente §5, §6.2 y §7.4; archivo
  `E-prueba-de-la-metafora-y-del-marco.md`.
- **Criterio de hecho:** cumplido; la frontera queda declarada en §5.2 y §6.2.

### Camino F — La conciencia (dejar como pregunta abierta, gestionada)
- **Qué:** NO resolver por metáfora. Mantener y desarrollar las vías de
  `circulacion-consciente-pregunta-abierta` como problema abierto declarado.
- **Por qué:** el documento explica incompletud y distribución, no *por qué hay
  experiencia*. Colarlo por analogía rompería la regla de oro.
- **Dónde toca:** documento-puente §7.5; unidades `circulacion-consciente-...`,
  `conciencia-como-forma-de-relacion`.
- **Criterio de hecho:** que siga marcado como abierto y no se contamine con los
  otros pisos.

### Camino G — Situarse frente a la literatura ★ prioridad alta
- **Qué:** posicionar el proyecto frente a los vecinos más cercanos y decir, para
  cada uno, *en qué coincide y en qué se separa*. Mínimo obligado: **Simondon**
  (la relación precede a los términos), **Karen Barad** (los relata no preexisten
  a las relaciones), **Thomas Metzinger** (*Being No One*: no hay self completo,
  solo un modelo fenoménico del self — el vecino más cercano), **Ladyman & Ross**
  (realismo estructural óntico), **Luhmann** (punto ciego del sistema que se
  auto-observa), **Whitehead**, **Hofstadter** (*strange loops*) y **Nāgārjuna**
  (originación dependiente). Simmel ya está en el documento-puente.
- **Por qué:** cada pilar del proyecto (relación primaria, límites del
  autoconocimiento, cognición distribuida, cerebro predictivo, moneda relacional)
  ya está muy poblado. La originalidad NO está en los ladrillos, solo en la
  construcción. Sin este posicionamiento, el primer lector informado desarma el
  proyecto como "otra versión de la ontología relacional". Con él, se vuelve *tu*
  ontología relacional. Es además insumo directo del Camino E (qué añade tu
  versión = §7.6).
- **Dónde toca:** nuevo archivo `ontologia-relacional/02-estado-de-la-cuestion.md`;
  retroalimenta documento-puente §5 y §7.6.
- **Criterio de hecho:** para cada autor/tradición, una línea "coincide en X / me
  separo en Y", y una frase final que nombre el diferencial propio.
- **Estado (2026-11-05):** hecho en `02-estado-de-la-cuestion.md` (v1.0).
- **Pendiente — tipología de convergencias.** El proyecto mira dónde se unen
  contextos; no busca una teoría única. Para que el mapa distinga puentes que
  soportan peso de palabras parecidas, se proponen tres tipos: **estructural**,
  **estructural condicional** y **resonancia**. **Quedan registrados sin
  aplicar** hasta encontrar criterios que los definan. Candidato a criterio, sin
  adoptar: una convergencia es estructural si existe una traducción entre los dos
  contextos que preserve algo no verbal (un teorema, una cantidad, una
  predicción); análogo al test de consistencia del mapa de transición de la nota
  09.

### Camino H — Hacer explícito el salto intra→inter-sistema ★ prioridad alta
- **Qué:** distinguir el argumento *intra-cerebro* (la economía interna de un
  sistema cognitivo: por qué no puede auto-modelarse) del argumento *inter-cerebro*
  (una red social de sistemas: por qué el conocimiento colectivo se distribuye), y
  luego articular bajo qué condiciones el segundo *hereda* al primero — sin usar
  "sistema" como comodín que los confunde.
- **Por qué:** es la costura **C3** del §3 del documento-puente y el salto sobre el
  que se apoyan los pasos 4–5 de la derivación (relacionalidad y moneda). Es la
  contraparte social del Camino A (que es intra-sistema). Hoy no estaba ni siquiera
  listado como paso: era el eslabón invisible.
- **Dónde toca:** documento-puente §3 (C3) y §5; posible nuevo archivo o sección.
- **Criterio de hecho:** un argumento que diga con precisión *qué* del límite
  individual se transfiere a lo colectivo y *qué no*, y por qué.
- **Estado (2026-11-05): primera versión hecha** en
  `ontologia-relacional/H-salto-intra-inter-sistema.md`. Abierto: agencia
  colectiva (trabajo futuro, con criterio de hecho: variables esenciales,
  regulación e irreductibilidad a un nodo, aplicados a un caso concreto); costo de
  verificar frente a producir; ritmo de regeneración de diversidad.

### Camino I — De la imposibilidad a la regulación (perspectividad dinámica) ★ prioridad alta
- **Abierto por:** la nota 08 (2026-09-04), «Curvatura sin métrica».
- **Qué:** el Camino A termina en un resultado **negativo** (el auto-modelo completo es
  imposible → la perspectiva es forzada). Este camino da el paso siguiente: **qué
  régimen de regulación se sigue de esa imposibilidad**. La respuesta propuesta es la
  *perspectividad dinámica* — si no puedes tener la vista completa, desplaza
  sistemáticamente la que tienes — con tres piezas: hacia dónde (relevancia como
  gradiente local), cuándo (desacuerdo entre cartas vecinas) y a qué precio (pago
  disipativo por transición).
- **Por qué:** es lo único del material reciente que produce **argumento y no marco**
  —el test del Camino E—, y es el primer contenido *positivo* del proyecto. Todo lo
  demás hasta ahora dice qué no se puede; esto dice qué sí, sin violar lo anterior.
- **Insumos ya escritos:** `unidades/perspectividad-dinamica.md`,
  `relevancia-como-gradiente-local.md`, `desacuerdo-entre-cartas-vecinas.md`,
  `espacio-de-descripciones-y-geodesicas.md`, `holonomia-y-memoria-como-torsion.md`.
- **Dónde toca:** nuevo archivo `ontologia-relacional/I-perspectividad-dinamica.md`;
  retroalimenta el §3 del documento-puente (la derivación gana un paso 0': de la
  parcialidad forzada al desplazamiento obligado) y el §7.1.

Se divide en dos ramas con prioridades muy distintas — **no confundirlas**:

La nota 09 cambió el orden interno de este camino. Lo que estaba aparcado (formalizar
D) recibió candidatos concretos el mismo día en que se abrió, así que el camino se
reorganiza en **tres sub-pasos, y el primero es una prueba de humo barata que puede
matar a los otros dos**. Hacerla antes que nada.

- **I.0 — La prueba de humo: ¿la curvatura es distinta de cero?** (★ hacer primero,
  es corto). Todo el Test B —y con él la rehabilitación de la holonomía— depende de que
  el espacio tenga curvatura. Hay **dos maneras de que devuelva cero en silencio**, las
  dos detectadas al revisar la nota 09:
  1. **Conexión mal elegida.** «Fisher da una conexión canónica» es ambiguo: la
     geometría de la información trae la familia de α-conexiones de Amari, y las dos
     más naturales para familias exponenciales (α = ±1, exponencial y de mezcla) son
     **planas** — holonomía trivial por construcción. Hay que usar la **Levi-Civita**
     de la métrica de Fisher (α = 0), y dejarlo escrito.
  2. **Parametrización mal elegida.** El modelo de **Bernoullis independientes** de la
     opción (1) del §7 de la nota es **plano para todo N**: una Fisher diagonal cuyo
     `g_ii` depende solo de `θ_i` es una métrica producto de variedades de dimensión 1;
     con `u_i = 2·arcsin(√θ_i)` queda `g = Σ du_i²`, euclidiana sobre la caja (0,π)^N.
     Riemann ≡ 0, holonomía trivial, **Test B ≡ 0**. Esto responde por cálculo la
     pregunta que la nota dejaba para «un ejemplo de 3–4 relaciones»: no hace falta el
     ejemplo, la opción (1) tal como está escrita queda descartada para sostener el
     test.
  **La lectura conceptual del cálculo es el hallazgo, no el cálculo:** la curvatura
  viene de la **dependencia entre relaciones**. Bernoullis independientes = relaciones
  que no se enteran unas de otras = espacio plano = ninguna señal. Modelar las
  relaciones como interruptores independientes es, literalmente, aplanar la ontología
  del proyecto. **Criterio de hecho:** una decisión escrita sobre conexión y
  parametrización, con la curvatura verificada no nula. Ver
  `unidades/parametrizacion-de-t-blanda-vs-grassmanniana.md`, donde queda además
  propuesta una tercera opción que no estaba en la nota —**Bernoulli con
  acoplamientos** (tipo Ising / campo aleatorio de Markov)—: conserva la lectura
  literal «relaciones más o menos activas» *y* recupera la curvatura, al precio de que
  la Fisher deje de ser diagonal.
- **I.1 — El mecanismo de recalibración.** Desarrollar los *dos tests* como mecanismo
  completo: cuántas cartas, cómo se generan, qué umbral de divergencia dispara el
  desplazamiento y —lo más importante— **quién paga la señal**. El atractivo original
  del criterio era ser barato; el Test B exige métrica, conexión y segundas derivadas.
  Como todo el edificio descansa en presupuesto finito (L2), hay que mostrar que el
  regulador **puede costear el instrumento con el que detecta que se degrada**. Si no
  puede, la geometría es correcta y el regulador igualmente ciego. **Criterio de
  hecho:** una especificación implementable y refutable, más el párrafo que declara el
  precedente (query by committee, desacuerdo de ensambles como incertidumbre
  epistémica) y dice en qué se separa el proyecto — que es en *derivarlo* de una
  restricción termodinámico-estructural en vez de adoptarlo como heurística.
- **I.2 — Cerrar el formalismo.** Con I.0 resuelto, terminar de fijar el objeto: la
  métrica de Fisher sobre el canal con pérdida p(t | x; θ), el residuo como distorsión
  D, la relación entre R(D) y el pago, y **la que falta**: el *information bottleneck*,
  que dejó de ser «extensión futura» para volverse necesario — al elegir compresión y
  no predicción, la nota 09 dejó la **relevancia fuera del formalismo**, y sin variable
  relevante nada dice qué vale la pena conservar.

**Deudas honestas del camino (dejarlas a la vista, no taparlas):**
1. **La premisa de no-estacionariedad.** «Hay que desplazarse» solo se sigue si el
   entorno o el sistema cambian. En un mundo estacionario, quedarse quieto puede ser
   óptimo. Sigue **sin enunciarse en ninguna nota**: es el flanco más barato de tapar y
   el más caro de que te lo encuentren.
2. **El costo de la señal** (ver I.1). Es hoy la pregunta abierta más importante del
   camino.
3. **Φ/IIT entró por la puerta lateral.** La nota 09 declara de pasada que la variable
   ontológica de la obra «es Φ/IIT», y **eso no está documentado en ningún archivo del
   repo**. Es un compromiso caro (teoría en disputa activa; Φ intratable de calcular) y
   adoptarlo como subproducto de una decisión técnica sobre métricas roza justo lo que
   el **Camino F** prohíbe. Decidirlo de frente o degradarlo a *place-holder declarado*
   («una medida de integración causal, de la cual Φ es un candidato»).
4. **Chentsov, con su salvedad.** «La única métrica invariante bajo estadísticos
   suficientes» vale **salvo escala y sobre el símplex finito**. El proyecto ya asume
   finitud en todas partes, así que la salvedad cuesta poco y compra rigor — pero hay
   que escribirla.
5. **Idealización de tasa-distorsión.** R(D) es el mínimo asintótico para codificación
   por bloques de una fuente estacionaria sin memoria; un observador finito y singular
   no habita ese régimen y paga más.
6. **Óptimos locales.** El gradiente local hereda la tensión exploración/explotación y
   no la resuelve; las cartas vecinas la alivian, no la cierran.

*Deudas ya saldadas por la nota 09, para no re-litigarlas:* D sin métrica (Fisher
candidata); «residuo» sin definir (= distorsión D); Landauer acota el borrado (una
compresión con pérdida *es* descarte, la premisa se cumple sola); «qué cuenta como
vecina» (radio de inyectividad / escala de curvatura, derivado y no tuneado).

### Orden sugerido
**A ✅ → C ✅(quirúrgico) → E ✅ → [integrar A y E al puente] ✅ (2026-10-20) →
I.0 → I.1 + G + H → I.2 → B → D**, con **F** como restricción permanente (no un
paso).

- **Pendiente inmediato:** **I.0** (prueba de humo de curvatura). La integración
  A/E ya está hecha (rama `integracion-a-e`); el §3 del puente incorpora la ruta
  L1a + L2 y el perímetro C1–C3 está declarado.
- **I.0 va antes que todo lo demás del camino I** y es corto. No construir encima sin
  haber verificado que la curvatura no es cero.
- **I.1, G y H pueden ir en paralelo.** H sigue siendo la contraparte social de A.
- **G se vuelve claramente más urgente con este lote:** las unidades nuevas tienen
  vecinos muy poblados y muy citables (Vervaeke en *relevance realization*, la
  inferencia activa en acción epistémica, el desacuerdo de ensambles en aprendizaje
  automático, y ahora **toda la geometría de la información** — Amari, Chentsov,
  Efron). El diferencial defendible no es haber inventado estas herramientas, sino
  **derivar su necesidad desde una restricción termodinámico-estructural**. Si el
  proyecto no lo declara así, el primer lector informado lo hará por él.
- B, D e I.2 se benefician de tener lo anterior hecho.

> **Reencuadre de la ambición (2026-07-31):** el objetivo NO es "una filosofía
> nueva" (los pilares ya existen), sino **(a)** una síntesis con voz propia,
> **(b)** un argumento-puente concreto que se sostiene o no (Camino A), y **(c)**
> una obra literaria singular (la original, `capitulos/`). Ese encuadre es
> defendible; "nueva filosofía" expone el proyecto a ser desarmado. Ojo: la obra
> *original* puede ser más original —como literatura filosófica— que la derivada;
> no dejar que la derivada le robe la energía.

---

## 5. Índice rápido de archivos (para no buscar)

- `ontologia-relacional/00-documento-puente.md` — tesis vertebral (leer primero).
- `ontologia-relacional/HOJA-DE-RUTA.md` — este archivo.
- `extraccion-ideas/indice.md` — 36 unidades de las notas (25 de núcleo).
- `extraccion-ideas/indice-obra.md` — 16 unidades de la obra original.
- `extraccion-ideas/unidades/` y `unidades-obra/` — las unidades individuales.
- `extraccion-ideas/notas-crudas/` — las 10 notas fuente.
- `ontologia-relacional/02-estado-de-la-cuestion.md` — Camino G.
- `ontologia-relacional/H-salto-intra-inter-sistema.md` — Camino H.
- `ontologia-relacional/A-bisagra-inferencia-activa-buen-regulador.md` — Camino A.
- `ontologia-relacional/E-prueba-de-la-metafora-y-del-marco.md` — Camino E.

## 6. Bitácora (añadir una línea por sesión, lo más reciente arriba)

- **2026-11-05 (Camino H, rama `camino-h-salto-intra-inter`)** — Creado
  `H-salto-intra-inter-sistema.md`. Tres preguntas en lugar del comodín
  «sistema»: el **límite de copia se hereda** (sin Paso 2); el **deber de regular
  no se hereda** (perspectiva colectiva solo si la red es agente); el **límite de
  evaluación se transforma** en asimetría (Wolpert). Cinco condiciones para que la
  red funcione como red de verificadores (diversidad, asimetría verificar /
  producir, código común, costo pagable, puntos ciegos no correlacionados). Tensión
  central: **la circulación erosiona la diversidad** (March 1991, Zollman 2010), así
  que una red distribuida persiste solo si la regenera; «no repetir» como condición
  de persistencia; la fungibilidad como patología por exceso. Documento-puente a
  **v2.4**.

- **2026-11-05 (Camino G, rama `camino-g-estado-de-la-cuestion`, PR #4)** —
  Creado `02-estado-de-la-cuestion.md` (v1.0): tiempo relacional en tres capas
  (región literal; contenido vía RQM, declarado; acuerdo como postulado), con la
  gramática relacional asignada a MENTEMONEDA; corolario de evaluación y sus
  vecinos; los ocho vecinos de G más **Breuer (1995)** y **Wolpert (2008)**,
  antecedentes directos del núcleo. Documento-puente a **v2.3**: el plano cabe, la
  evaluación no (§2.4); RQM solo en la capa de contenido (§5.1); el §3 reclama la
  construcción, no los ladrillos; **Luhmann aceptado y derivado** (solo circula lo
  comprimible) y criterio de C3 corregido: *se hereda el pasado común; los
  resultados circulan; la evaluación no viaja*. Abierta la **nota 10** (plano +
  módulo de evaluación; ¿cómo nace un nodo con una capacidad nueva?) para el
  **Camino H**.

- **2026-10-20 (integración A/E al documento-puente)** — Trabajo en la rama
  `integracion-a-e` (worktree separado; `main` local con el commit de
  normalización `0a9fdfd`, sin push):
  - **Normalización:** `.gitattributes` (`* text=auto eol=lf`); 88 archivos de
    texto en LF; commit `0a9fdfd` en `main` (local).
  - **§2–§3 (commit `c73d8a4`):** el nudo se reescribe sobre **L1a (conteo) +
    L2 (finitud/costo)**; L1b (regreso) queda como respaldo. L2 es **premisa**
    de L1a, no obstrucción paralela. El motor «deber regular × no poder
    completar → perspectiva» da el paso 1 ganado. Conant-Ashby se degrada a
    corroboración débil; el FEP queda como marco debatido. C1 acotada: quedan
    Paso 2 y L2 ⇒ finitud.
  - **§5–§8 y referencias (commit `d4859a4`):** §5 declara la ontología
    relacional **marco**, no tesis predictiva; la moneda pasa a herramienta de
    dos usos (patologías de circulación sí; singularidad no); §6 se divide en
    Proyecto A (argumento) y Proyecto B (marco/metáfora); §7 reordena la agenda
    (C1 residual, C2, C3, moneda, conciencia, literatura); §8 y referencias
    actualizadas (Conant-Ashby DOI/páginas, Virgo et al. 2025, Bruineberg et
    al. 2022, Colombo & Wright 2021, Wentworth 2021).
  - **Conteos:** 9 notas / 36 unidades / 25 núcleo. **Siguiente:** I.0.

- **2026-08-17 (sesión de Caminos E → A → C)** — Tras el lote 04–07 se hicieron tres
  cosas, todas en archivos nuevos de `ontologia-relacional/` (el documento-puente NO
  se tocó; pendiente de integrar tras revisión del usuario):
  - **Camino E hecho** (`E-prueba-de-la-metafora-y-del-marco.md`). Veredicto en dos
    niveles: (1) la **metáfora de la moneda** se degrada de columna a herramienta de
    dos usos —sí para *patologías de circulación*, no para *singularidad* (la
    fungibilidad del dinero contradice los frutos únicos)—; (2) hallazgo fuerte: **la
    ontología relacional es MARCO, no tesis predictiva** — el §3 (lo que tiene dientes)
    NO usa la relacionalidad; la relacionalidad *interpreta* río abajo. Lo único que el
    marco prohíbe —«no hay conocimiento sin perspectiva»— es el mismo diente de §3.
    Diagnóstico: el lote 04–07 era casi todo *marco* (dilución), salvo la
    entropía-costo (rescate para §3/A) y el gancho «orden ≠ justicia».
  - **Camino A redactado y reequilibrado** (`A-bisagra-inferencia-activa-buen-regulador.md`).
    Primero se montó sobre buen regulador (Conant-Ashby) + FEP; la verificación
    (abajo) los debilitó, así que se **reescribió apoyándolo en variedad + finitud
    (L1a + L2)**, que NO necesitan ni el teorema ni el FEP. Núcleo: *deber-regular ×
    no-poder-completar (parte finita < todo auto-inclusivo) = parcialidad forzada =
    perspectiva*. **Refinamiento nuevo del nudo:** L2 no es obstrucción aparte de L1 —
    su finitud *habilita* el argumento de conteo (energía finita ⇒ estados finitos);
    endurece la composición del §3. El diamante «perspectivismo por imposibilidad» se
    conserva sobre pierna firme.
  - **Camino C (quirúrgico) hecho** para A. Verificado contra fuentes: (a) el teorema
    del buen regulador es **más débil que su eslogan** (solo *algunos* óptimos son
    modelos; homomorfismo *con pérdida*; sobre el sistema *externo*, no el yo) → se
    jubiló como pilar; (b) **P2 (FEP↔buen regulador) lo sostiene Friston pero está
    contestado**, y el «modelo» puede ser *atribuido por un observador* (Virgo, Biehl,
    Baltieri & Capucci 2025) — amenaza que resultó **aliada** del perspectivismo; (c)
    FEP «influyente pero debatido», confirmado. Fuentes en el §7 del archivo A.
  - **Pendiente inmediato (próxima sesión):** integrar A y E al documento-puente
    (reescribir §2, §3, §5, §6, §7.1 según el §5 del archivo A y el cierre de E). NO
    hecho aún — requiere revisión del usuario.
  - **Reencuadre reforzado:** hay dos proyectos y no hay que confundirlos — (A) la
    contribución rigurosa = **§3, la composición L1×L2** (object-compatible, casi
    novedosa: es *el* activo); (B) la síntesis generativa / obra. La ontología
    relacional y la moneda son **marco y voz de B**, no argumento de A. Antídoto fijado:
    ante cada idea nueva preguntar *«¿marco o argumento? ¿qué prohíbe?»*.
- **2026-08-17 (cierre del lote 04–07)** — Procesadas las **notas 05, 06 y 07**
  además de la 04. Corpus: 3 → **7 notas**, 16 → **27 unidades**, núcleo 6 → **18**.
  Añadida una **capa físico-informacional** entera: cristales del tiempo + Whitehead
  ([`ontologia-de-procesos`], [`cristales-del-tiempo`]), Wolfram/hipergrafos
  ([`universo-computacional-wolfram`]), entropía y su reverso
  ([`entropia-como-variable-relacional`], [`neguentropia-exploracion-y-compresion`]) y
  su bajada aplicada ([`economia-biomimetica-y-limites-a-la-concentracion`]). **Dos
  hallazgos:** (1) la nota 06 da carne a la **costura termodinámica L2** (`entropía` =
  costo físico del auto-modelado → material directo del **Camino A**) y es el puente
  abstracto con `pago-metabolico-de-la-conciencia` de la obra. (2) La nota 07 **cruzó
  el eje físico-informacional nuevo con el económico-sistémico de la nota 02**
  (eguentropía ↔ cáncer/monopolios), ascendiendo 4 unidades al núcleo. **Riesgos
  vivos:** toda la capa nueva es la más especulativa del corpus (modelo E=ln|R| sin
  definir; «principio de conservación relacional» que no conserva; analogía
  vida/agujeros negros; falacia is→ought en la economía biomimética; «ilusión de
  convergencia» Rovelli/Whitehead/Wolfram). Cada unidad quedó con su nota de cautela.
  **No integrar al documento-puente sin pasar por A/D/E/H.** Próximo paso natural:
  Camino A (ahora con insumo termodinámico real) o Camino E (test de honestidad, que
  la capa nueva vuelve urgente).
- **2026-08-17** — **Reabierta la extracción** (revierte la decisión §2.5) con la
  **nota 04** («Realidad Relacional, Información y Conciencia»). Añadidas **5 unidades
  nuevas** (`interpretaciones-relacionales-de-lo-cuantico` [QBism/RQM],
  `ontologia-informacional`, `ley-de-relaciones-productivas`,
  `meta-red-memoria-estadistica`, `capas-de-emergencia-relacional`) y promovidas al
  núcleo `conciencia-como-forma-de-relacion` y `circulacion-consciente-pregunta-abierta`
  (ahora 2 apariciones). Total: 16 → **21 unidades**; núcleo 6 → **8**. La nota 04
  aporta **anclaje físico** que faltaba (Rovelli/QBism → alimenta Caminos C y G) y una
  **definición operacional de conciencia** («red que modela sus propias relaciones»).
  **Advertencia:** su capa físico-informacional es la más especulativa —ley evolutiva
  cosmológica y «memoria estadística del universo» rozan la infalsabilidad—; cada
  unidad quedó con nota de cautela epistémica y son material directo del **Camino E**
  (test de honestidad) y del **Camino H** (salto intra→inter-sistema). *No* integrar
  esto al documento-puente sin pasar antes por A/E/H.
- **2026-07-31** — Desarrollado a fondo el **§3** del documento-puente: las dos
  obstrucciones (L1 lógico-estructural, L2 termodinámica) **se componen** (regreso
  × costo = impagable), imagen mapa/territorio, y las **cuatro costuras C1–C4**.
  Añadido el **Camino H** (salto explícito intra→inter-sistema = costura C3), antes
  invisible. El núcleo robusto del aporte = sobredeterminación + composición L1×L2;
  el perímetro por demostrar = C1 (Camino A), C2 (Camino D), C3 (Camino H).
- **2026-07-31** — Añadido el **Camino G** (situarse frente a la literatura) y el
  **reencuadre de la ambición** (síntesis + argumento-puente + obra literaria, no
  "nueva filosofía"), tras una ronda de feedback crítico. El aporte candidato a
  novedad es el §3 (unificar límite metabólico y límite lógico); su validez
  depende del Camino A. Riesgo mayor identificado: la "ilusión de convergencia"
  (infalsabilidad) — antídoto = §7.3 / Camino E.
- **2026-07-31** — Creados el documento-puente y esta hoja de ruta. Extracción
  cerrada (3 notas → 16 unidades; obra original → 16 unidades + 2 facetas
  fundidas). Definido el puente (moneda) y el registro (filosófico riguroso).
