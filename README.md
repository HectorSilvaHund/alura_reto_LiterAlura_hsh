**Reto LiterAlura HSH**

¡Hola!  
Este es mi reto de LiterAlura para un **catálogo de libros**.  
La idea es: buscar libros en internet usando la API de **Gutendex**, guardarlos en una base de datos, y luego jugar con ellos desde la consola.  

---

¿Qué hace?

- Buscar un libro por su **título** (ej: “Pride”) → lo trae de Gutendex y lo guarda en PostgreSQL.  
- Evita duplicados 
- Listar todos los **libros** registrados.  
- Listar todos los **autores**.  
- Ver qué **autores estaban vivos en un año** (ej: 1600 → Cervantes, Shakespeare).  
- Listar libros por **idioma** (`ES`, `EN`, `FR`, `PT`).  
- Y si buscas algo raro (tipo “QOQOQO”), te avisa que no existe.  

---

¿Qué usé?

- **Java 17**  
- **Spring Boot 3** (con JPA y Web)  
- **PostgreSQL**
- **Gutendex API** (es como una biblioteca digital gratis con miles de libros)  

---

IDE: IntelliJ

---

Ejemplo de uso

Cuando lo corres, aparece este menú:

1. Buscar y registrar libro por título
2. Listar libros registrados
3. Listar autores registrados
4. Listar autores vivos en un año
5. Listar libros por idioma (ES/EN/FR/PT)
6. Salir

