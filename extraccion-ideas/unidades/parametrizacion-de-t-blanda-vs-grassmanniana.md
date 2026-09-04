---
titulo: Qué es t — activación blanda vs. Grassmanniana (pregunta abierta, con un resultado que la inclina)
estado: semilla
primera_aparicion: notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
apariciones:
  - notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
pensadores_relacionados: [Hermann Grassmann, Shun'ichi Amari, Bradley Efron (curvatura estadística), Ronald Fisher, Alan Edelman / Tomás Arias / Steven Smith (geometría de Stiefel-Grassmann)]
resumen: >
  Última pregunta abierta de la nota 09, y bloqueante para formalizar el holonomy-test.
  Se propuso t = «subconjunto de relaciones activas», y se detectó el problema: un
  subconjunto puro es un **vértice de un hipercubo** —discreto, sin gradiente, sin
  vecindad infinitesimal—, y todo el aparato de cartas, covectores y Fisher exige
  continuidad para poder derivar. (Nota relacionada: solo los subespacios *coordenados*
  provienen de un subconjunto, y son 2^N puntos aislados dentro del continuo de la
  Grassmanniana.) Dos salidas, sin decidir: **(1) activación blanda** —Bernoulli por
  relación, θ_i ∈ (0,1), Fisher diagonal g_ii = 1/(θ_i(1−θ_i)), el subconjunto puro
  como límite en las esquinas del cubo—; **(2) Grassmanniana** —t como punto de Gr(k,N)
  que varía suavemente, con métrica y curvatura canónicas ya conocidas, al precio de
  cambiar la lectura de «relaciones prendidas/apagadas» por «cuánto y en qué dirección».
---

Es la junta entre el formalismo y la ontología: de esta elección depende qué significa
literalmente «perspectiva» en el proyecto. La nota deja la decisión pendiente y propone
compararlas con un ejemplo de 3–4 relaciones.

**Resultado que hace innecesario ese ejemplo, al menos para la opción (1).** Si el
criterio de decisión es *cuál de las dos sostiene el Test B* (ver
[[dos-tests-de-divergencia]]), la opción (1) **se descarta sola, analíticamente y para
todo N**:

> La propia fórmula que la nota escribe lo delata. Una Fisher **diagonal** cuyo
> `g_ii` depende **solo de θ_i** es una métrica producto de N variedades de dimensión
> 1. Con el cambio de coordenadas `u_i = 2·arcsin(√θ_i)` se obtiene
> `du_i = dθ_i/√(θ_i(1−θ_i))`, y la métrica queda `g = Σ du_i²`: **euclidiana** sobre
> la caja abierta (0, π)^N. Es decir, el modelo de Bernoullis independientes es una
> variedad **plana** — tensor de Riemann idénticamente nulo, dominio simplemente
> conexo. Luego su holonomía es **trivial** y **el Test B devuelve cero siempre, por
> construcción.** No hay curvatura que medir porque no hay ninguna.

Y la lectura conceptual de ese cálculo es mejor todavía que el cálculo:

> **La curvatura viene de la dependencia entre relaciones.** Bernoullis independientes
> = relaciones que no se enteran unas de otras = espacio plano = ninguna señal. En el
> momento en que las relaciones se acoplan estadísticamente, el modelo deja de ser un
> producto, se vuelve una familia exponencial **curva** (en el sentido de Efron)
> dentro del símplex, y aparece curvatura no nula. Para un proyecto cuya tesis
> fundacional es [[relacion-unidad-fundamental]], esto es casi poético y del todo
> conveniente: **la geometría solo tiene algo que decir si las relaciones son
> genuinamente interdependientes.** Modelarlas como interruptores independientes es,
> literalmente, aplanar la ontología del proyecto.

**Lo que esto sugiere para la decisión** (sin cerrarla, es del usuario):
- **(1) tal como está escrita: descartada** para sostener el holonomy-test. Sigue
  sirviendo como parametrización cómoda si el objetivo fuera solo medir distancias,
  no curvatura.
- **(1′) Bernoulli con acoplamientos** —añadir términos de interacción entre relaciones,
  tipo campo aleatorio de Markov / Ising— es la opción que **conserva la lectura
  literal** («relaciones más o menos activas») **y recupera la curvatura**. No estaba
  en la nota y probablemente es la salida correcta: es el punto medio que nadie
  propuso. Costo: la Fisher deja de ser diagonal y de tener forma cerrada bonita.
- **(2) Grassmanniana: viable y curvada.** Gr(k,N) es un espacio simétrico compacto con
  métrica, conexión, curvatura y holonomía canónicas y bien estudiadas — el Test B
  tendría ahí todo lo que necesita. El costo es el que la nota ya identifica, y es
  ontológico, no técnico: se pierde la lectura «prendida/apagada» y se gana «cuánto y
  en qué dirección». (Advertencia menor: en casos degenerados —k=0, k=N, Gr(1,2)— es
  trivial o plana; el rango debe ser no degenerado.)

**Cautela epistémica (regla de oro).**
- *Demostrable:* la planitud del modelo Bernoulli-producto bajo la métrica de Fisher es
  un hecho estándar de geometría de la información (métrica diagonal con `g_ii(θ_i)` ⇒
  isometría con un dominio euclidiano), y la curvatura de la Grassmanniana es geometría
  clásica. Ninguno de los dos es tesis del proyecto.
- *Advertencia de fondo:* este resultado **debe leerse junto con** la trampa de las
  α-conexiones señalada en [[metrica-de-fisher-espacio-de-perspectivas]]. Son dos
  maneras distintas de que el Test B muera en silencio devolviendo cero — una por
  elegir mal la conexión, otra por elegir mal la parametrización. Cualquier
  formalización futura debería empezar verificando que la curvatura **no** es nula
  antes de construir nada encima. Es la prueba de humo del Camino I.2.
- *Lo que sigue abierto de verdad:* qué relación hay entre la k de la Grassmanniana (o
  la intensidad de activación) y el presupuesto finito del observador (L2). Debería
  haber una: «cuántas relaciones puede sostener» es exactamente lo que la finitud
  acota, y sería elegante que la dimensión del modelo saliera del presupuesto en vez de
  ponerse a mano.

**Veredicto de recurrencia**: ocurrencia única (nota 09). Estatuto: **pregunta abierta
declarada**, ahora con una opción descartada por cálculo y una tercera sobre la mesa.
