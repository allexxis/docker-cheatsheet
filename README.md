
<p align="center">
  <img src="https://miro.medium.com/max/200/1*lUNmBw_oyS2ADWqZs4DLOA.png" alt="Docker Logo">
</p>

#Docker Cheatsheet

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

