#<span style="color:#4C8CB4">Docker Cheatsheet</span>    ![docker](https://miro.medium.com/max/100/1*lUNmBw_oyS2ADWqZs4DLOA.png "Docker image")


Para obtener una version de imagen especifica se utiliza

```bash
<imagen>:version
```

Para obtener la ultima version se puede utilizar
o solo escribir el nombre de la imagen en docker hub

```bash
<imagen>:latest
```

Para iniciar una imagen Ejemplo: nginx:latest

```bash
$ docker run nginx
```

Para listar todos los running containers

```bash
$ docker ps
```

Para listar todos los running containers y stop containers

```bash
$ docker ps -a
```

