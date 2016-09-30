![jointDeveloper](https://raw.githubusercontent.com/jointDeveloper/Aprendizaje-Web/gh-pages/IMG/robot-logo.png)

# Comunidad jointDeveloper

## Dependencias

npm (https://www.npmjs.com)
```
(sudo) apt-get install npm
```

## Blog

Ref:
* http://support.ghost.org/installing-ghost-linux/
* [nginx](https://www.digitalocean.com/community/tutorials/how-to-create-a-blog-with-ghost-and-nginx-on-ubuntu-14-04)

### Instalar Ghost

* Descargar la última versión de Ghost desde Ghost.org:
```
curl -L https://ghost.org/zip/ghost-latest.zip -o ghost.zip
```

* Descomprimir Ghost dentro del directorio `/var/www/ghost`(Directorio recomendado):
```
unzip -uo ghost.zip -d /var/www/ghost
```

* Ve al nuevo directorio e instala Ghost (dependencias de producción unicamente):
```
cd /var/www/ghost && npm install --production
```

* Editar `config.js`:
Linea 14 Para pruebas locales: `http://localhost:2368`


### Starting Ghost

Para iniciar Ghost (entorno de producción), ejecuta

```npm start --production```


### Instalación del Tema

* Descomprimir el tema en la carpeta "content/themes" de la instalación de Ghost.

* Ve al administrador de Ghost, y en "settings/general/themes" selecciona joint-theme

___
#### _Más Información_

<a href="https://github.com/jointDeveloper/"><img src="https://raw.githubusercontent.com/jointDeveloper/media/master/social-icon/github.png" alt="Github-jointDeveloper" /></a>
<a href="https://facebook.com/jointDeveloper/"><img src="https://raw.githubusercontent.com/jointDeveloper/media/master/social-icon/facebook.png" alt="Facebook-jointDeveloper" /></a>
<a href="https://twitter.com/jointdev"><img src="https://raw.githubusercontent.com/jointDeveloper/media/master/social-icon/twitter.png" alt="Twitter-jointDeveloper" /></a>
<a href="https://instagram.com/jointdeveloper/"><img src="https://raw.githubusercontent.com/jointDeveloper/media/master/social-icon/instagram.png" alt="Instagram-jointDeveloper" /></a>
<a href="mailto:developerjoint@gmail.com"><img src="https://raw.githubusercontent.com/jointDeveloper/media/master/social-icon/email.png" alt="E-mail-jointDeveloper" /></a>
<a href="https://jointdeveloper.github.io/Aprendizaje-Web/"><img src="https://raw.githubusercontent.com/jointDeveloper/media/master/social-icon/internet.png" alt="Web-jointDeveloper" /></a>
___
