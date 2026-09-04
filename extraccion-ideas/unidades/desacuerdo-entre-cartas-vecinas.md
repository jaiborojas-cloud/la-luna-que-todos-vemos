---
titulo: El desacuerdo entre cartas vecinas (criterio local de degradación)
estado: en desarrollo
primera_aparicion: notas-crudas/nota-08-curvatura-sin-metrica-perspectividad-dinamica.md (2026-09-04)
apariciones:
  - notas-crudas/nota-08-curvatura-sin-metrica-perspectividad-dinamica.md (2026-09-04)
  - notas-crudas/nota-09-geometria-de-las-cartas-de-perspectiva.md (2026-09-04)
pensadores_relacionados: [H. S. Seung / Manfred Opper / Haim Sompolinsky (query by committee), W. Ross Ashby, Karl Friston, John Vervaeke, Donald Campbell (triangulación por múltiples métodos), Shun'ichi Amari]
resumen: >
  Respuesta a la pregunta operativa «¿cómo sabe un sistema, sin vista global, que su
  perspectiva actual se está degradando?». Se evaluaron tres candidatos: (1)
  **persistencia de la sorpresa** — barato pero lento, y confunde mal-calibración con
  cambio real del entorno; (2) **razón esfuerzo/efecto** — comparar frecuencia y
  magnitud de las reponderaciones contra la reducción real de residuo; más rápido,
  pero exige historial de ajustes, y la memoria cuesta; (3) **desacuerdo entre cartas
  vecinas** — el elegido: sostener simultáneamente varias perspectivas de **baja
  resolución** cerca de la actual y usar su **divergencia** como señal de alarma.
  Es local, computable, y no requiere vista global. Reconocido como la versión honesta
  y no sobrevendida de la intuición de holonomía original.
---

Es el **aporte operacional** de la nota 08 y el que la salva de ser solo geometría
prestada. La cadena queda completa: la [[incompletud-necesaria]] dice que no hay carta
global; la [[perspectividad-dinamica]] dice que entonces hay que desplazarse; la
[[relevancia-como-gradiente-local]] dice hacia dónde, sin mirar el todo; y esta unidad
dice **cuándo** — cuándo el sistema debe moverse.

**El movimiento clave, y por qué es honesto.** La holonomía prometía una señal
(el fallo de cierre de un lazo en D) que el sistema, en el mejor de los casos, no
podría medir desde dentro; ver [[holonomia-y-memoria-como-torsion]]. El desacuerdo
entre vecinas conserva la intuición —*la discrepancia entre descripciones es
información*— pero la vuelve **accesible al sistema**: no hace falta recorrer un lazo
ni conocer una curvatura, basta comparar dos aproximaciones burdas de lo mismo. Es la
degradación deliberada de una idea elegante a una idea usable, y ese cambio de
estatuto —de *analógico* a *tesis argumentada con mecanismo*— es exactamente lo que la
regla de oro premia.

**La economía del truco.** Las cartas vecinas son de **baja resolución** a propósito:
mantener varias perspectivas completas en paralelo violaría el presupuesto finito (L2)
que fundamenta todo el edificio. La apuesta es que unas pocas aproximaciones baratas
compran una señal de alarma cuyo valor supera su costo. Es también un paliativo
parcial del óptimo local que hereda la [[relevancia-como-gradiente-local]]: las
vecinas ven un poco más allá de donde alcanza el gradiente de la carta actual.

**Cautela epistémica (regla de oro).**
- *Tesis argumentada con mecanismo:* el criterio es concreto y, a diferencia de casi
  todo el lote 04–07, **se podría implementar y falsar**. Un ensamble de modelos de
  baja capacidad cuya divergencia anticipe la caída de desempeño de un modelo
  principal es un experimento hoy realizable; si la divergencia no anticipara nada, el
  criterio muere. Eso es una virtud rara en el corpus.
- *Precedente que hay que citar (Camino G):* esto ya existe en aprendizaje automático
  bajo otros nombres — **query by committee** (Seung, Opper & Sompolinsky, 1992),
  desacuerdo de ensambles como estimador de **incertidumbre epistémica**, y la
  triangulación por múltiples métodos de Campbell. El proyecto **no lo está
  inventando**; lo está *derivando* desde una restricción termodinámico-estructural en
  vez de adoptarlo como heurística. Ese es el diferencial defendible, y hay que
  enunciarlo así o el primer lector informado lo desarma.
- *Flanco abierto (lo que falta):* qué cuenta como «vecina». Sin métrica sobre D no
  hay noción definida de cercanía —la misma deuda que arrastra el
  [[espacio-de-descripciones-y-geodesicas]]—, así que hoy «vecina» significa, en el
  mejor caso, «obtenida por una perturbación barata de la carta actual». Además, dos
  cartas vecinas **pueden estar de acuerdo y equivocadas a la vez** (sesgo compartido
  por construcción, si nacen de perturbar la misma carta): el criterio detecta
  inestabilidad, no error. Es una alarma de humo, no un detector de verdad. Decirlo
  así lo mantiene dentro de rigor.

**Qué queda por hacer** (Camino I de la hoja de ruta): desarrollarlo como mecanismo
completo de recalibración — cuántas vecinas, cómo se generan, qué umbral de divergencia
dispara el desplazamiento, y quién paga la señal.

**Reapariciones**
- *nota-09*: **la unidad queda reparada, y por disolución.** La nota 09 detecta el
  defecto que aquí no se había visto —la divergencia es **ambigua**: puede significar
  estructura real no capturada (señal) o una carta rompiéndose (artefacto), y las
  respuestas son opuestas— y lo resuelve notando que «vecinas» significa **dos cosas
  distintas, con dos tests distintos** ([[dos-tests-de-divergencia]]): mismo punto en
  dos cartas (Test A, consistencia por jacobiano — nunca debería divergir, es
  depuración) vs. puntos distintos y cercanos (Test B, holonomía tras transporte
  paralelo — esa sí es señal). También **salda el flanco abierto** que este archivo
  dejaba: «qué cuenta como vecina» deja de ser parámetro libre y pasa a derivarse del
  radio de inyectividad / escala de curvatura.
  *El precio, que hay que registrar:* lo que hacía atractivo a este criterio era ser
  **barato**; el Test B exige conexión, métrica y sus derivadas. Sigue siendo local,
  pero ya no es gratis — y en un edificio fundado en presupuesto finito (L2), habrá
  que mostrar que la señal vale su costo.

**Veredicto de recurrencia**: recurrente (notas 08 y 09) — y con una trayectoria
interna poco común: propuesta como versión honesta de una idea sobrevendida (08) y
luego **corregida por ambigüedad y reconstruida sobre geometría real** (09). Es, junto
con la entropía-costo de la nota 06, uno de los pocos rescates del material reciente
que sirve al **Proyecto A** (argumento) y no solo al Proyecto B (marco).
