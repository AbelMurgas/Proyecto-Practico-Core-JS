# Proyecto-Practico-Core-JS
La creación de este proyecto es con el fin de servir como practica del núcleo de Javascript como lenguaje de programación.

**Se va a tener mi solución pronto en al rama "Main"**

## Descripción del Proyecto:
Se necesita crear un Sistema de Inventario y Gestión de Usuarios en una aplicación de línea de comandos desarrollada en Node.js (Entorno de javascript en el servidor) que simula un sistema de autenticación y un sistema de gestión de inventario. El objetivo principal es proporcionar una plataforma segura y eficiente para administrar usuarios y productos, utilizando técnicas de manejo de archivos, encriptación de contraseñas y operaciones CRUD.

## Requerimientos del Sistema:
Node.js:

## Caracterìsticas 

### Manejo de Archivos:
La aplicación utiliza archivos CSV para almacenar información de usuarios y productos. Asegúrate de tener permisos de lectura y escritura en el directorio de trabajo, Además de separar las "tablas" de tu proyecto en diferentes archivos para un mejor control y manejo de los datos. A pesar de ser mejor idea usar una base de datos para facilitar las consulta de los datos, se prefiere por tema de conocimiento y práctica que las consultas sean realizadas utilizando solo código y manejo de archivos CSV. De querer practicar con otro tipo de archivo como TXT u otros se puede hacer sin problemas.

### Clasificaciòn de productos:
Las categorías y productos a manejar es a elección del desarrollador, también el cómo lo va a clasificar (numérico o alfanumérico), lo importante es que el usuario pueda clasificar sus productos en diferentes categorías, estas categorías a su vez tienen diferentes cajas (cada caja con su id) y en cada caja caven "n" cantidad del producto asociado, el usuario debe poder saber cuantos productos de un mismo tipo hay, cuantos espacios o cajas hay de una categoría, cuáles están llenas y cuáles no, poder asignar un producto a una caja, poder eliminar producto o moverlo a otra caja. Se deben definir aspectos importantes previos, como por ejemplo un listado de productos, un listado de categorías, y un listado de cajas asociado a categorías. Mientras as complejo sea tu inventario, más pondrás a prueba tu nivel y más aprenderás en el proceso.

### Encriptación de Contraseñas:
Se implementa encriptación de contraseñas utilizando la biblioteca bcrypt para garantizar la seguridad de la información del usuario. En este caso no es necesario crear un sistema de recuperación de cuenta, pero sí se debe desarrollar un sistema de usuario ADMIN, que sea el único capaz de cambiarle la contraseña a un usuario que la haya perdido.

### Interfaz de Línea de Comandos (CMD):
La interfaz de línea de comandos es fácil de usar e interactuará con el usuario para realizar operaciones como iniciar sesión, registrar usuarios y gestionar el inventario.

## Funcionalidades Básicas Que Debe Tener:

### Manejo de Archivos:
#### Almacenamiento en Archivos CSV:
La aplicación debe almacenar la información de usuarios, categorías, cajas y productos en archivos CSV. Cada entidad tendrá su propio archivo para facilitar la gestión y mantenimiento de los datos.
#### Operaciones CRUD en Archivos:
Implementa operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para todas las entidades. Permitir al usuario realizar estas operaciones garantizará un control completo sobre la información almacenada.

### Clasificación de Productos:
#### Definición de Categorías y Productos:
Permite al desarrollador definir categorías y productos a manejar. La clasificación puede ser numérica o alfanumérica según las preferencias.
#### Gestión de Categorías:
El usuario podrá asignar productos a diferentes categorías y ver cuántas cajas hay en cada categoría.
#### Gestión de Cajas:
Cada categoría puede contener varias cajas, cada una identificada por su ID. La aplicación permitirá verificar cuántas cajas hay en una categoría, identificando cuáles están llenas y cuáles no.
#### Gestión de Productos:
Permite al usuario conocer la cantidad de productos de un mismo tipo y asignar productos a cajas específicas. También se debe permitir la eliminación de productos o moverlos a otra caja.

### Encriptación de Contraseñas:
#### Encriptación Segura:
Utiliza la biblioteca bcrypt para garantizar la encriptación segura de las contraseñas de los usuarios.
#### Usuario ADMIN:
Implementa un sistema de usuario ADMIN que tiene privilegios especiales, como cambiar la contraseña de otros usuarios. Esto añade un nivel adicional de seguridad.

## Notas Adicionales:

### Validaciones:
La aplicación debe incluir validaciones para garantizar la entrada de datos correcta y prevenir posibles errores.

### Documentación:
Todo el código está documentado de manera clara para facilitar la comprensión y colaboración.

### Errores y Mensajes:
Los mensajes de error son descriptivos y proporcionan información útil para el usuario. La aplicación maneja los errores de manera elegante.
