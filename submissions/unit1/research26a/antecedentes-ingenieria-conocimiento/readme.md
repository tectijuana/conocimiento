# Ingeniería del Conocimiento (TIC-1015)

## Investigación Individual

> **Antecedentes de la Ingeniería del Conocimiento**

| | |
|---|---|
| **Estudiante** | [BUSTILLOS ORTIZ, José Luis] |
| **Docente** | [René Solis Reyes] |
| **Asignatura** | Ingeniería del Conocimiento (TIC-1015) |
| **Institución** | Tecnológico Nacional de México |

---

## 1. Introducción

La Ingeniería del Conocimiento es una disciplina relativamente moderna, pero sus fundamentos vienen de mucho tiempo atrás. En esta investigación exploraré algunos de los antecedentes históricos más importantes que llevaron al desarrollo de esta área.

Revisaré las contribuciones de Aristóteles en lógica formal, el papel de la filosofía analítica, algunas ideas interesantes de la alquimia sobre crear inteligencia artificial, y finalmente las aportaciones de von Neumann y Feynman a la computación moderna. El objetivo es entender mejor de dónde vienen las ideas que hoy usamos en sistemas inteligentes.

---

## 2. Objetivo

Conocer los principales antecedentes históricos de la Ingeniería del Conocimiento, enfocándome en Aristóteles, la alquimia, la filosofía analítica,  y las contribuciones de von Neumann y Feynman.

---

## 3. Marco teórico

**Ingeniería del Conocimiento:** Disciplina que se dedica a construir sistemas computacionales que usan conocimiento para resolver problemas complejos.

**Conceptos básicos:**

- **Conocimiento:** Información que se puede aplicar para tomar decisiones
- **Razonamiento:** Proceso de sacar conclusiones a partir de información que ya tenemos
- **Lógica formal:** Sistema de reglas para razonar correctamente

---

## 4. Desarrollo

### 4.1 Aristóteles y la lógica formal

Aristóteles (384-322 a.C.) fue el primero en sistematizar cómo razonamos. Creó el **silogismo**, que es una forma de razonamiento con dos premisas y una conclusión:

> **Ejemplo clásico:**
> - Todos los humanos son mortales *(premisa mayor)*
> - Sócrates es humano *(premisa menor)*
> - Por lo tanto, Sócrates es mortal *(conclusión)*

Esto es importante para la Ingeniería del Conocimiento porque los sistemas expertos actuales funcionan de manera similar. Usan reglas del tipo "SI esto, ENTONCES aquello" que vienen directamente de la lógica aristotélica.

**Ejemplo en computadora:**
```python
SI animal(X) Y mamífero(X) 
ENTONCES tiene_sangre_caliente(X)
```

Esta forma de razonar con reglas es la base de muchos sistemas inteligentes.

---

### 4.2 La alquimia y la idea de crear inteligencia

La alquimia tiene una conexión interesante con la inteligencia artificial. Los alquimistas no solo querían convertir plomo en oro, también querían crear vida e inteligencia artificiales.

**El homúnculo:** *Paracelso*, un alquimista del siglo XVI, describió cómo crear un ser humano artificial en el laboratorio. Esto muestra que la idea de crear inteligencia artificial es muy antigua.

**El Golem:** En la tradición judía, el Golem era un ser artificial creado mediante palabras mágicas. Se activaba escribiendo *"verdad"* en su frente y se desactivaba borrando una letra. Esto se parece bastante a cómo programamos computadoras hoy:

- El Golem recibía órdenes → Las computadoras ejecutan instrucciones
- Se activaba con símbolos → Los programas se escriben en código
- Tenía limitaciones → La IA actual es limitada, no puede hacer todo

Estas historias muestran que los humanos siempre hemos soñado con crear máquinas que piensen.

---


### 4.3 Filosofía analítica

En los siglos XIX y XX, varios filósofos trabajaron en hacer la lógica más formal y matemática:

**Gottlob Frege:** Desarrolló una lógica más avanzada que la de Aristóteles, usando símbolos matemáticos. Esto es la base de cómo las computadoras *"piensan"* hoy.

**Bertrand Russell:** Intentó demostrar que toda la matemática se puede derivar de la lógica. Aunque no lo logró completamente, sus ideas influyeron mucho en la programación de computadoras.

**Ludwig Wittgenstein:** Estudió la relación entre lenguaje y pensamiento, algo muy importante para el procesamiento de lenguaje natural.

Gracias a estos filósofos, hoy tenemos herramientas como:
- Lenguajes de programación lógica (Prolog)
- Bases de datos que usan lógica
- Sistemas para verificar que un programa funcione correctamente

---

### 4.4 John von Neumann: Las computadoras modernas

John von Neumann (1903-1957) es una de las personas más importantes en la historia de las computadoras.

**Su contribución principal: La arquitectura von Neumann**

Inventó la forma en que funcionan casi todas las computadoras hoy en día. Su idea clave fue que los programas y los datos se pueden guardar en la misma memoria. Antes de esto, había que reconectar físicamente los cables de las computadoras para cambiar de programa.

**Componentes básicos:**
- CPU (cerebro de la computadora)
- Memoria (donde se guardan datos y programas)
- Entrada/salida (teclado, pantalla, etc.)

También trabajó en teoría de juegos, que estudia cómo tomar decisiones estratégicas. Esto es muy importante para sistemas de IA que tienen que decidir qué hacer en diferentes situaciones.

---

### 4.5 Richard Feynman: Computación cuántica

Richard Feynman (1918-1988) fue un físico que ganó el Premio Nobel. En 1981 tuvo una idea revolucionaria: las computadoras normales no pueden simular bien sistemas cuánticos (átomos, partículas, etc.). Propuso usar sistemas cuánticos para computar.

**¿Qué es la computación cuántica?**

En las computadoras normales, un bit es 0 o 1. En computadoras cuánticas, un "qubit" puede ser 0 y 1 al mismo tiempo (superposición cuántica). Esto permite hacer muchos cálculos en paralelo.

**¿Para qué sirve?**

- Simular moléculas para diseñar medicamentos
- Optimización (encontrar la mejor solución entre millones de opciones)
- Inteligencia artificial más potente

Aunque todavía estamos desarrollando computadoras cuánticas prácticas, la idea de Feynman abrió un campo completamente nuevo en la computación.



---

## 5. Análisis y discusión

Después de revisar estos antecedentes, me di cuenta de varias cosas interesantes:

**Conexión histórica:** La Ingeniería del Conocimiento no apareció de la nada. Hay una línea clara desde Aristóteles hasta la IA moderna. Cada persona o época aportó algo que hizo posible el siguiente paso.

**Aplicaciones actuales:**
- Los sistemas expertos usan la lógica de Aristóteles
- Los lenguajes de programación vienen de la filosofía analítica
- Las computadoras funcionan con la arquitectura de von Neumann
- La computación cuántica de Feynman apenas está empezando

**Limitaciones:** Aunque estos personajes hicieron contribuciones importantes, también tuvieron limitaciones. Por ejemplo, la lógica de Aristóteles no puede manejar incertidumbre, y las computadoras de von Neumann consumen mucha energía comparadas con el cerebro humano.

Lo más interesante es que la idea de crear inteligencia artificial es muy antigua (como el Golem), pero solo hasta hace poco tenemos la tecnología para intentarlo en serio.

---

## 6. Conclusiones

1. La Ingeniería del Conocimiento tiene raíces muy antiguas. Aristóteles empezó todo con su lógica formal hace más de 2000 años.

2. Los alquimistas y sus ideas sobre crear seres artificiales (homúnculo, Golem) muestran que la humanidad siempre ha soñado con crear inteligencia artificial.

3. La filosofía analítica (Frege, Russell, Wittgenstein) convirtió esas ideas en matemáticas formales que las computadoras pueden usar.

4. Von Neumann diseñó la arquitectura básica de las computadoras modernas. Sin su trabajo, no tendríamos IA.

5. Feynman imaginó un tipo completamente nuevo de computación (cuántica) que podría hacer que la IA sea mucho más poderosa en el futuro.

6. Cada contribución histórica resolvió algunos problemas pero también tiene limitaciones. Por eso la IA sigue siendo un campo en desarrollo.

Lo que más me sorprende es que muchas ideas que parecen nuevas en realidad tienen antecedentes muy antiguos. La diferencia es que ahora tenemos la tecnología para implementarlas.

---

## 7. Aporte al repositorio

Esta investigación aporta una visión histórica de la Ingeniería del Conocimiento que conecta ideas antiguas con tecnología moderna. Puede servir a otros estudiantes para entender mejor de dónde vienen los conceptos que estudiamos en el curso.

El documento muestra que la IA no es solo tecnología reciente, sino el resultado de miles de años de pensamiento humano sobre el conocimiento y la inteligencia.

---

## 8. Referencias

1. Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4ta ed.). Pearson.

2. Aspray, W. (1990). *John von Neumann and the Origins of Modern Computing*. MIT Press.

3. Feynman, R. P. (1982). Simulating physics with computers. *International Journal of Theoretical Physics*, 21(6-7), 467-488.

4. Principe, L. M. (2013). *The Secrets of Alchemy*. Chicago: University of Chicago Press.

5. Stanford Encyclopedia of Philosophy. (2023). "Aristotle's Logic". Disponible en: https://plato.stanford.edu/entries/aristotle-logic/

6. Copeland, B. J. (2004). *The Essential Turing*. Oxford: Clarendon Press.

---

## 9. Declaración de originalidad

Declaro que esta investigación fue elaborada por un servidor para el curso de Ingeniería del Conocimiento. Se consultaron las fuentes listadas en las referencias y el análisis general es mi propio trabajo.

**Firma:** [Bustillos Ortiz José Luis]

**Fecha:** [10/02/2026]

---

<div align="center">

**Tecnológico Nacional de México**  
*Ingeniería del Conocimiento • TIC-1015*

</div>
