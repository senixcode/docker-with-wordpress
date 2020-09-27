# Docker con wordpress

***Idioma***
- 🇪🇸 Español
- [🇺🇸 Ingles](./README.md)

# Indice

- [Variables de entorno](#Variables-de-entorno)
- [Docker compose](#Docker-compose)
- [Referencias](#Referencias)
# Variables-de-entorno

  Renombrar el archivo **.envExample** a **.env**, tu puedes modificar este archivo
  
# Docker-compose

  Ejecuta en el mismo directorio de **docker-compose.yml**
  ```bash
  docker-compose --env-file .env up -d
  ```
  Verifica por la terminal
  ```bash
  docker ps
  ```
  Verifica por el navegador
  - [localhost:80](http://localhost:80)
 
  Verifica tu mysql por la terminal, y escribe tu **contraseña root**, Con este ejemplo seria **admin**
  ```bash
  docker exec -it my_mysql mysql -uroot -p
  ```

# Referencias

***Docker Instalación***
- [Docker installation](https://docs.docker.com/engine/install/)
- [Docker compose installation](https://docs.docker.com/compose/install/)

***Docker Documentación***
- [Docker Environment variables in Composer](https://docs.docker.com/compose/environment-variables/)
- [Docker compose wordpress](https://docs.docker.com/compose/wordpress/)

***Imagenes***
- [mysql](https://hub.docker.com/_/mysql)
- [wordpress](https://hub.docker.com/_/wordpress)

***Otros***
- [(Medium) Using Variables in Docker-Compose](https://medium.com/better-programming/using-variables-in-docker-compose-265a604c2006)
- [(Youtube-spanish) MySQL with Docker, step by step](https://www.youtube.com/watch?v=SgPPArUJAGs&t=1297s)
