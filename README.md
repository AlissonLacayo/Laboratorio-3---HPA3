# Laboratorio # 3
Fecha: 14/09/2026

## Contenido del Repositorio
Este laboratorio abarca el diseño e implementación de aplicaciones en C# (.NET) aplicando principios de Programación Orientada a Objetos (POO), arquitectura de navegación MDI y validaciones de datos tanto en entorno de consola como en formularios de escritorio Windows Forms.

## Tecnologías Utilizadas
* **Lenguaje / Framework:** C# (.NET Framework / .NET Core)
* **Tipo de Aplicación:** Windows Forms (Escritorio) y Aplicación de Consola
* **Herramientas:** Visual Studio, GitHub

## Capturas de Pantalla y Ejercicios

### Ejercicio 1: Registro de Colaboradores (DataGridView)
Se implementó un formulario de captura de datos con validaciones en tiempo real mediante `ErrorProvider` para asegurar la integridad de los campos obligatorios. Se integró una clase utilitaria con expresiones regulares (`Regex`) para validar el formato de correo electrónico y un control `DateTimePicker` para la fecha de nacimiento.

* **Estado inicial del formulario:**<br>
  <img src="./imagenes%20lab%203/formulario-estado-inicial.png" alt="Estado inicial del formulario" width="450">

* **Registro exitoso de un colaborador:**<br>
  <img src="./imagenes%20lab%203/datos-empleado-guardados.png" alt="Datos de empleado guardados" width="450">

* **Validación de errores (ej. campo salario):**<br>
  <img src="./imagenes%20lab%203/validacion-error-salario.png" alt="Validación de error en salario" width="450">

---

### Ejercicio 2: Juego de Craps (Consola)
Desarrollo de la lógica del juego de azar Craps en consola utilizando la clase `Random` para simular la tirada de dados y enumeraciones (`enum`) para gestionar los estados del juego.

* **Ejecución - Partida Ganada:**<br>
  <img src="./imagenes%20lab%203/craps-partida-ganada.png" alt="Partida ganada en Craps" width="450">

* **Ejecución - Partida Perdida:**<br>
  <img src="./imagenes%20lab%203/craps-partida-perdida.png" alt="Partida perdida en Craps" width="450">

---

### Ejercicio 3: Formulario MDI
Configuración de una arquitectura de Múltiples Documentos (MDI) con un formulario contenedor Padre y un menú de navegación mediante el control `ToolStrip`.

* **Ventana principal y secundaria en tamaño normal:**<br>
  <img src="./imagenes%20lab%203/ventana-principal-y-secundaria.png" alt="Ventana principal y secundaria" width="450">

* **Formulario secundario maximizado:**<br>
  <img src="./imagenes%20lab%203/form2-maximizado.png" alt="Formulario secundario maximizado" width="450">

* **Formulario secundario minimizado:**<br>
  <img src="./imagenes%20lab%203/form2-minimizado.png" alt="Formulario secundario minimizado" width="450">

## Estructura de Carpetas o Directorios

```plaintext
laboratorio-3-csharp/
├── CasoJuegoCraps/            # Proyecto de Consola: Lógica del juego Craps
├── EjemploGrid/               # Proyecto WinForms: Formulario y DataGridView
├── FormularioMDI/             # Ventana principal MDI
├── imagenes lab 3/            # Carpeta con las capturas de pantalla
│   ├── formulario-estado-inicial.png
│   ├── datos-empleado-guardados.png
│   ├── validacion-error-salario.png
│   ├── craps-partida-ganada.png
│   ├── craps-partida-perdida.png
│   ├── ventana-principal-y-secundaria.png
│   ├── form2-maximizado.png
│   └── form2-minimizado.png
└── README.md                  # Documentación del proyecto
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
