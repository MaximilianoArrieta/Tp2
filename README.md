Trabajo Práctico N°2 - Programación III
Este proyecto es una aplicación web desarrollada con Blazor WebAssembly (WASM) Stand-Alone utilizando .NET 10.0. El objetivo de la actividad es poner en práctica la creación de componentes reutilizables, gestión de modelos de datos, ciclos de vida de componentes y lógica de validación en el cliente.

Tecnologías Utilizadas
Framework: .NET 10.0 (Blazor WebAssembly)

Estilos: Bootstrap 5 (Integrado para diseño responsivo)

Lenguaje: C# / Razor

Funcionalidades del Proyecto
1. Modelado de Datos
Se implementó la clase Persona en la carpeta Models, que incluye propiedades como:

ID, Nombre Completo, Email, Domicilio, Fecha de Nacimiento y Ruta de Imagen.

2. Lista de Personas (/lista-personas)
Página que visualiza una tabla de 10 personas generadas dinámicamente mediante el método de ciclo de vida OnInitialized.

Uso de ciclos @foreach para el renderizado.

Diseño optimizado con tablas de Bootstrap.

3. Componentes Reutilizables
Componente Saludo: Un componente dinámico que acepta un parámetro [Parameter] string Nombre para mostrar un mensaje de bienvenida personalizado.

Implementación en Home: Se instanció el componente cuatro veces con diferentes nombres para demostrar la reutilización.

4. Control de Acceso (Login)
Interfaz de acceso con lógica de validación local:

Usuario: alumno

Contraseña: 1234

Incluye feedback visual mediante alertas de éxito o error tras el intento de ingreso.
