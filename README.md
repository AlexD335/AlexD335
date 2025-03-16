# Title 1
## Hi there, I'm Alex 👋

~~~cs
string name = "Alex";
~~~

**AlexD335/AlexD335** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

# Gestión de Tareas - Aplicación de Escritorio en C#

Este proyecto es una aplicación de escritorio desarrollada en C# que permite a los usuarios gestionar tareas, categorías y estados. La aplicación se conecta a una base de datos SQL Server para almacenar y recuperar información.

## Características Principales

- **Gestión de Tareas**: Los usuarios pueden agregar, editar y eliminar tareas.
- **Categorías**: Las tareas pueden ser organizadas en categorías personalizadas.
- **Estados**: Las tareas pueden tener diferentes estados (por ejemplo, "Pendiente", "En Progreso", "Completado").
- **Autenticación de Usuarios**: Los usuarios pueden registrarse e iniciar sesión para acceder a sus tareas.
- **Interfaz Gráfica**: La aplicación cuenta con una interfaz gráfica intuitiva desarrollada con Windows Forms.

## Requisitos del Sistema

- **.NET Framework**: Asegúrate de tener instalado .NET Framework 4.7.2 o superior.
- **SQL Server**: La aplicación utiliza una base de datos SQL Server. Asegúrate de tener SQL Server instalado y configurado.
- **Visual Studio**: Se recomienda utilizar Visual Studio 2019 o superior para abrir y compilar el proyecto.

## Configuración del Proyecto

### 1. Base de Datos

1. **Crear la Base de Datos**: Ejecuta el script SQL proporcionado en la carpeta `DatabaseScripts` para crear la base de datos y las tablas necesarias.
2. **Configurar la Cadena de Conexión**: Modifica la cadena de conexión en la clase `ConexionDB` para que apunte a tu instancia de SQL Server.

   ```csharp
   private static readonly string cadenaConexion = "Data Source=TU_SERVIDOR; Initial Catalog=TareasDB; Encrypt=False; TrustServerCertificate=True;";
