# Docker with wordpress

***Language***
- [🇪🇸 Spanish](./README.es.md)
- 🇺🇸 English

# Indice

- [Environment variables](#Environment-variables)
- [Docker compose](#Docker-compose)
- [Refence](#Reference)

# Environment-variables

  Rename file **.envExample** to **.env**, you can modify it
  
# Docker-compose

  Run in this same directory as **docker-compose.yml**
  ```bash
  docker-compose --env-file .env up -d
  ```
  Verify by terminal
  ```bash
  docker ps
  ```
  Check with browser
  - [localhost:80](http://localhost:80)
 
  Check your mysql by terminal, write you **root password**, with this example would be **admin**
  ```bash
  docker exec -it my_mysql mysql -uroot -p
  ```

# Reference

***Docker Install***
- [Docker installation](https://docs.docker.com/engine/install/)
- [Docker compose installation](https://docs.docker.com/compose/install/)

***Docker Docs***
- [Docker Environment variables in Composer](https://docs.docker.com/compose/environment-variables/)
- [Docker compose wordpress](https://docs.docker.com/compose/wordpress/)

***Images***
- [mysql](https://hub.docker.com/_/mysql)
- [wordpress](https://hub.docker.com/_/wordpress)

***Other***
- [(Medium) Using Variables in Docker-Compose](https://medium.com/better-programming/using-variables-in-docker-compose-265a604c2006)
- [(Youtube-spanish) MySQL with Docker, step by step](https://www.youtube.com/watch?v=SgPPArUJAGs&t=1297s)
