# BOOTCAMP-JAVA-jdbc
Descripcion: Ejemplo practico de un CRUD con JDBC tradicional, donde gestionamos directamente las conexiones, 
sentencias SQL y el manejo de recursos como Connection, PreparedStatement y ResultSet. Aunque es más laborioso 
que usar ORM como JPA o Hibernate, proporciona un control detallado sobre las interacciones con la base de datos. 

### Para realizar la conexion a la BD se deben definir las siguientes variables:
- DB_URL=jdbc:postgresql://localhost:5432/${dbname}
- DB_USERNAME=postgres
- DB_PASSWORD=****

### dependencies
- org.postgresql v42.7.3
