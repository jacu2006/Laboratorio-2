# Laboratorio #2: Modelado de Clases y Gestión de Atributos mediante Propiedades en C#

## 📌 Información General
* **Universidad Tecnológica de Panamá**
* **Facultad de Ingeniería en Sistemas Computacionales**
* **Licenciatura en Ingeniería de Sistemas y Computación**
* **Herramientas de Programación Aplicada III (.NET)**
* **Grupo: 1IL133**
* **Facilitador: Ing. Irina Fong**
* **Estudiante: Javier Acuña**

---

## 📝 Descripción del Laboratorio
Este laboratorio aborda los fundamentos de la Programación Orientada a Objetos (POO) en el lenguaje C# dentro de la plataforma .NET. Se centra en la creación e instanciación de clases, la implementación de métodos con y sin parámetros, el paso de argumentos, así como la aplicación del encapsulamiento utilizando variables de instancia privadas (`private`) y propiedades con descriptores de acceso (`get` y `set`).

---

## 🎯 Objetivos de Aprendizaje
* Comprender la estructura de una aplicación de consola en C# y el funcionamiento del método `Main` como punto de entrada de la ejecución.
* Diseñar y programar clases en C# aplicando los estándares de nomenclatura de la industria (convención **PascalCase**) y modelado previo mediante diagramas de clases UML.
* Implementar métodos con y sin parámetros para modularizar el comportamiento de los objetos.
* Aplicar los modificadores de acceso `public` y `private` para garantizar el ocultamiento de información y la seguridad de los datos.
* Manejar variables de instancia y propiedades con descriptores `get` y `set` para la lectura y escritura controlada de atributos en los objetos.

---

## 📁 Contenido y Estructura del Repositorio

El laboratorio está dividido en tres actividades progresivas:

### 🔹 Actividad 1: Declaración de Clases e Instanciación Básica
* **Clase:** `LibroCalificacion`
* **Conceptos:** Definición de una clase formal, instanciación de objetos usando el operador `new`, llamada a constructores implícitos y ejecución de métodos públicos de tipo `void` sin parámetros.

### 🔹 Actividad 2: Métodos con Parámetros y Formato de Entrada/Salida
* **Clase:** `MiLibroCalificaciones`
* **Conceptos:** Paso de parámetros del tipo `string`, captura de datos desde la consola mediante `Console.ReadLine()`, y uso de marcadores de posición posicionales (`{0}`) y saltos de línea (`\n`) dentro de `Console.WriteLine()`.

### 🔹 Actividad 3: Encapsulamiento, Variables de Instancia y Propiedades
* **Clase:** `LibroCalificaciones`
* **Conceptos:** 
  * Declaración de variables de instancia con modificador `private` para la protección de datos (ocultamiento de información).
  * Implementación de un constructor explícito que recibe parámetros para inicializar el estado del objeto al instanciarlo.
  * Creación de propiedades públicas (`NombreCurso`) con descriptores `get` (retorno del valor) y `set` (asignación del valor con la palabra reservada `value`).

---

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** C# (.NET Framework / .NET 10.0)
* **Entorno de Desarrollo (IDE):** Visual Studio 2026
* **Paradigma:** Programación Orientada a Objetos (POO)
* **Control de Versiones:** Git & GitHub
