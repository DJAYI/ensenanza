El proceso de análisis de sistemas en si mismo conlleva su propia rama de estudios, pero no me extenderé en los conceptos, y si lo deseas, puedes quedarte solo con el siguiente concepto, el cual es una definición personal en si.

> _"El Análisis es la abstracción de procesos del mundo real, los cuales identifican una necesidad (o problemática) y le da una solución eficaz a través de tareas/actividades_".

¡Wow, wow, wow (y no guau 🐶). Espera un momento! ¡¿Qué rayos significa todo eso?!

Tranquilo, te explicaré por partes. Cuando me refiero a la _"Abstracción de procesos del mundo real"_ me refiero a **agarrar** un proceso **ya existente**, que ya ofrece una **solución**. ¿Para qué? Te estarás preguntando, la razón es lo que viene después en _"Identifican una necesidad y le da una solución eficaz a través de tareas/actividades"_. Tengo un problema, necesito darle una solución eficaz a ese problema ¿Con qué? ¡Con el proceso anteriormente mencionado! (Es como jugar con Legos).

> Te voy a dar un pequeño ejemplo:

Supongamos que soy el administrador de una tienda y tengo **Dificultades** para llevar el _seguimiento del inventario de mis productos_. Tengo que:

**Realizar los siguientes procesos:**

> 	**A. Elegir el producto de cual voy a hacer seguimiento.**
> 		1. Anotar sus características en mi agenda (Su nombre, descripción y precio).
> 		
> 	**B. Seguir los Movimientos de existencias de ESE producto.**
> 		1. Contar cuantas tenía al comenzar el día.
> 		2. Contar cuantas vendí al terminar el día. (Y cuantas se "extraviaron", en fin, la delincuencia 😢).
> 		3. Y si el camión me surtió con nuevas existencias de ESE producto, también debo contar cuantas nuevas tengo.
> 		
> 	**C. Calcular el Stock a partir de los movimientos anteriores**
> 		1. Resto las que tenia al comenzar al día con las que tenía al terminar y saco mis "Salidas".
> 		2. Agarro el número de existencias nuevas que recibí  y las anoto como "Entradas".
> 		3. Resto las salidas de las entradas y lo que quede (sea negativo o positivo) lo sumo a lo que me quedó al final del día

**Dificultades:**
- La agenda con la que hago seguimiento se puede perder, puede ser hurtada o hacerse añicos. 

 - Los cálculos y operaciones pueden verse corruptas por errores humanos o verse afectados por la memoria. 

 - Puede que en el momento no anoté un movimiento importante por mero olvido y puede afectar al seguimiento final.

Como podrás observar, tengo un problema, que es el seguimiento del inventario de los productos. Pero pude describir una serie de procesos que llevan a una solución, aunque manual, funciona de forma eficaz, son los procesos A, B y C y cada uno tiene tareas especificas. ¿Crees que se podría evolucionar la forma en la que se maneje esta información?

Ya prácticamente tenemos el proceso de análisis completado y seguramente ni te diste cuenta, ¿Lo notaste? Tenemos una problemática, tenemos procesos que resuelven esa problemática (llamémosles requisitos/requerimientos funcionales) que constan de tareas especificas para ser llevados acabo (llamémosles historias de usuario).

> Sé que las historias de usuario constan de una persona o "Actor" que las lleva a cabo, pero en este caso como soy yo el administrador de la tienda, el único actor sería el "Administrador" (Si tuviera ayudantes o asistentes entonces si se tomaría mas en cuenta).

**Formato de Historia de Usuario aplicado:**

>"**Como** administrador de la tienda, **quiero** registrar las características de un producto **para** poder llevar control de inventario".

Solo hay que añadir un pequeño prefijo y es "Quiero que el Software me permita..." y completar con cada uno de los procesos anteriormente descritos y sus tareas/actividades correspondientes. Adicionalmente puedo hablar con mi cliente (El administrador de la tienda) y decirle:

>¿Quieres que haga algo más, un inicio de sesión o que los datos se guarden en alguna parte específicamente, o algo más? 

A manera de escudriñar un poco más sus necesidades y entregar un producto de mejor calidad.

>A veces los clientes no sabrán ni lo que quieren, debes tener paciencia y tratar de enfocarte en encontrar una **Problemática** y los **Procesos**. Si puedes mejorar los procesos, mucho mejor. Busca toda la información posible y analízala por partes (nunca como un TODO imposible de resolver).

El análisis es el primer paso crítico en el desarrollo de software. Identificar las necesidades y procesos existentes permite definir una base sólida para el diseño y desarrollo de cualquier sistema de información (Software o aplicación).

---
### Glosario.

---

1. **Análisis:**
    
    - Contexto en el texto: Se menciona como una de las etapas clave del SDLC.
    - Explicación Sugerida:
        
        > Es el proceso de entender un problema y definir claramente qué se necesita para resolverlo.
        
2. **Requisitos (o Requerimientos):**
    
    - Contexto en el texto: Se menciona como las características necesarias de un software.
    - Explicación Sugerida:
        
        > Son las funciones o características que el software debe cumplir para resolver un problema.
        
3. **Historias de Usuario:**
    
    - Contexto en el texto: Usado como una forma de describir tareas específicas para el sistema.
    - Explicación Sugerida:
        
        > Son descripciones breves de lo que un usuario necesita del software, escritas en lenguaje cotidiano.
        
4. **Actor:**
    
    - Contexto en el texto: Mencionado como la persona o sistema que realiza una acción en el software.
    - Explicación Sugerida:
        
        > Es quien interactúa con el sistema, como un administrador, cliente o máquina.
        
5. **Escalable:**
    
    - Contexto en el texto: Usado para describir software que puede manejar crecimiento.
    - Explicación Sugerida:
        
        > Significa que el software puede crecer o adaptarse fácilmente para manejar más usuarios o datos en el futuro.
        
6. **Problema/Problemática:**
    
    - Contexto en el texto: Base para identificar necesidades durante el análisis.
    - Explicación Sugerida:
        
        > Es cualquier situación o desafío que el software debe resolver.
        
7. **Procesos:**
    
    - Contexto en el texto: Describen actividades del mundo real que deben digitalizarse.
    - Explicación Sugerida:
        
        > Son conjuntos de pasos o tareas que se realizan para lograr un objetivo.
        
8. **Tareas/Actividades:**
    
    - Contexto en el texto: Mencionadas como componentes específicos de un proceso.
    - Explicación Sugerida:
        
        > Son acciones individuales necesarias para completar un proceso.
        
9. **Requisitos Funcionales:**
    
    - Contexto en el texto: Relacionados con los procesos y tareas del análisis.
    - Explicación Sugerida:
        
        > Son las funciones específicas que el software debe realizar, como registrar ventas o calcular el inventario.
        
10. **Software de Calidad:**
    
    - Contexto en el texto: Mencionado como el objetivo final del SDLC.
    - Explicación Sugerida:
        
        > Es software que funciona correctamente, es fácil de usar y cumple con las necesidades del cliente.
        
11. **Estándar:**
    
    - Contexto en el texto: Descrito como una norma que se suele seguir.
    - Explicación Sugerida:
        
        > Es una forma aceptada y común de realizar algo.
        

---
