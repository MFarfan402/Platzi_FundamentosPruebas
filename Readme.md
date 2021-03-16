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

# Gestión, monitoreo y control

##  Caja Blanca, Gris y Negra

Cuando nos referimos a una caja es la manera de observar el contenido del software.
Caja negra: No vemos como fue construido el código. Solo vemos la interfaz.
Caja blanca: Podemos ver lo que hay adentro del código.
Caja gris: Integraciones, como fluyen los datos a través de las redes.


Tecnicas de pruebas:
* Caja negra.
- Partición de equivalencia. Agrupamiento de los casos de acuerdo a ciertos grupos.
- Valores límite. Uso de valores frontera, máximos y mínimos.
- Tablas de decisiones. Matrices de resultados, variables de entrada y variables de salida.
- Transición de estado. Como se comporta el componente dadas ciertas condiciones de entrada. 
- Casos de uso. Probar flujos completos.

* Caja blanca.
- Cobertura de declaraciones. (Cobertura de sentencias)
Dependiendo del tipo de software, implica que cada línea de código debería de ser ejecutada alguna vez. Y para una puesta en producción debería de tener un índice de cobertura antes de una liberación.
Práctica las sentencias ejecutables en el código. Se mide entre el número de sentencias ejecutadas, entre el número de sentencias ejecutables.
- Cobertura de código.
Se prueban los flujos basados en los resultados de cada decisión. La cobertura se mide entre el número total de resultados de decisión ejecutados, entre el número de casos de uso.

* Caja gris.
- Casos de negocio.
Es necesario concocer como interactua el usuario con el sistema. Para eso hay un flujo con datos de entrada, procesamiento y datos de salida. Tiene relación con el business model.
- Pruebas E2E.
Como se esta reflejando la interfaz de acuerdo a cierto contexto dado.
- Pruebas de integración.
Como se transportan los datos. Las integraciones son las respuestas de como fluyen los datos a tavés de distintos servicios.

## Gestión de monitoreo y control: Monitoreo y Seguimiento.

El 30% de las empresas no logran gestionar y monitorear las pruebas.

Etapas de gestión de pruebas:
Planeación, Monitoreo, análisis, diseño, implementación, ejecución y finalización.

Planeación: Definir los objetivos de las pruebas. Alcancce, estimación y recursos.
Monitoreo y control: Metricas que nos revelen si llevamos avances. Forma en la que nos alertará si el plan no se está llevando a cabo.
Análisis: Decidir cuales son las prioridades. 
Diseño: diseño de casos de uso. Después priorizar las pruebas, identificar el entorno de pruebas, trazabilidad entre pruebas y condiciones. 
Implementación: Infraestructura suficiente para ejecutar las pruebas. Equipo y material para su seguimiento, datos de entrada, arquitectura y software de seguimiento.
Ejecución: ejecutar las suites de pruebas de acuerdo con el plan que se ha realizado. 
Finalización: Que porcentaje se ejecutaron, aprender lecciones sobre el proceso, comunicar los defectos.

## Roles y responsabilidades

Aunque seamos especialista en software. Cuando se dividen las responsabilidade para el area de pruebas manuales se observan 4 roles principales:
Escpecialista en pruebas manuales: Pensamiento lateral, organización diseño y documentación.
Especialista en pruebas tecnicas: Conocimientos técnicos. Estar siempre actualizada en las herramientas que le permitan acelerar el trabajo. Autodidacta, continuo entrenamiento.
Lider del equipo de pruebas: gestión a todo el equipo, dar seguimiento a los defectos.
Ingeniero de calidad: La cultura, el proceso, alinear las pruebas de acuerdo el negocio.

La responsabilidad de todos ellos es que se aseguren de la calidad del producto que se está entregando.

## Roles y Responsabilidades en acción

Independientemente del rol, un tester participa de todas las etapas del proceso de desarrollo de software.
El perfil del tester conjuga habilidades con el conocimiento del negocio, de la aplicación y del diseño, ejecución y administración de las pruebas.

Tester manual: Estrategia, definición, ejecución y cobertura de pruebas para cumplir los requerimientos.
Tester técnico: Acelera la capacidad de ejecución de las pruebas. Implementa herramientas que permitan la automatización de pruebas. o la correctaa selección de datos de pruebas o el monitoreo de la ejecución de las pruebas.
El líder de pruebas: Se vuelve un facilitador de servicios, información y herramientas para el equipo de pruebas.
El ingeniero de calidad: Ayuda al negocio en general. Ayuda a testers como cualquier otro miembro del equipo a llevar a cabo pruebas que reduzcan el error humano.


# Gestión de bugs

## Ejercicios

1. "Es el encargado de hacer coaching de calidad en toda la empresa"
Respuesta: Ingeniero de calidad.

2. "Es el reponsable de emplear herramientas que automaticen o aceleren las ejecuciones de las pruebas"
Respuesta: Tester técnico.

3. "Es el responsable de asegurarse de la cobertura de pruebas y nuevos escenarios"
Respuesta: Tester manual.

4. "Es el facilitador del equipo que se asegura de implementar lo necesario para que se ejecuten las pruebas".
Respuesta: Líder de pruebas.

## Retrabajo

Las empresas deciden tener un monitoreo a través de herramientas no solo visuales, pero que todos puedan tener de manera clara que es lo que ya se hizo, que es lo que se está haciendo y que es lo que se va a hacer después.

Para esto sirven las acciones de control:
- Si identificamos un riesgo.

    El monitoreo nos sirve para saber si estamos encontrando un riesgo para el negocio. Cuando algo se esta saliendo de control, cuando no vayamos a acabar a tiempo o si tenemos algún bloqueador.

- Si identificamos falta de ambientes.

    Es común que el ambiente de pruebas no siempre este configurado o que requiera ser actualizado. Para poder tener una idea de que los ambientes estén listos deben formar parte de nuestras métricas de monitoreo y avances de trabajo.

- Si el DoD no se cumple.

    Se realizaron las pruebas, se aceptaron los cambios, pero puede que no se ajuste el criterio a lo nuevo que se haya cambiado


Los resultados de las pruebas:
¿Cuántas pruebas se han ejecutado? ¿Cuantas ellas encontraron un defecto o un blocker?
Desempeño del equipo de testing:
No asiste alguien, no hubo internet, el cliente no entrego. Muchas circunstancias forman parte del desempeño.

¿Cuándo sucede el retrabajo?
"Principal causa de de costos elevados y que la planeación no funcione."
Las acciones, las actividades y los hábitos de como gestionar los hábitos son el retrabajo.

- Falta o mala documentación.
- Falta de capacitación o dominio en las herramientas utilizadas.
- Falta de capacitación o dominio en el software a utilizar.
- Falta de comunicación