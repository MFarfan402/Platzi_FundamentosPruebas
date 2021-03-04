--------------------------------------------------------
## Proceso de pruebas del software y los estándares internacionales.

¿Que pruebas debemos hacer? 
¿Cuál debe ser nuestra perspectiva como testers?

Recursos: Carencias que se muestran como defectos a largo plazo.
Metodologías: Estartegia de como se llevan a cabo las pruebas.
Herramientas: Permite el trabajo de analísis y documentación de los defectos.

"El 64% de los errores se producen en el análisis y diseño."
Cuando no se entiende el software se empieza a crear defectos porque se deconoce lo que se quiera lograr.

Las pruebas se encargan de: 
- Definir la calidad de producto y calidad de proceso.
- Detectar y corregir la falta de calidad.

Certificaciones de testing:
- Indiiduos
- Procesos
- Empresas 

Estándares de testing:
- ISTQB
- IEEE
- TPI

## Proceso de pruebas del software: Calidad y Defectos

¿Que es la calidad? Es una percepción entre lo deseado y analizado.
La calidad forma parte del proceso. Si no se entiende lo que es la calidad para el cliente, no se tendrá la calidad deseada. 
Si no se entiende lo que dice el cliente, en todas las fases del ciclo de vida del desarrollo de software se tendrán defectos.

Verificación: Revisión en cada una de las etapas lo que el cliente espera. Se hace en el momento de cada etapa.
Validación: Revisión antes de la entrega final.

Anomalías - Cualquier insatisfactoria condición.
Defecto - No desempeña funciones.
Fallo - Incapacidad dentro de márgenes.
Error - Acción humana incorrecta.

## Principios del testing moderno.

Evolución natural del testing ágil. Necesidad de evolucionar la perspectiva del desarrollador y el tester, trabajar como un equipo. El tester debería enfocarse en la calidad de software y el desarrollador debería crear el software. Todo trabajando en conjunto.

    Principios de Testing Moderno.

    "Podemos comenzar a pasar de ser los dueños de las pruebas o la calidad, a ser los embajadores de la calidad del producto."

        1. Nuestra prioridad es mejorar el negocio.

    Todo cambio mejora el negocio, entonces el no hacer el trabajo correctamente puede poner en riesgo al negocio.

        2. Nosotros aceleramos al equipo, usamos modelos como Lean Thinking y Teoría de las Restricciones para ayudar a identificar, priorizar y mitigar cuellos de botellas en el sistema.

    Tener ideas y construir basando en procesos cortos. Crear módulos de manera ágil. 

        3. Somos la fuerza para la mejora continua, ayudando al equipo a adaptarse y optimizar para tener éxito, en lugar de proporcionar una red de seguridad para detectar fallas.

    Enfoque de pruebas relacionado a fases. Pruebas distribuidas que permita mitigar el riesgo.

        4. Nos preocupamos profundamente acerca de la cultura de calidad en el equpo, y asesoramos, lideramos y nutrimos el equipo para llevarlos a una cultura de calidad más madura.

    El tester se vuelve un coach. "La calidad es la prioridad del equipo". El rol del tester es acompañar durante todo el proyecto a la calidad del producto.

        5. Nosotros creemos que el cliente es el úncio capaz de juzgar y evaluar la caldiad de nuestro producto.

    Creemos que el % de calidad esta dado por el cliente. 

        6. Nosotros usamos datos de manera extensa y profunda para entender los casos de uso del cliente y entonces cerrar huecos entre hipótesis del producto e impacto del negocio.

        7. Expandimos las habilidades de testing y el conocimiento en todo el equipo; entendemos que esto reduce o elimina la neceisadad de un especialista dedicado al testing.
    
    Conocer herramientas que aceleten el trabajo.

--------------------------------------------------------

## Presupuesto, Recursos, Tiempo y Actividades Clave

Los elementos que tomamos en cuenta para crear un proyecto de software son el presupuesto, el recurso y el tiempo. 
Una mala planeación del proyecto puede hacer que los costos se incrementen.

Actividades clave. Son actividades que nos permitan no salirnos de tiempo o costos y que la capacidad del equipo lo pueda llevar a cabo. 

Definición -> Análisis -> Diseño -> Desarrollo -> Pruebas -> Validación -> Mantenimiento.

* Análisis: 
Pruebas. Observar en los requerimientos si estan completamente explícitos para que el software lo pueda cubrir.
(Ejemplo de Login. N usuarios, login fallido).
Evitar que no se vayan detalles en los requerimientos.

* Diseño: 
Establecer los criterios visuales de lo que espera ver el cliente. (Validaciones sobre los componentes). 

* Desarrollo:
Implica módulos, funciones, BD, arquitectura general de la base de datos. No se necesita esperar a que el frontend este completado. 

* Pruebas:
Pruebas en dispositivos, pruebas de conexión. Sirven para confirmar lo funcional dentro de los requerimientos.
Pruebas de aceptación, donde esta el usuario final.

## Estrategia de pruebas

Son aquellas que nos permiten conocer por donde comenzar, planearlas, identificarlas. 

¿Que problema tenemos actualmente? ¿Qué problema debemos evitar? 

Caracterísiticas:
- La prueba comienza desde los niveles más básicos modulares.
- Distintas técnicas de pruebas.

Objetivos: 
- Planificar las pruebas necesarias en cada iteración. Incluyendo las pruebas de unidad, integración y pruebas de sistema.
- Diseñar e implementar pruebas creando casos de prueba.
- Realizar diferentes pruebas.

## Testing del desarrollo de software

Diferencias entre testing y checking.
Testing: Exploración que genera nuevos resultados.
Nunca termina, siempre hay nuevos escenarios. 

Checking: Ya sabemos que sucede algo y esperamos que suceda ese algo. Asegurarnos que siempre sucedan.
Estrategias del checking: Ejecutar checking solo si sucede algo más. Se ejecutan cada vez que... Se ejecuten de manera programada.

(Ejemplo de una maleta, cosas que se meten por primera vez, checklist.)

Errores comunes:
- Pruebas duplicadas: Invertir tiempo en algo que ya se llevo a cabo.
- Pruebas similares: Pruebas con el mismo flujo. Orientado a pruebas automatizadas.
- Pruebas sin valor agregado: Pruebas que no esta asociado al negocio.
- Pruebas caducadas. La naturaleza del software es incremental, por lo que se pueden volver obsoletas.

Checking mal empleado:
- Pobre cobertura de pruebas.
- Falta de actualización.
- Mal manejo de versiones

Ventajas de correr checking:
- Correr pruebas en paralelo o en múltiples plataformas
- Reducimos el error humano
- Probamos grandes cantidades de datos

Continous Delivery/Continous Integration

## Testing ágil

En pequeñas iteraciones logremos reducir el riesgo que se pueda correr en la entrega.
El testing ágil involucra a todos los miembros de un equipo, todos en el equipo son testers, pero el tester trata de tener la mayor cobertura de pruebas.

Estrategias ágiles (Forma de llevar el proceso de pruebas, documentación y entrega efectiva):
- Testing de todo el equipo.
- Testing independiente.
- Integración Continua (DEVOPS)
- TDD 
- BDD
- ATDD

Las pruebas dependen de todo el equipo. 

Ejemplos de niveles de prueba: componente, integración

## Niveles de pruebas.

Pruebas de niveles por capas. Nos sirve para separar las pruebas y tener una mayor cobertura permitiendonos mayor descripción y comprensión de todos los elementos.

- Pruebas de componentes.

Cosas pequeñas que podamos observar. No tienen que ver con todo un flujo completo. 

- Pruebas de integración.

Un sistema tiene una serie de componentes que trabajan juntos y se forma el sistema. Pero cuando se tienen varios sistemas, necesitamos la integración entre estos mismos. 

Las pruebas de integración miden la comunicación entre todos los componentes.

- Pruebas de sistema.

Incluyen el contexto. 

- Pruebas de aceptación.

Ya se ejecutaron las pruebas funcionales. Estas son cuando ya vamos a entregar a nuesstro cliente. Ultima verificación junto con las pruebas de cliente.

## Tipos de pruebas.

En los niveles sabemos la profundidad de las pruebas. Pero en los tipos conoceremos las técnicas que se van a emplear para probar cierto sistema.

Tipo de actividad específica que vamos a tomar de acuerdo con nuestros objetivos. 

- Pruebas funcionales.
¿Como funciona un sistema? ¿Como interactua un usuario con el?
¿Que es lo que hace el sistema?

- Pruebas no funcionales.
Aun cuando el sistema funciona, no es accesible, que tenga la capacidad para interactuar con la aplicación.

- Pruebas estructurales.
Pruebas sobre la base de datos, que el servidor se encuentre bien configurado. (Pruebas de caja blanca).

- Pruebas de manejo de cambios.
Pruebas de regresión y es necesario revisar que el sistema este acorde al sistema.

## Pruebas estáticas y dinámicas

Pruebas estáticas se basan en la examinación manual de los elementos que conforman la construcción del software.

Prubas dinámicas se enfocan principalmente en comportamientos externos visibles durante la ejecución del software.

Elementos de pruebas estáticas:
- Contratos, planes y calendario del proyecto, así como su presupuesto.
- El análisis de requerimientos.
- Especificaciones o reglas de negocio. 
- Definición de HU, criterios de aceptación, mockups, arquitectura
- Las pruebas (puntos de verificación CI)
- Guías de usuario
- Evaluación/revisión del código.

El desarrollador cree todo lo que se le dice en un requerimiento. Pero el tester debe trabajar de forma conjunta con el product owner para revisar lo que pide el cliente, lo que se puede construir y lo que se está construyendo.

Beneficios:
- Detectar y corregir defectos de manera más eficiente.
- Identificar y priorizar la ejecución de pruebas en etapas posteriores
- Prevenir defectos:
    - Que no son detectables durante las pruebas dinámicas.
    - Duratne la etapa de análisis y diseño.
- Reducimos inconsistencias, ambigüedades, contradicciones y definiciones incorrectas.
- Reducimos costos y tiempos
- Reducimos retrabajos
- Mejoramos la comunicación entre todos los miembros del equipo.

"La obviedad es la causa principal de la introducción de defectos."

## Definición y diseño de pruebas.

¿Que hace un tester?
1. Encontrar problemas.
2. Documentar problemas.
3. Comunicar problemas.

"Si no encuentra problemas antes de que el producto sea entregado al cliente, entonces su testing es ineficiente"
"Si cuando encuentras problemas no sabe documentar y reproducir los pasos correctos su testing genera retrabajo"
"Si como QA no sabe  argmentar y proteger los intereses del negocio o de los clientes, su testingo no agrega valor"

¿Que debe contener el caso de prueba?
Nombre, desscripción, pasos, resultados esperados, resultados actuales