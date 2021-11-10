# Timnet

_Proyecto final Diseño de sistema 2021_

el proyecto consiste acutalmente de 3 partes, una app de android cuyo instalador puede ser descarcago desde [Este enlace](https://github.com/dds-frd-utn/Timnet/releases/tag/v0.0.1-alpha)

un dash web que se puede acceder desde [Este enlace](https://portero-timnet.web.app) o se puede compilar con las instrucciones que estan acontinuacion

una parte de functions que va a manejar el envio de la notificaciones al usuario de los toques de timbre

y a futuro dos paneles de administrador para administrar el sistema, uno a nivel edificio/casa_ y el otro como dueños del sistema

```json
Datos logueo dash web
{
    "username":"edelsol",
    "password":"qwe123"
}
```
## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

### Pre-requisitos 📋

_Node & npm, ionic Cli, GIT_

[Ionic Environment Setup](https://ionicframework.com/docs/intro/environment)
[Installing Ionic](https://ionicframework.com/docs/intro/cli)


## Ejecutando el server ⚙️

_En el caso de la app Timnet se tiene que compilar en nativo, para esto se va a necesitar un emulador o un telefono conectado via ADB_

```
ionic cordova run android
```
_En el caso de la app Timnet-porter puede ser compilada en una web con el comando:_

```
ionic serve
```

_En el caso de la app Timnet-functions se puede compilar en local bajando el enotrno de desarrollo de firebase, pero esta ya esta subida a cloud y se puede utilizar desde ahi:_


