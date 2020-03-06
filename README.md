
<p align="center">
  <img src="https://miro.medium.com/max/200/1*lUNmBw_oyS2ADWqZs4DLOA.png" alt="Docker Logo">
</p>

#Docker Cheatsheet

Obtener una version de imagen especifica se utiliza

```bash
<image>:<version>
```

Obtener la ultima version se puede utilizar
o solo escribir el nombre de la imagen en docker hub

```bash
<image>:<latest>
```

Iniciar un container Ejemplo: nginx:latest

```bash
$ docker run nginx
```

Iniciar un container en modo detach o "background"

```bash
$ docker run -d nginx
```

Attach o conectarse a un running container


```bash
$ docker attach <ID|NAME>
```

Listar todos los running containers

```bash
$ docker ps
```

Listar todos los running containers y stop containers

```bash
$ docker ps -a
```

Parar un container

```bash
$ docker stop <ID|NAME>
```

Remover un stop container

```bash
$ docker rm <ID|NAME>
```

Remover todos los stop containers

```bash
$ docker rm $(docker ps -a -q)
```

Listar todas las imagenes descargadas

```bash
$ docker images
```





