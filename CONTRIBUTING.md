# Guía para el trabajo en equipo — AgroBPA

Esta guía establece algunas pautas que utilizaremos durante el desarrollo de AgroBPA con el propósito de mantener una buena organización entre los integrantes del equipo.

La idea principal es trabajar de forma coordinada, mantener un historial claro de los cambios y evitar problemas al momento de integrar el trabajo realizado por cada integrante.

---

## 1. Distribución de actividades

Cada integrante tendrá a su cargo determinadas actividades dentro del proyecto.

Se debe procurar trabajar sobre las tareas asignadas y consultar con el equipo antes de comenzar una actividad que pueda involucrar archivos o funcionalidades que estén siendo desarrolladas por otro compañero.

De esta manera evitamos duplicar trabajo y reducimos la posibilidad de generar conflictos.

---

## 2. Manejo de ramas

La rama `main` será utilizada para mantener una versión estable del proyecto.

Por esta razón, los desarrollos nuevos, correcciones y pruebas deben realizarse utilizando ramas independientes.

### Ejemplos de ramas

`git checkout -b feature/usuarios`

`git checkout -b feature/cultivos`

`git checkout -b fix/login`

El nombre de cada rama debe permitir identificar fácilmente el objetivo del trabajo realizado.

---

## 3. Registro de cambios

Cada modificación importante debe quedar registrada mediante un commit.

El mensaje debe ser corto, específico y permitir entender qué se modificó.

### Ejemplos de commits

`feat: implementar formulario de usuarios`

`feat: agregar gestión de cultivos`

`fix: solucionar error de inicio de sesión`

`docs: modificar guía del proyecto`

`style: ajustar diseño del panel`

Evitemos utilizar mensajes poco descriptivos como:

- `cambios`
- `prueba`
- `arreglado`
- `actualización`
- `nuevo`

Un buen mensaje facilita posteriormente la revisión del historial del proyecto.

---

## 4. Preparación antes de programar

Antes de comenzar una sesión de trabajo, es conveniente comprobar que contamos con la versión más reciente del proyecto.

Para actualizar los cambios disponibles podemos utilizar:

`git pull`

De esta manera trabajamos sobre una versión más actualizada y disminuimos la posibilidad de encontrar conflictos posteriormente.

---

## 5. Revisión antes de realizar un push

Antes de enviar los cambios al repositorio remoto, cada integrante debe comprobar que su trabajo funciona correctamente.

Se debe revisar principalmente:

- Que la aplicación inicie sin problemas.
- Que la funcionalidad desarrollada cumpla con lo solicitado.
- Que no se hayan dañado funciones existentes.
- Que únicamente se hayan modificado los archivos necesarios.
- Que no existan archivos temporales o innecesarios.
- Que no se hayan incluido datos personales, contraseñas o claves privadas.

Después de realizar estas comprobaciones se puede proceder a subir el trabajo.

---

## 6. Integración mediante Pull Request

Cuando una funcionalidad o corrección haya sido finalizada, se deberá solicitar su integración mediante un **Pull Request**.

En la descripción se debe indicar de forma sencilla:

- Qué trabajo fue realizado.
- Qué funcionalidad fue agregada o modificada.
- Qué inconveniente fue solucionado, si aplica.
- Si el cambio puede influir en otras partes del sistema.

Siempre que sea posible, otro integrante deberá revisar el código antes de incorporarlo a `main`.

---

## 7. Manejo de conflictos

Durante el trabajo colaborativo pueden aparecer conflictos cuando diferentes integrantes modifican una misma parte del proyecto.

Cuando esto ocurra, se debe identificar primero qué cambios pertenecen a cada integrante y determinar cuál debe conservarse.

No se deben eliminar cambios de otros compañeros sin consultar previamente.

Si el conflicto afecta una funcionalidad importante, lo recomendable es comunicarlo al equipo y solucionarlo conjuntamente.

---

## 8. Buenas prácticas de programación

El código de AgroBPA debe mantenerse organizado para facilitar su lectura, modificación y mantenimiento.

Para ello procuraremos:

- Utilizar nombres comprensibles.
- Mantener una estructura de carpetas clara.
- Evitar código repetido.
- Separar correctamente las responsabilidades.
- Mantener los componentes y funciones organizados.
- Utilizar comentarios solamente cuando aporten información útil.
- Conservar un formato de código uniforme.

El objetivo es que cualquier integrante pueda comprender el trabajo realizado por otro compañero.

---

## 9. Comunicación entre integrantes

El desarrollo colaborativo requiere mantener informados a los demás integrantes.

Se debe comunicar al equipo cuando:

- Se comience una actividad que pueda afectar otras funcionalidades.
- Se termine una tarea importante.
- Aparezca un error que impida continuar.
- Se necesite apoyo para resolver un problema.
- Se realice un cambio estructural.
- Una modificación pueda afectar el trabajo de otro integrante.

Una comunicación adecuada permite solucionar problemas antes de que se conviertan en conflictos mayores.

---

## 10. Cuidado del repositorio

El repositorio representa el trabajo conjunto del equipo, por lo que cada integrante debe procurar mantenerlo limpio y organizado.

Antes de subir archivos se debe verificar que realmente hagan parte del proyecto.

No se deben subir:

- Archivos temporales.
- Carpetas generadas automáticamente que no sean necesarias.
- Contraseñas.
- Claves de acceso.
- Tokens.
- Información privada.
- Archivos personales.

También se recomienda utilizar correctamente el archivo `.gitignore` para evitar agregar elementos que no deben formar parte del repositorio.

---

## 11. Compromiso del equipo

El resultado de AgroBPA depende del trabajo realizado por todos los integrantes.

Cada persona debe asumir responsabilidad sobre las actividades que desarrolla, pero también debe estar dispuesta a colaborar cuando otro integrante necesite apoyo.

Las decisiones que puedan modificar de manera importante la estructura o funcionamiento del proyecto deben ser comunicadas al equipo antes de aplicarse.

Trabajar de manera organizada permitirá avanzar con mayor facilidad, reducir errores y conservar una versión estable del proyecto.

---

## Proyecto AgroBPA

**Trabajo colaborativo — SENA**

**Objetivo:** desarrollar el proyecto de manera organizada, mantener un repositorio limpio y facilitar la integración del trabajo realizado por todos los integrantes.
