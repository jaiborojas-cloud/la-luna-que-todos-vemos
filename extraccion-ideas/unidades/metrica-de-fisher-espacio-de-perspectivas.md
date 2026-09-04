---
titulo: La métrica de Fisher sobre el espacio de perspectivas (y la separación de capas Φ / Fisher)
estado: en desarrollo
primera_aparicion: notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
apariciones:
  - notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
pensadores_relacionados: [Ronald Fisher, Nikolai Chentsov (Čencov), Shun'ichi Amari, C. R. Rao, Giulio Tononi (IIT / Φ), Claude Shannon]
resumen: >
  Paga la deuda mayor de la nota 08: **D no tenía métrica**. Candidata propuesta: la
  **métrica de información de Fisher** sobre el espacio de configuraciones relacionales.
  Tres razones dadas: da una conexión canónica (sin la cual no hay transporte paralelo
  ni holonomía), fija una escala de curvatura no arbitraria (sin la cual «vecindad» es
  un parámetro libre), y es —por el **teorema de Chentsov**— la única métrica
  riemanniana invariante bajo estadísticos suficientes. Fricción detectada y resuelta:
  Fisher es maquinaria shannoniana, pero la variable ontológica declarada de la obra es
  **Φ/IIT** (información integrada, no shannoniana). Resolución por **separación de
  capas**: Φ es la variable ontológica (estructura causal integrada de la red, lo que
  se maximiza); Fisher es la geometría del **espacio de descripciones**
  (discriminabilidad entre perspectivas, no del objeto descrito).
---

Es la unidad que hace que [[holonomia-y-memoria-como-torsion]] pueda volver del exilio
y que [[dos-tests-de-divergencia]] tenga sobre qué operar. Con métrica hay conexión;
con conexión hay transporte paralelo; con transporte paralelo hay holonomía medible.
Todo el aparato de la nota 09 cuelga de esta elección.

**La separación de capas es el movimiento más fino de la nota.** Evita un error de
categoría que habría sido letal —geometrizar la conciencia con la misma entropía que
la obra rechazó para definirla— distinguiendo *lo que se mide* de *el espacio donde se
mide*. Fisher no dice nada sobre el objeto descrito; dice cuán distinguibles son dos
descripciones de él. Es la misma disciplina del Camino E aplicada a una herramienta
matemática: decir exactamente qué trabajo hace y qué trabajo no hace.

**Cautela epistémica (regla de oro).**

- *Teorema de Chentsov — enunciarlo con su alcance.* El resultado clásico (Čencov 1972)
  es que la Fisher es, **salvo escala**, la única métrica riemanniana invariante bajo
  estadísticos suficientes **sobre el símplex de distribuciones en un conjunto finito**
  (invariancia bajo morfismos de Markov). Hay extensiones al caso infinito/continuo
  (Ay, Jost, Lê, Schwachhöfer), pero no son el teorema clásico. La frase «la única
  métrica invariante» es correcta **con la salvedad de finitud y de escala**; sin ellas
  se sobrevende. Como el proyecto ya asume finitud en todas partes (L2), la salvedad
  cuesta poco y compra rigor.
- **⚠ Trampa técnica que hay que fijar por escrito: *qué* conexión.** «Fisher da una
  conexión canónica» es ambiguo, y la ambigüedad es fatal para el Test B. La geometría
  de la información trae **una familia** de α-conexiones (Amari), y las dos más
  naturales para familias exponenciales —la exponencial (α=1) y la de mezcla (α=−1)—
  son **planas**: su curvatura es idénticamente cero, y por tanto **su holonomía es
  trivial**. Si el proyecto usa esas, el Test B devuelve cero siempre y la señal
  desaparece por construcción. La conexión que hay que usar es la de **Levi-Civita de
  la métrica de Fisher** (α=0). Esto debe quedar escrito antes de formalizar nada más;
  es el tipo de detalle que hunde un formalismo entero en silencio.
- *Φ/IIT — un compromiso pesado que el corpus **no tiene documentado**.* La nota dice
  que la variable ontológica de la obra «es Φ/IIT, adoptada precisamente para evitar
  reducir conciencia a entropía de Shannon». **Esa adopción no aparece en ningún
  archivo del repo**: Tononi solo figura como mención de pasada en la nota 07 y en
  [[neguentropia-exploracion-y-compresion]]. O la decisión se tomó en una conversación
  no registrada, o es nueva aquí. En cualquier caso hay que decidirla explícitamente,
  porque **IIT es un compromiso caro**: es una teoría en disputa activa (con una carta
  abierta de 2023 que la acusa de no falsable, y sus réplicas), y Φ es
  computacionalmente intratable de calcular para sistemas no diminutos. Adoptarla
  ata el proyecto a una apuesta contestada en el punto más visible. **Alternativa a
  considerar:** dejar la variable ontológica como *place-holder declarado* («una medida
  de integración causal, de la que Φ es un candidato») — se conserva el antirreduccionismo
  sin comprar la teoría entera.
- *La otra cara de la separación de capas:* si Φ vive en una capa y Fisher en otra, hay
  que decir **cómo se comunican**. Hoy son adyacentes, no integradas. La geodésica
  minimiza pago (Fisher/Shannon) y lo que se maximiza es Φ: falta el enunciado que
  relacione ambas magnitudes, o el proyecto tiene dos monedas sin tipo de cambio. Es la
  pregunta abierta más importante que deja esta unidad.

**Veredicto de recurrencia**: ocurrencia única (nota 09). Es, junto con
[[dos-tests-de-divergencia]], el par que convierte el andamiaje analógico de la nota 08
en un objeto matemático manipulable — a condición de fijar la conexión y de resolver
el estatuto de Φ.
