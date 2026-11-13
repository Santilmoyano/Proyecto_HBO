Podemos crear una interfaz mas atractiva para el usuario utilizando las 10 mejores películas.

Problema de negocio: La amplia cantidad de opciones del catalogo puede dificultar la rapida elección del usuario y por lo tanto disminuir la retención.

En este proyecto propongo desarrollar una interfaz que destaque las 10 peliculas mejor valoradas y las presente de forma atractiva.

stack tecnológico: SQL, PostgreSQL, DBeaver, GithHub.

Metodología CRISP-DM
El proyecto se desarrolló tomando como referencia la metodología CRISP-DM.
- Comprensión del negocio: se definió como objetivo mejorar la experiencia de navegación de HBO Max mediante la identificación de películas mejor valoradas.
- Comprensión de los datos: se utilizó un dataset de películas de HBO Max obtenido de Kaggle.
- Preparación de los datos: se seleccionaron los registros y atributos necesarios para el análisis y se organizó la información para su almacenamiento.
- Modelado: se diseñó una estructura relacional y se implementó en PostgreSQL.
- Evaluación: se ejecutaron consultas SQL para identificar las 10 películas mejor valoradas.
- Despliegue: se documentaron los resultados y se presentó una propuesta de mejora para la plataforma.

Organización por SPRINTS
El desarrollo se organizó mediante 3 sprints de trabajo, dividiendo el proyecto en entregas pequeñas y manejables.

Cada sprint tuvo objetivos concretos y entregables definidos, permitiendo evaluar los avances y realizar ajustes durante el desarrollo.

Los detalles de la metodogia de trabajo usada estan en la seccion nota metodologica del proyecto.

Hallazgo principal: Destacar las 10 mejores peliculas puede ayudar a los usuarios a identificar rapidamente contenido de alta valoración.

Instrucciones para ejecutar el proyecto:
-Clonar el repositorio: descargar el proyecto desde GitHub o clonar el repositorio utilizando Git.
-Instalar PostgreSQL: verificar que PostgreSQL se encuentre instalado y funcionando en el equipo.
-Abrir DBeaver: iniciar DBeaver y establecer una conexión con el servidor PostgreSQL.
-Crear la base de datos: crear una nueva base de datos destinada al proyecto HBO Max.
-Ejecutar el script de creación: abrir el archivo SQL correspondiente y ejecutar las sentencias para crear las tablas y relaciones de la base de datos.
-Cargar los datos: ejecutar el script de inserción para incorporar los registros de películas.
-Ejecutar la consulta: ejecutar las sentencias para obtener las 10 películas mejor valoradas.
