Geometría de las cartas de perspectiva:

<!-- Pegada tal cual, salvo la notación matemática inline: el copiado la triplicaba
     (p(t∣x;θ)p(t\mid x;\theta) p(t∣x;θ)) y se dejó una sola forma legible.
     Ninguna otra palabra fue tocada. -->


1. El problema de partida
La divergencia entre cartas vecinas del atlas de perspectivas es ambigua: puede significar (a) curvatura/topología real no capturada por el atlas (señal informativa), o (b) que una carta se está rompiendo (artefacto). El desacuerdo, por sí solo, no distingue una causa de otra, y las respuestas son opuestas.


2. Resolución: dos tests, no un criterio añadido
La ambigüedad se disuelve al notar que "vecinas" puede significar dos cosas distintas, con dos tests distintos:

- Test A — mismo punto, dos cartas. Si el gradiente de relevancia es un covector genuino (sección del cotangente), su expresión en una carta se obtiene de la otra vía el jacobiano de la transición, exactamente. Si el pullback no coincide más allá del ruido numérico, eso no es señal geométrica — es la prueba de que el objeto o la carta está roto. Este test nunca debería divergir en un atlas bien construido.
- Test B — puntos distintos y cercanos. Comparar covectores en puntos distintos exige una conexión (transporte paralelo), que es dependiente de la trayectoria si la variedad tiene curvatura. La divergencia residual después de transportar correctamente — la holonomía — es la divergencia informativa genuina: mide curvatura real.

Los casos (a) y (b) del problema original no compiten por el mismo test: (b) vive en el Test A, (a) vive en el Test B.


3. La escala de "vecindad" deja de ser un parámetro libre
La escala válida para el Test B es el radio dentro del cual la aproximación de primer orden del transporte paralelo sigue siendo confiable: el radio de inyectividad / escala de curvatura local de la conexión. No se tunea; se deriva del objeto geométrico mismo.


4. El gradiente de relevancia debe ser un campo covectorial genuino
Sin este supuesto, "mirar desde aquí" y "mirar desde allá" difieren solo por ser coordenadas distintas del mismo punto, y la alarma de divergencia se dispara con artefactos de carta, no con inadecuación real. La consistencia inter-carta exigida es la condición de que las expresiones locales de un mismo covector coincidan bajo el jacobiano de la transición — de metáfora a ecuación.


5. Candidato de métrica: Fisher, con separación de capas
Se evaluó la métrica de información de Fisher sobre el espacio de configuraciones relacionales como métrica natural para las cartas (da conexión canónica, escala de curvatura no arbitraria, y es la única métrica riemanniana invariante bajo estadísticos suficientes — teorema de Chentsov).

Fricción identificada y resuelta: Fisher es maquinaria shannoniana, mientras que la variable ontológica de la obra es Φ/IIT (información integrada, no shannoniana), adoptada precisamente para evitar reducir conciencia a entropía de Shannon. Se resolvió con una separación de capas explícita:

- Φ/IIT — variable ontológica: estructura causal integrada de la red, lo que se maximiza.
- Fisher — geometría del espacio de descripciones: discriminabilidad entre perspectivas/cartas, no del objeto descrito.


6. Espacio muestral fijado: compresión, no predicción
El objetivo declarado es calcular perspectivas, no predecir. Se descartó por ahora la opción de Fisher sobre eventos futuros de la red (predictiva) en favor de Fisher sobre la distribución de estados internos del observador finito — un canal con pérdida p(t | x; θ) que comprime el estado completo de la red x en lo que el observador finito puede sostener, parametrizado por θ (las coordenadas de la carta).

Esto conecta directamente con el gozne de pago/Landauer ya establecido en la obra: por teoría de tasa-distorsión, sostener una compresión con distorsión D tiene un costo mínimo en bits R(D), que es disipación. La métrica de Fisher sobre θ hereda ese costo — no es geometría añadida, es la misma estructura leída dos veces.

Puente hacia el test predictivo futuro: el information bottleneck generaliza este mismo canal añadiendo un término que preserva información sobre una variable relevante y (eventos futuros). Cuando se retome la opción predictiva, se extiende el mismo objeto — no se construye un segundo marco en paralelo.


7. Pregunta abierta: qué es t concretamente
Se propuso t = "subconjunto de relaciones activas". Se identificó que esto no es equivalente en general a un subespacio en álgebra lineal: solo los subespacios coordenados (span{e_i : i ∈ S}) provienen de un subconjunto, y son una familia discreta y finita (2^N) dentro del continuo de todos los subespacios (Grassmanniana). Un subconjunto activo/inactivo puro es un vértice de un hipercubo — discreto, sin gradiente, sin vecindad infinitesimal — y todo el aparato de cartas/covectores/Fisher construido en la sesión requiere continuidad para poder derivar.

Dos salidas identificadas, sin decidir aún:

- Activación blanda (Bernoulli por relación): θ_i ∈ (0,1), intensidad continua de activación. Métrica de Fisher explícita y diagonal (g_ii = 1/(θ_i(1−θ_i))). El subconjunto activo puro es el límite en las esquinas del cubo. Encaja directo con lo ya fijado en §6.
- Grassmanniana: t como punto de Gr(k,N) que varía continuamente — no selección discreta sino deformación suave de cuánto contribuye cada relación a un subespacio de dimensión k. Métrica y curvatura canónicas, ya conocidas — pero cambia la lectura literal de "relaciones prendidas/apagadas" a "cuánto y en qué dirección".

Pendiente: decidir entre las dos (o comparar con un ejemplo de 3–4 relaciones) antes de fijar la interpretación relacional de θ y avanzar a formalizar el holonomy-test completo.
