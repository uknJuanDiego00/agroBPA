Guía de trabajo colaborativo — AgroBPA

Este documento contiene las reglas y recomendaciones que seguiremos como equipo para trabajar de manera organizada en el desarrollo del proyecto AgroBPA.

El objetivo es evitar conflictos entre los cambios realizados por los integrantes y mantener el proyecto organizado y fácil de mantener.

1. Organización del trabajo

Cada integrante debe trabajar principalmente en la tarea o funcionalidad que le haya sido asignada.

Antes de comenzar una nueva tarea, debemos comunicarnos con el equipo para evitar que dos personas trabajen sobre la misma parte del proyecto al mismo tiempo.

2. Uso de ramas

No se deben realizar cambios directamente sobre la rama main.

Para cada funcionalidad, corrección o tarea se debe crear una rama propia.

Ejemplos:

git checkout -b feature/registro-usuarios
git checkout -b feature/gestion-cultivos
git checkout -b fix/error-login


El nombre de la rama debe indicar brevemente qué se está trabajando.

3. Commits

Los commits deben ser claros y explicar qué cambio se realizó.

Ejemplos:

feat: agregar registro de usuarios
feat: crear módulo de cultivos
fix: corregir validación del formulario
docs: actualizar documentación
style: mejorar estilos de la pantalla principal


Se recomienda evitar mensajes demasiado generales como:

cambios
actualizacion
arreglos
cosas nuevas


Es mejor que cada commit represente un cambio concreto.

4. Antes de hacer cambios

Antes de comenzar a trabajar, debemos actualizar nuestra rama con los últimos cambios del proyecto.

git pull


Esto ayuda a reducir conflictos y evita trabajar sobre una versión desactualizada del código.

5. Antes de subir cambios

Antes de hacer push, cada integrante debe verificar que sus cambios funcionen correctamente y que no hayan afectado otras funcionalidades.

Se recomienda revisar:

Que el proyecto pueda ejecutarse correctamente.

Que no existan errores evidentes.

Que los cambios realizados correspondan únicamente a la tarea trabajada.

Que no se hayan agregado archivos innecesarios.

Que no se incluyan contraseñas, claves API u otra información privada.

6. Pull Requests

Cuando una tarea esté terminada, se debe crear un Pull Request hacia main.

El Pull Request debe explicar brevemente:

Qué se desarrolló o modificó.

Qué problema se solucionó.

Si se realizaron cambios importantes en otras partes del proyecto.

Antes de integrar los cambios a main, otro integrante del equipo debe revisarlos cuando sea posible.

7. Resolución de conflictos

Si aparecen conflictos al integrar cambios, los integrantes involucrados deben comunicarse para resolverlos.

No se deben eliminar o modificar los cambios de otro compañero sin entender primero qué función cumplen.

En caso de duda, es preferible consultar al equipo antes de realizar cambios importantes.

8. Organización del código

Todos debemos procurar mantener una estructura de código ordenada y coherente.

Se recomienda:

Utilizar nombres claros para variables, funciones, componentes y archivos.

Mantener funciones y componentes con responsabilidades claras.

Evitar duplicar código innecesariamente.

Mantener la estructura de carpetas organizada.

Comentar únicamente cuando sea necesario explicar una lógica que no sea evidente.

9. Comunicación del equipo

La comunicación es importante para evitar problemas durante el desarrollo.

Si un integrante va a modificar una parte importante del proyecto, debe comunicarlo al resto del equipo cuando pueda afectar el trabajo de los demás.

También debemos informar cuando:

Una tarea esté terminada.

Se encuentre un error importante.

Se necesite ayuda con alguna parte del proyecto.

Un cambio pueda afectar otras funcionalidades.

10. Responsabilidad sobre los cambios

Cada integrante es responsable de revisar los cambios que realiza antes de subirlos al repositorio.

El objetivo no es solamente completar una tarea, sino contribuir a que el proyecto completo se mantenga funcional y organizado.

11. Trabajo como equipo

AgroBPA es un proyecto desarrollado entre todos los integrantes del equipo. Por esta razón, debemos mantener una comunicación respetuosa y ayudarnos cuando sea necesario.

Las decisiones importantes sobre la estructura, funcionalidades o cambios que puedan afectar varias partes del proyecto deben ser comunicadas y, cuando sea necesario, discutidas entre todos.

La finalidad de estas reglas no es complicar el desarrollo, sino ayudarnos a trabajar de manera organizada y evitar perder o sobrescribir el trabajo de nuestros compañeros.

Proyecto AgroBPA — SENA