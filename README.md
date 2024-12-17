# 📚 LiterAlura 📚
LiterAlura es una aplicación interactiva que te permite buscar, registrar y listar libros y autores de la biblioteca digital de Gutendex. Una herramienta ideal para amantes de la literatura.

## 🚀 Características Principales
1. Buscar libros por título:
Encuentra información sobre libros mediante su título y añádelos a la base de datos si no están registrados.
2. Buscar autores por nombre:
Localiza autores registrados y consulta su información, como fechas de nacimiento, fallecimiento y libros publicados.
3. Listar libros registrados:
Visualiza todos los libros guardados en la base de datos con detalles como título, autor, idioma y descargas.
4. Listar autores registrados:
Obtén un listado completo de autores junto con información detallada y sus obras asociadas.
5. Listar autores vivos en un año específico:
Identifica autores que estaban vivos en un año determinado.
6. Listar libros por idioma:
Filtra los libros registrados según su idioma (Español o Inglés).
7. Listar autores por año:
- Nacimiento: Encuentra autores nacidos en un año específico.
- Fallecimiento: Muestra autores fallecidos en un año concreto.

## 💻 Requisitos
- Java 11 o superior
- Dependencias necesarias para el uso de Spring y repositorios de base de datos (JPA, Hibernate, etc.).

## 🛠️ Tecnologías Utilizadas
- Java: Lenguaje principal de la aplicación.
- Spring Framework: Para inyección de dependencias y manejo de repositorios.
- JPA/Hibernate: Persistencia de datos en la base de datos.
- API Gutenberg: Fuente de información de libros y autores.

## 🗃️ Estructura del Código
- Principal.java: Contiene el menú interactivo y las funcionalidades principales.
- ConsumoAPI: Realiza peticiones a la API Gutenberg.
- ConvierteDatos: Convierte datos JSON a objetos Java.
- AutorRepository: Gestión de autores y libros en la base de datos.

## 📝 Próximos Desarrollos
- Añadir más filtros de búsqueda (por género, año de publicación, etc.).
- Mejorar la interfaz de usuario (GUI).

## ¡Gracias por usar LiterAlura! 📖✨
