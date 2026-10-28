#Sistema de Control de Acceso#

Descripción

Este proyecto es una aplicación desarrollada en C# Windows Forms que permite controlar el ingreso de personas a un laboratorio mediante una cola de espera.

Estructura de datos utilizada

Se implementó una cola FIFO (First In, First Out), que significa que la primera persona en entrar es la primera en salir.

Se utiliza Queue<string> para almacenar los nombres de las personas que esperan ingresar al laboratorio.

También se utiliza List<string> para guardar y administrar el historial de las personas que han ingresado.

Funcionamiento

Registrar: permite agregar el nombre de una persona a la cola de espera.

Atender: permite atender a la primera persona de la cola y registrar su ingreso al laboratorio.

Cola de espera: muestra las personas que todavía están esperando.

Historial de ingresos: muestra las personas que ya ingresaron al laboratorio.

Validaciones: la aplicación muestra mensajes si se intenta registrar un nombre vacío o atender cuando no hay personas esperando.

Tecnologías utilizadas

Lenguaje de programación: C#.

Entorno de desarrollo: Visual Studio.

Interfaz gráfica: Windows Forms.

Requisitos

Tener instalado Visual Studio.

Tener instalada una versión compatible de .NET.

Contar con los archivos del proyecto.

Instrucciones para ejecutar el proyecto

Descargar o clonar este repositorio.

Abrir la solución del proyecto (.sln) en Visual Studio.

Esperar a que Visual Studio cargue el proyecto.

Seleccionar el proyecto como proyecto de inicio, si es necesario.

Presionar F5 o hacer clic en Iniciar para ejecutar la aplicación.

Escribir el nombre de una persona y presionar Registrar.

Presionar Atender para permitir el ingreso de la primera persona de la cola.
