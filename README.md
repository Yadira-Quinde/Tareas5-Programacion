# Deber 5 de Programación
## Descripción de lo que hace el código
El presente proyecto realizado en la aplicación principal JavaFX muestra los resultados de la base de datos Fórmula 1 y permite al usuario seleccionar un año de un "ComboBox" para actualizar la tabla de resultados los conductores. La interfaz incluye columnas para el nombre del conductor (Driver name), victorias (Wins), puntos (total points) y rango (Rank). 

La misma que tambien está administrada por un repositorio "DriverResultRepository" que extrae datos de una base de datos PostgreSQL. Las categorías de modelo ("Circuit", "Constructors", "DriverResult") representan entidades de base de datos, mientras que los repositorios ("CircuitRepository", "ConstructorsRepository", "DriverResultRepository", "SeasonRepository") manejan la interacción con los datos de la base de datos, cómo recuperarlos años disponibles, resultados de pilotos, los constructores, y detalles de circuitos. Estos componentes trabajan vinculandose para mostrar datos relevantes de Fórmula 1 en la interfaz de usuario.

Aunado a esto, el código incluye varias funciones y estructuras adicionales. En la aplicación JavaFX, la organización de los componentes se realiza mediante **HBox** y **Vbox**, que permiten un diseño ordenado y responsivo de la interfaz de usuario. El **TableView** se configura dinámicamente con datos provenientes de la base de datos, lo que permite una actualización en tiempo real según la selección del año.
![image](https://github.com/Yadira-Quinde/Tareas5-Programacion/assets/168947646/a6eec646-cd48-4a3e-97e6-ab436c51c9e0)

###Consulta del año 1995 y 2005
![image](https://github.com/Yadira-Quinde/Tareas5-Programacion/assets/168947646/d47f8022-e146-40da-b7b3-d4695fe397a8)
![image](https://github.com/Yadira-Quinde/Tareas5-Programacion/assets/168947646/0171928a-5f21-4e24-8ce4-08bf71166712)
