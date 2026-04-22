# API Rest - Inventario de productos 

API REST completa para gestionar el inventario de una tienda , construida con Spring Boot, Gradle , PostGres y dockerizada 

## Tecnologias 
- spring boot 4.0.5
- gradle
- postgresSQL
- JPA - Hibernate
- docker, Docker-compose


## Como ejecutar localmente 
´´´ bash 
# 1. clonar repositorio
git clone https://github.com/PatracaMiguel/Inventario 

# 2. entrar a la carpeta inventario
cd inventario

# 3. ejecutar con docker-compose
docker-compose up --build

## Endpoints 

| Método | Endpoint | Descripción |
| ------ | -------- | ----------- |
| GET    | /productos | Lista de productos |
| GET    | /productos/{id} | Producto especifico |
| POST   | /productos | Crear producto |
| PUT    | /productos/{id} | Modificar producto |
| DELETE | /productos/{id} | Eliminar producto |


## Descripción de la base de datos
La base de datos se crea automáticamente al iniciar el contenedor de docker-compose, y se borra al pararlo.

Base de datos: PostgreSQL (puerto 5433)

