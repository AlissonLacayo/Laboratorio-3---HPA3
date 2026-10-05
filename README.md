# Laboratorio # 3
Fecha: 14/09/2026

## Contenido del Repositorio
Este laboratorio abarca el diseño e implementación de aplicaciones en C# (.NET) aplicando principios de Programación Orientada a Objetos (POO), arquitectura de navegación MDI y validaciones de datos tanto en entorno de consola como en formularios de escritorio Windows Forms.

## Tecnologías Utilizadas
* **Lenguaje / Framework:** C# (.NET Framework / .NET Core)
* **Tipo de Aplicación:** Windows Forms (Escritorio) y Aplicación de Consola
* **Herramientas:** Visual Studio Insiders, GitHub

## Capturas de Pantalla y Problemas

### Ejercicio 1: Registro de Colaboradores (DataGridView)
Se implementó un formulario de captura de datos con validaciones en tiempo real mediante `ErrorProvider` para asegurar la integridad de los campos obligatorios. Se integró una clase utilitaria con expresiones regulares (`Regex`) para validar el formato de correo electrónico y un control `DateTimePicker` para la fecha de nacimiento, almacenando los datos en memoria y mostrándolos dinámicamente en un `DataGridView`.

* **Estado inicial del formulario:**
  ![Formulario en estado inicial](./imagenes/formulario-estado-inicial.png)

* **Registro exitoso de un colaborador:**
  ![Datos de empleado guardados](./imagenes/datos-empleado-guardados.png)

* **Validación de errores (ej. campo salario):**
  ![Validación de error en salario](./imagenes/validacion-error-salario.png)

---

### Ejercicio 2: Juego de Craps (Consola)
Desarrollo de la lógica del juego de azar Craps en consola utilizando la clase `Random` para simular la tirada de dados. Se implementaron enumeraciones (`enum`) para gestionar los estados del juego (Ganó, Perdió, Continúa) y estructuras `switch` para la evaluación del tiro inicial y la definición del "Punto" en tiros subsecuentes.

* **Ejecución - Partida Ganada:**
  ![Partida ganada en Craps](./imagenes/craps-partida-ganada.png)

* **Ejecución - Partida Perdida:**
  ![Partida perdida en Craps](./imagenes/craps-partida-perdida.png)

---

### Ejercicio 3: Formulario MDI
Configuración de una arquitectura de Múltiples Documentos (MDI) con un formulario contenedor Padre (`IsMdiContainer = true`) y un menú de navegación mediante el control `ToolStrip`. Se controló la apertura y enfoque de los formularios Hijos asignando la propiedad `MdiParent` y ejecutando el método `BringToFront()` para evitar la duplicación de ventanas.

* **Ventanas principal y secundaria en tamaño normal:**
  ![Ventana principal y secundaria](./imagenes/ventana-principal-y-secundaria.png)

* **Formulario secundario maximizado:**
  ![Formulario secundario maximizado](./imagenes/form2-maximizado.png)

* **Formulario secundario minimizado:**
  ![Formulario secundario minimizado](./imagenes/form2-minimizado.png)

## Estructura de Carpetas o Directorios

```plaintext
laboratorio-3-csharp/
├── CasoJuegoCraps/            # Proyecto de Consola: Lógica del juego Craps
│   ├── Program.cs             # Punto de entrada de la aplicación
│   └── Craps.cs               # Clase de negocio, enums y tiradas
├── EjemploGrid/               # Proyecto WinForms: Formulario y DataGridView
│   ├── Form1.cs               # Lógica de interfaz y eventos
│   ├── Persona.cs             # Clase modelo de entidad
│   └── Utilidades.cs          # Clase estática con validaciones Regex
├── FormularioMDI/             # Proyecto WinForms: Ventana principal MDI
│   ├── Form1.cs               # Contenedor Padre y ToolStrip
│   └── Form2.cs               # Formulario Hijo
├── imagenes/                  # Carpeta con las capturas de pantalla del proyecto
│   ├── formulario-estado-inicial.png
│   ├── datos-empleado-guardados.png
│   ├── validacion-error-salario.png
│   ├── craps-partida-ganada.png
│   ├── craps-partida-perdida.png
│   ├── ventana-principal-y-secundaria.png
│   ├── form2-maximizado.png
│   └── form2-minimizado.png
└── README.md                  # Documentación del proyecto
## Instrucciones de Ejecución / Uso
**1. Clonar el repositorio**: 
```bash
git clone [https://github.com/tu-usuario/laboratorio-3-csharp.git](https://github.com/tu-usuario/laboratorio-3-csharp.git)
```
**2. Configurar el entorno local:**
​Abrir la solución .sln en Visual Studio o la carpeta principal en Visual Studio Code

**3. Ejecutar el comando de arranque:**
​Consola: Acceder a la carpeta CasoJuegoCraps y ejecutar dotnet run.
​Windows Forms: Establecer el proyecto deseado como inicio en Visual Studio y presionar

## Autor
**​Nombre:** Alisson Lacayo  

**​Asignatura:** Herramientas de la Programación Aplicada III (.NET)

**​Grupo:** 1IL133

**​Carrera:** Licenciatura en Ingeniería en Sistemas y Computación 

​**Institución:** Universidad Tecnológica de Panamá (UTP)  

**​Fecha de Realización:** 14/09/2026  

## Referencias 
​Material didáctico del curso Herramientas de la Programación Aplicada III (UTP).
​Directrices del Resumen del Repositorio (UTP - FISC).  
