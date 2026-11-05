# Camino H — El salto intra→inter: qué hereda la red del límite de cada nodo

> **Qué es esto.** La costura **C3** del documento-puente: los pasos 3–5 de la
> derivación (§3.2) saltan de la economía interna de *un* sistema cognitivo a una
> red de sistemas, usando «sistema» como comodín. Este archivo separa los dos
> argumentos y dice con precisión **qué del límite individual se transfiere a lo
> colectivo, qué no, y por qué** (criterio de hecho del Camino H en la hoja de
> ruta). Arranca de la nota 10 (`extraccion-ideas/notas-crudas/nota-10-...`) y del
> criterio de §7.3 (v2.3).
>
> Fecha: 2026-11-05. Estatuto: argumento con núcleo demostrable (§2.1–§2.2), una
> condición declarada (§2.3), cinco condiciones de funcionamiento (§3) y una
> tensión que se convierte en tesis (§4). Retroalimenta §3.2, §3.3, §5.2, §7.2 y
> §7.3 del documento-puente.

---

## 0. El resultado, en una frase

> **El límite de copia se hereda sin premisa nueva; el deber de regular no se
> hereda; el límite de evaluación se transforma en asimetría; y la ganancia de
> distribuir existe solo bajo cinco condiciones, la más frágil de las cuales —la
> diversidad— es erosionada por la propia circulación.**

De ahí sale una consecuencia que el documento no tenía: una red que conoce de forma
distribuida solo persiste si **regenera diversidad**. La regla «no repetir» deja de
ser un adorno y pasa a ser una condición de persistencia (§4).

---

## 1. El comodín «sistema»: tres preguntas que el documento confundía

**Definiciones de trabajo.**

- **Nodo:** un sistema finito que evalúa (un cerebro, un dispositivo).
- **Red** N: un conjunto finito de nodos acoplados por **comunicación**, en el
  sentido aceptado en §7.3: lo que circula entre nodos es lo comprimible
  (descripciones, resultados), no la evaluación.
- **Agente:** un sistema con **variables esenciales** que debe mantener en rango
  para persistir (Ashby, 1952). Es lo que el Paso 2 del documento-puente supone
  del cerebro: *debe* regular un todo que lo incluye.

Con eso, «el límite del sistema» se parte en tres preguntas distintas:

| | Pregunta | Quién evalúa | Qué se evalúa |
|---|---|---|---|
| **Q1** | ¿Puede un nodo contener el todo? | un nodo | la red que lo incluye |
| **Q2** | ¿Puede un nodo conocer por completo a otro? | un nodo | otro nodo |
| **Q3** | ¿Puede la red conocerse a sí misma? | la red | la red |

El documento-puente, en los pasos 3–5 de §3.2, pasa de una a otra sin decirlo. Las
tres tienen respuestas distintas.

---

## 2. Qué se hereda, qué no, qué se transforma

### 2.1 Se hereda sin premisa nueva: el límite de copia (Q1)

Un nodo es una **parte propia** de la red. Por conteo (L1a), una parte propia
finita no distingue todos los estados del todo; Breuer (1995) lo probó para
cualquier observador contenido en el sistema que observa, clásico o cuántico,
determinista o estocástico.

Lo notable es que este caso es **más fácil** que el intra: no necesita el Paso 2.
El nodo no tiene que *deber* regular la red; basta con que sea parte de ella y
finito. La finitud la paga, como siempre, L2: cada nodo tiene presupuesto finito.

**Estatuto:** *demostrable* para nodos finitos. **Se hereda íntegro.**

### 2.2 Se transforma: el límite de evaluación (Q2)

Dentro de un nodo, el límite de evaluación es **reflexivo** (§2.4 del
documento-puente). Entre nodos no desaparece: **cambia de forma**.

- **Lo que se prohíbe:** dos nodos no pueden inferirse por completo el uno al otro.
  Wolpert (2008) lo prueba para inferencia fuerte entre cualesquiera dos
  dispositivos (Teorema 3), y para inferencia débil entre dispositivos
  **distinguibles** (Teorema 1).
- **Lo que se permite:** la inferencia en **una dirección**. Un nodo puede saber de
  otro lo que el otro no sabe de sí; lo que no puede ocurrir es que ambos se sepan
  por completo a la vez.
- **Cómo se aprovecha:** el nodo que sabe algo del otro no se lo transfiere como
  evaluación; se lo **ofrece** como resultado, y el otro lo **verifica** con su
  propio módulo. Ese es el modelo de las pruebas interactivas (Goldwasser, Micali
  & Rackoff, 1985; Babai, 1985): un verificador limitado queda convencido de
  verdades que no podría producir solo (Shamir, 1992).

**Estatuto:** la prohibición es *demostrable* (Wolpert); la ganancia por
verificación es *demostrable en complejidad computacional*; que las mentes
funcionen así es **tesis**. **El límite se transforma: de reflexivo a asimétrico.**

**Dos mecanismos que no hay que confundir.** El límite de un nodo sobre sí mismo
tiene dos fuentes distintas, y se comportan distinto al pasar a otro nodo:

- **Contención** (Breuer; conteo): el nodo es parte de lo que intenta medir. Para
  otro nodo, el primero ya no lo contiene: este límite **no viaja**. B puede
  distinguir estados de A que A no distingue de sí.
- **Autorreferencia** (diagonal): el nodo consulta un veredicto sobre sí mismo y
  puede hacer lo contrario. Este límite **sí puede reaparecer** entre dos nodos, y
  aparece por la comunicación misma: si B predice «A hará X» y A recibe la
  predicción antes de actuar, A puede hacer lo contrario. El bucle A → B → A
  reconstruye el diagonal. Es lo que impide la inferencia mutua completa
  (Wolpert, Teoremas 1 y 3).

**La condición que esto impone a la circulación (efecto Edipo).** Popper llamó
*efecto Edipo* a la influencia de una predicción sobre el hecho predicho. Aquí
toma una forma precisa, que distingue dos clases de evaluación ajena:

- Lo que B sabe del **estado o el pasado** de A se puede comunicar sin perder
  valor: A lo recibe, lo verifica y lo usa.
- Lo que B sabe de la **conducta futura** de A, sobre la que A puede reaccionar,
  **se anula en parte al comunicarse**. Conserva su valor solo mientras quede fuera
  del pasado causal de A hasta que el hecho ocurra.

Así, la capa de región del tiempo relacional (`02-estado-de-la-cuestion.md` §1)
decide qué evaluación ajena puede circular sin destruirse. Matiza el modelo de
«el otro pone su perspectiva en la mesa»: hay perspectivas que, puestas en la
mesa, dejan de ser ciertas. *Estatuto: la reconstrucción del diagonal es
demostrable (Wolpert); su forma temporal es tesis estructural.*

### 2.3 No se hereda: el deber de regular (Q3)

El motor del documento-puente es *deber regular × no poder completar →
perspectiva* (§3.1). El **deber** viene del Paso 2: el nodo persiste solo si
mantiene sus variables esenciales en rango.

**Para la red, ese deber no está dado.** Una red de nodos no tiene, por el solo
hecho de existir, variables esenciales que deba mantener. Por eso:

- Se puede derivar que **en** la red hay perspectivas (una por nodo agente) y que
  circulan.
- **No** se puede derivar que **la** red tenga una perspectiva propia. Eso solo vale
  si la red es, ella misma, un agente: si tiene variables esenciales y se regula
  para conservarlas.

Hay candidatos a agentes colectivos —organizaciones, instituciones, colonias—, y
Luhmann ofrece un criterio posible: los sistemas sociales son autopoiéticos. Pero
autopoiesis no es lo mismo que tener variables esenciales en el sentido de Ashby, y
el documento no puede saltar de una a la otra sin argumento.

**Criterio de agencia colectiva (pendiente, trabajo futuro).** Una red cuenta como
agente si se cumplen tres cosas:

1. **Variables esenciales identificables:** magnitudes que, fuera de cierto rango,
   disuelven la red como tal (no a sus nodos).
2. **Regulación:** mecanismos de la red que responden a las desviaciones de esas
   variables y las devuelven al rango.
3. **Irreductibilidad a un nodo:** esa regulación no es la de un solo nodo que
   decide por todos.

*Criterio de hecho del trabajo futuro:* aplicar (1)–(3) a un caso concreto (una
institución, una organización) y mostrar que se cumplen, o cuál falla. Mientras
no se haga, la perspectiva colectiva queda como condición, no como hecho.

**Estatuto:** *condición declarada*, no hecho. **El deber de regular no se
hereda.** La frase «la sociedad tiene un punto de vista» no se deriva; la frase
«en la sociedad hay puntos de vista que circulan», sí.

### 2.4 Circula: lo comprimible, sobre un suelo físico común

Lo que pasa entre nodos es **comunicación**, y el marco lo deriva (§7.3): circula
lo que se comprime —descripciones, resultados, certificados—; la evaluación no se
comprime y no viaja.

El suelo de esa circulación es físico, no comunicativo: un mensaje cuenta como
compartido solo cuando está en el **pasado causal de ambos** nodos
(`02-estado-de-la-cuestion.md` §1). La comunicación se apoya en la intersección de
pasados; no la crea.

### 2.5 Cuadro de herencia

| Pieza | Dentro de un nodo | En la red | ¿Se hereda? |
|---|---|---|---|
| Límite de copia (L1a) | sí | sí: el nodo es parte de la red | **Se hereda**, sin Paso 2 |
| Finitud (L2) | por el presupuesto del nodo | por el de cada nodo | **Se hereda** |
| Deber de regular (Paso 2) | sí: condición de persistir | solo si la red es agente | **No se hereda**: condición |
| Punto ciego por **contención** | el nodo no distingue todos sus estados | el otro nodo no lo contiene: puede verlo | **Se invierte**: lo ve el otro |
| Punto ciego por **autorreferencia** | el nodo no decide toda propiedad de sí | reaparece si el veredicto ajeno llega antes del hecho (efecto Edipo) | **Se conserva condicionado** por la capa de región |
| Transparencia total (nadie tiene la vista completa) | imposible | imposible: ni nodo ni comité la tienen (conteo; Wolpert, T1 y T3) | **Se conserva** para la red entera |
| Evaluación (profundidad lógica + pago L2) | no admite atajo | no viaja: cada nodo evalúa con su módulo | **No viaja** |
| Perspectiva | derivada | una por nodo; colectiva solo si la red es agente | **Parcial** |
| Lo que circula | — | lo comprimible (comunicación) | — |
| Suelo común | — | intersección de pasados causales | literal |

---

## 3. Cuándo una red funciona como red de verificadores: cinco condiciones

Que el conocimiento *esté* distribuido es forzoso (§2.1). Que distribuirlo *mejore*
la cobertura no lo es: depende de cinco condiciones.

**V1 — Diversidad (distinguibilidad).** Nodos idénticos comparten puntos ciegos:
lo que uno no ve, ningún otro lo ve. El propio Teorema 1 de Wolpert necesita
dispositivos distinguibles. La diferenciación de la nota 10 —mismo plano, módulos
distintos— satisface V1. *Estatuto: necesaria; tesis estructural.*

**Posición sobre Hong & Page (2004) y Thompson (2014).** Hong & Page presentaron un
modelo según el cual grupos diversos superan a grupos de alta habilidad; Thompson
sostuvo que el resultado matemático es casi trivial y que su lectura social es un
mal uso. **V1 no depende de ese debate.** Se apoya en dos cosas más débiles y más
firmes: que nodos idénticos comparten puntos ciegos (lógico) y que el Teorema 1 de
Wolpert exige distinguibilidad (demostrado). Que los grupos diversos *rindan más*
en tareas reales es una afirmación empírica que el Camino H **no hace**: queda
**fuera de su alcance**. Hong & Page se cita solo como antecedente del tema, no
como apoyo.

**V2 — Asimetría verificar / producir.** La ganancia existe donde verificar es más
barato que producir. Donde verificar cuesta lo mismo que producir, distribuir es
solo **replicar**. *Estatuto: demostrable en su dominio (complejidad); su alcance
en mentes, tesis.*

**V3 — Código común.** Un resultado ofrecido solo se puede verificar si el que lo
recibe puede leerlo. Hace falta un código compartido: el contexto que disuelve la
ambigüedad de lo comprimido solo para quien conoce el sistema. **De dónde sale
el código:** el código común es **pasado común sedimentado**. Dos nodos pueden
decodificar lo que circula entre ellos en la medida en que comparten historia
causal; donde no la comparten, el receptor completa lo que falta con lo más
probable en su propio modelo, y lo que obtiene es un artefacto. V3 es así la capa
de región del tiempo vista desde la comunicación. **Tensión con V1:**
demasiado código común homogeniza (falla V1); demasiado poco vuelve ruido lo que
circula (falla V3). *Estatuto: tesis, ligada al hilo de compresión.*

**V4 — Costo pagable (L2).** Verificar cuesta energía (Landauer). La red gana solo
si producir una vez y verificar muchas cuesta menos que producir muchas. Cuando no,
aparecen las **patologías de circulación** que la metáfora de la moneda sí sabe
nombrar (documento-puente §5.2): atesoramiento (los resultados no se ofrecen),
circulación sin verificación (los errores se propagan como moneda falsa) y
saturación (más resultados de los que se pueden verificar). *Estatuto: tesis; la
pregunta del costo es experimental (nota 10, §7).*

**V5 — Puntos ciegos no del todo correlacionados.** El punto ciego **global** de la
red es lo que ningún nodo ve ni puede verificar: la intersección de los puntos
ciegos de todos. Es vacío, o pequeño, solo si los puntos ciegos no están todos
correlacionados. Es la misma condición de independencia que el teorema del jurado
de Condorcet (1785). *Estatuto: tesis estructural.* **Esto responde en parte a C2**
(§7.2 del documento-puente): distribuir mejora la cobertura **si y solo si** los
puntos ciegos son en parte independientes.

---

## 4. La tensión: la circulación erosiona la diversidad

Las cinco condiciones no son estables. Hay una dinámica que juega en contra de V1
y V5, y la produce la propia circulación:

1. Un nodo ofrece un resultado; otros lo verifican y lo **adoptan**.
2. Al adoptarlo, sus modelos se parecen más.
3. Modelos más parecidos tienen puntos ciegos más correlacionados.
4. La cobertura de la red **baja**, aunque cada nodo, por separado, sepa más.

No es especulación aislada. March (1991) lo mostró en organizaciones: cuando los
miembros aprenden rápido del «código» de la organización, cada uno mejora, pero la
organización deja de aprender, porque el código solo aprende de quienes se desvían
de él; en entornos cambiantes, solo la renovación —gente nueva, ideas nuevas— la
mantiene buscando. Zollman (2010) lo mostró en comunidades científicas: conviene
una **diversidad transitoria**, que dure lo bastante para no descartar teorías
antes de tiempo, pero no tanto que impida converger; limitar la información que
recibe cada individuo ayuda a sostenerla, y combinar demasiados mecanismos de
diversidad la vuelve tan estable que el resultado empeora.

**Consecuencia (tesis):** una red que conoce de forma distribuida solo persiste si
**regenera diversidad** a un ritmo que compense la homogeneización que produce su
propia circulación. Las tres vías de la nota 10 —variación, recombinación,
acoplamiento— son los mecanismos de regeneración. Y la regla «no repetir» encuentra
aquí una justificación funcional: no es solo una preferencia por lo nuevo, es la
condición para que la red no se vuelva ciega en conjunto.

**Un giro sobre la metáfora (Camino E).** El Camino E mostró que la propiedad
definitoria del dinero, la **fungibilidad**, contradice la singularidad de cada
perspectiva. Aquí esa misma propiedad aparece del otro lado: **una red cuyas
perspectivas se han vuelto fungibles ha perdido su cobertura.** La fungibilidad no
describe la mente; describe la **patología** de una red que circuló demasiado sin
regenerarse. Es un uso legítimo de la metáfora, dentro de la frontera de §5.2:
nombra una forma de fallo. *Estatuto: analógico productivo.*

Hay, por tanto, dos patologías de circulación, opuestas:

| Patología | Qué pasa | Qué falla |
|---|---|---|
| **Por defecto** (atesoramiento) | los resultados no se ofrecen | no hay verificación cruzada |
| **Por exceso** (fungibilización) | todo se adopta, nada se regenera | V1 y V5: los puntos ciegos se alinean |

---

## 5. Escala: intra e inter son el mismo análisis a distinta escala

Un cerebro también es una red de subsistemas que se comunican. Lo que hace que un
nivel cuente como «intra» no es el tamaño ni el material, sino **si el todo de ese
nivel es un agente**. Eso da el criterio que reemplaza al comodín:

> **Un nivel cuenta como «sistema», en el sentido del documento-puente, si y solo
> si tiene variables esenciales que debe regular.** En ese nivel valen el motor y la
> perspectiva. Por debajo, hay partes; por encima, hay redes, que heredan el límite
> de copia pero no el deber.

Con eso, la pregunta «¿se transfiere el argumento del cerebro a la sociedad?» se
vuelve otra, más precisa: **¿la sociedad, o esta institución, es un agente?** Es
una pregunta empírica para cada caso, no una cuestión de palabras. *Estatuto:
propuesta metodológica.* (Converge con la relatividad de escala de la ontología en
Ladyman & Ross, 2007.)

---

## 6. Libro de cuentas

| Afirmación | Estatuto | Base |
|---|---|---|
| Ningún nodo distingue todos los estados de la red que lo contiene | **Demostrable** (nodos finitos) | L1a; Breuer 1995 |
| Ese límite no necesita el Paso 2 | **Demostrable** | §2.1 |
| Dos nodos no se infieren por completo el uno al otro | **Demostrable** (con sus condiciones) | Wolpert 2008, Teoremas 1 y 3 |
| Un verificador limitado puede certificar lo que no produce | **Demostrable** (complejidad) | Goldwasser et al. 1985; Babai 1985; Shamir 1992 |
| El punto ciego por contención lo ve otro nodo; el de autorreferencia reaparece por comunicación | **Demostrable** en su núcleo | Breuer 1995; Wolpert 2008; §2.2 |
| La evaluación ajena de la conducta futura se anula en parte al comunicarse | **Tesis estructural** | Popper 1957 (efecto Edipo); §2.2 |
| El código común es pasado común sedimentado | **Tesis** | §3, V3; `02` §1 |
| Las mentes funcionan como red de verificadores | **Tesis** | §2.2 |
| La red tiene perspectiva propia | **Solo si es agente** (condición) | §2.3 |
| Distribuir mejora la cobertura si y solo si V1–V5 | **Tesis estructural** | §3 |
| La circulación erosiona la diversidad | **Tesis con apoyo en modelos** | March 1991; Zollman 2010 |
| Una red distribuida persiste solo si regenera diversidad | **Tesis** | §4 |
| La fungibilidad describe la patología por exceso | **Analógico productivo** | §4; Camino E |
| «Sistema» = nivel con variables esenciales | **Propuesta metodológica** | §5; Ashby 1952 |

---

## 7. Qué cambia en el documento-puente (aplicado en la v2.4)

1. **§3.2, paso 3** («complementariedad → distribución»): deja de ser automático;
   la distribución es forzosa (§2.1), pero que **mejore** la cobertura exige V1–V5.
2. **§3.3, C3:** pasa de «por saldar» a **acotada por el Camino H**. Queda abierto
   el criterio de agencia colectiva.
3. **§5.2:** añade la patología por exceso (fungibilización) como segundo uso
   legítimo de la metáfora.
4. **§7.2, C2:** V5 da la condición: la cobertura mejora si y solo si los puntos
   ciegos no están todos correlacionados.
5. **§7.3:** remite a este archivo.

---

## 8. Lo que queda abierto

- **Agencia colectiva (trabajo futuro, con criterio de hecho en §2.3):** aplicar
  los tres requisitos —variables esenciales, regulación, irreductibilidad a un
  nodo— a un caso concreto. Pregunta lateral: si la autopoiesis de Luhmann cumple
  el requisito 2.
- **El costo de verificar frente a producir** (V2, V4): medible en un caso de
  juguete; candidato a experimento preregistrado.
- **El ritmo de regeneración.** Zollman muestra que la diversidad debe ser
  transitoria: ¿hay un ritmo óptimo de variación frente a convergencia? Conecta con
  la pregunta de la nota 10 sobre el umbral de von Neumann.
- **Medir la correlación de puntos ciegos** (V5) sin acceso a los puntos ciegos
  mismos: solo se ven desde fuera, y desde fuera también hay puntos ciegos.

## 9. Lo que lo falsificaría

- Un nodo finito que distinga todos los estados de la red que lo contiene
  (contradiría Breuer).
- Una red de nodos homogéneos que cubra mejor que una heterogénea en tareas donde
  verificar es barato (debilitaría V1).
- Una red que circule intensamente durante mucho tiempo sin perder diversidad y sin
  regenerarla (debilitaría §4).

---

## Referencias

- Ashby, W. R. (1952). *Design for a Brain.* Chapman & Hall (2.ª ed., 1960).
- Babai, L. (1985). "Trading group theory for randomness." *Proceedings of the
  17th ACM STOC*, 421–429.
- Breuer, T. (1995). "The impossibility of accurate state self-measurements."
  *Philosophy of Science*, 62(2), 197–214.
- Condorcet, Marqués de (1785). *Essai sur l'application de l'analyse à la
  probabilité des décisions rendues à la pluralité des voix.* Imprimerie Royale.
- Goldwasser, S., Micali, S., & Rackoff, C. (1985). "The knowledge complexity of
  interactive proof-systems." *Proceedings of the 17th ACM STOC*, 291–304.
- Hong, L., & Page, S. E. (2004). "Groups of diverse problem solvers can outperform
  groups of high-ability problem solvers." *PNAS*, 101(46), 16385–16389.
  DOI: 10.1073/pnas.0403723101.
- Ladyman, J., & Ross, D. (2007). *Every Thing Must Go.* Oxford University Press.
- Luhmann, N. (1984). *Soziale Systeme.* Suhrkamp.
- March, J. G. (1991). "Exploration and exploitation in organizational learning."
  *Organization Science*, 2(1), 71–87.
- Popper, K. R. (1957). *The Poverty of Historicism.* Routledge & Kegan Paul.
- Shamir, A. (1992). "IP = PSPACE." *Journal of the ACM*, 39(4), 869–877.
- Thompson, A. (2014). "Does diversity trump ability? An example of the misuse of
  mathematics in the social sciences." *Notices of the AMS*, 61(9), 1024 ss.
  DOI: 10.1090/noti1163.
- Wolpert, D. H. (2008). "Physical limits of inference." *Physica D*, 237(9),
  1257–1281. DOI: 10.1016/j.physd.2008.03.040.
- Zollman, K. J. S. (2010). "The epistemic benefit of transient diversity."
  *Erkenntnis*, 72(1), 17–35. DOI: 10.1007/s10670-009-9194-6.

> **Revisión (2026-11-05, misma sesión).** §2.2 separa contención y
> autorreferencia y añade el efecto Edipo; §2.5 divide la fila del límite de
> evaluación; V3 recibe el origen del código común.
>
> **Nota de verificación (2026-11-05, pasada final).** Cotejados contra fuente:
> March 1991 (revista, volumen, páginas y resultado); Zollman 2010 (revista,
> volumen, páginas, DOI y la idea de diversidad transitoria); Hong & Page 2004
> (revista, volumen, número, páginas, DOI); Thompson 2014 (revista, volumen,
> número, página inicial, DOI); Ashby, *Design for a Brain* (Chapman & Hall, 1952;
> 2.ª ed. 1960); Popper (el efecto Edipo se introduce en *The Poverty of
> Historicism*). **Sin cotejar:** la página final de Thompson; la sección exacta de
> Popper; la página de Ashby donde define «variables esenciales» (concepto
> estándar del libro).
