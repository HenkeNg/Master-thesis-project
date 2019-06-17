uses Dotnet 2.3 and docker-compose

"dotnet build" to build
"dotnet publish" to publish the needed dlls to be able to use them in Docker

To bring everything up run "docker-compose up" then you will get:
- PgAdmin available at http://localhost:8081 (email: admin@vizrt.com, pass:admin). Add the server hostname: postgres, user: admin, pass: admin
- RabbitMq admin interface is available at http://localhost:15672 (user: guest, pass: guest)
- EventStore admin is available at http://localhost:2113 (user: admin, pass: changeit)
- Api is available at http://localhost:8080/api
