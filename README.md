# Título del Proyecto
```
Api para servicio de delivery
API DJANGO REST FRAMEWORK
```

[![screenshot.png](https://i.postimg.cc/T24Mm8yf/screenshot.png)](https://postimg.cc/yWcb4bXb)

[![screenshot1.png](https://i.postimg.cc/nVvSF6v3/screenshot1.png)](https://postimg.cc/3WxF9ffG)


## RUTAS

| METHOD | RUTA | FUNCIONALIDAD |ACCESSO|
| ------- | ----- | ------------- | ------------- |
| *POST* | ```/auth/signup/``` | _Register new user_| _All users_|
| *POST* | ```/auth/jwt/create/``` | _Login user_|_All users_|
| *POST* | ```/auth/jwt/refresh/``` | _Refresh the access token_|_All users_|
| *POST* | ```/auth/jwt/verify/``` | _Verify the validity of a token_|_All users_|
| *POST* | ```/orders/``` | _Place an order_|_All users_|
| *POST* | ```/orders/``` | _Get all orders_|_All users_|
| *GET* | ```/order/{order_id}/``` | _Retrieve an order_|_Superuser_|
| *PUT* | ```/orders/{order_id}/``` | _Update an order_|_All users_|
| *PUT* | ```/update-status/{order_id}/``` | _Update order status_|_Superuser_|
| *DELETE* | ```/delete/{order_id}/``` | _Delete/Remove an order_ |_All users_|
| *GET* | ```/user/{user_id}/orders/``` | _Get user's orders_|_All users_|
| *GET* | ```/user/{user_id}/order/{order_id}/``` | _Get user's specific order_|
| *GET* | ```/docs/``` | _View API documentation_|_All users_|



## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._


### Pre-requisitos 📋

```
Python 2x en adelante
Git
Django
Editor de codido
```

### Instalación 🔧

_Teniendo python, django y git instalados_
_Clona la repo_

```
git clone https://(link del repo)
```

_Instala los requerimientos(pip install -r requirements.txt)_
_Alojate en la carpeta raiz del proyecto y ejecuta el archivo manage.py(python manage.py runserver)_
_Entra a la url que birnda la consola_
_Y listo, disfruta de la api!!!_

```


## Construido con 🛠️


* VSC vode
* Python 3x
* Django 4

## Versionado 📌

*V.1

## Autores ✒️

* **Matias Toniolo** 

## Licencia 📄


## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
