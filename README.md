# Conventional_Commit
**¿Que es un commit?**

Un *commit* es un "Punto de guardado" que registra los cambios realizados en los archivos de un proyecto específico 

**¿Que es conventional commit?**

*Conventional commit* es un conjunto de reglas para estandarizar los mensajes de commit, para que sea mas fácil escribir herramientas automatizadas encima, describiendo las características, correcciones y cambios importantes realizados.

Deben ser estructurados de la siguiente manera:

"<type>[optional scope]: <description>

[optional body]

[optional footer(s)]"


**Algunos tipos mas comunes**

Feat    =   Nueva funcionalidad para el proyecto

Fix     =   Corrección de un error

Docs    =   Cambios en la documentación 

Style   =   Cambios que no afectan el código (Espacios, formato, comas etc)

Refactor=   Reescritura del código sin cambiar su funcionalidad 

Perf    =   Mejoras de rendimiento

Test    =   Agregar o corregir pruebas

Chore   =   Tareas menores o de mantenimiento

Revert  =   Reversión de un commit anterior

Breaking Change =   Modificación del código que rompe la compatibilidad con versiones anteriores


**Ejemplos de Conventional Commit**

(Confirmar mensaje con "!" para llamar la atención)

feat!: send an email to the customer when a product is shipped

(Confirmar con "!" y pie de página BREAKING CHANGE)

chore!: drop support for Node 6

BREAKING CHANGE: use JavaScript features not available in Node 6.


**¿Por qué es importante?**

Esta información es fundamental para poder mantener un proyecto sano, colaborativo y estable sobre todo al trabajar en equipo, advirtiendo de los cambios hacia los demás en algunos casos ellos teniendo que adaptar su código a este cambio (Esto con BREAKING CHANGE por ejemplo). Esto es útil por que mejora la colaboración en equipo ya que otros desarrolladores podrán entender rápidamente el impacto de cada cambio sin tener que revisar todo el código
