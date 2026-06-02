COMO CORRER ESTE PROYECTO CON ANGULAR

1) Primero corre el backend Spring Boot:
   cd C:\Users\DELL\IdeaProjects\vacunacion_seguridad_basica\vacunacion
   .\mvnw spring-boot:run

   Debe abrir en: http://localhost:8080

2) Abre otra terminal y corre el frontend Angular:
   cd C:\Users\DELL\IdeaProjects\vacunacion_seguridad_basica\vacunacion\frontend
   npm install
   ng serve

   Debe abrir en: http://localhost:4200

IMPORTANTE:
- npm install y ng serve SOLO van dentro de la carpeta frontend.
- Spring Boot va en la carpeta vacunacion, donde está pom.xml.
- Angular consume la API de Spring Boot en http://localhost:8080/api.
