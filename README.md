
# Challenge Literalura


¡Bienvenido(a) a Literalura! 📚

Literalura es una aplicación que te permite gestionar tu biblioteca personal de libros.

## ¿Qué puedes hacer con Literalura? 

- Buscar libros por título en la API

- Buscar libros por autor que se encuentre en la base de datos.

- Listar libros y autores registrados.

- Buscar autores vivos en un año específico.

- Listar libros por idioma.

- Obtener el top 10 de libros más buscados.

- Generar estadísticas sobre las descargas de libros.

## ¿Cómo funciona Literalura?

Literalura utiliza una API externa para obtener información sobre libros y autores: https://gutendex.com/ También almacena información en una base de datos local para que puedas acceder a ella incluso sin conexión a internet.

## Estructura del proyecto:

src/main/java:

com.aluracursos.challengeliteralura:

model: Contiene las clases que representan los datos de libros y autores.

repository: Contiene las interfaces y clases que se utilizan para acceder a la base de datos.

service: Contiene las clases que implementan la lógica de negocio de la aplicación.

principal: Contiene la clase principal de la aplicación.

src/main/resources: Contiene los archivos de configuración de la aplicación.

pom.xml: Contiene las dependencias del proyecto.

## Tecnologías utilizadas:

Java 17

Spring Boot 3.2.4

PostgreSQL

Maven

## Instalación

### Clona el repositorio:

git clone https://github.com/tu-usuario/tu-proyecto.git
cd tu-proyecto
Configura la base de datos PostgreSQL y actualiza las credenciales en el archivo application.properties.

### Ejecuta la aplicación:

./mvnw spring-boot:run

## Uso

![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/d96cbe48-6939-4228-a533-b3cfbe5586f9)

Buscar un libro:

Ejecuta la aplicación y selecciona la opción 1.
Ingresa el título del libro que deseas buscar.
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/fde379b2-0eb0-436f-85a7-260b59529771)

Opción dos

Busca libro por nombre del autor en la base de datos
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/734b0420-2625-4d72-afb4-360941d9f4e7)

Opción tres y cuatro

Lista libros registrados en la base de datos y la cuatro lista los autores.
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/61933028-5a05-4b81-a9a8-5f2a904c566c)

Opción cinco

Lista los autores vivos en el año que uno escoja.
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/801d2ac4-8329-4207-9ffe-44972aa799a3)

Opcion seis

Lista libros en la base de datos por los idiomas en que estan realizados
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/37b193c8-5e31-403f-95bf-7a7420b1442d)

Opción siete

Lista autores por año de nacimiento o fallecimiento
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/e5a28b70-b02f-4a22-8ea4-fe12a7e6a235)

Opción ocho

Lista los libros mas buscado que se encuentren en la base de datos
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/933ea17e-5a87-4aaa-917f-46042e972a76)

Opción nueve

Genera una estadistica de los libros buscados en donde se encuentra el promedio de descargas
![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/ec515646-3b4d-4f49-9051-784778b86c47)



![image](https://github.com/MToro2024/literalura-ch-3/assets/160083161/d497b856-23fd-4aa9-8f0f-6968160affa1)
