# API-CRUD



# Paso 1 - Iniciar sesion para generar el token del usuario 
<br>

![img_1](img/post_login.PNG)

<br>

# Paso 2 - Peticion GET servicios disponibles
- En el apartado de Authorization -> bearer token - Colocar el token generado en /login para poder llamar mediante una peticion GET a los servicios disponibles 


<br>

![img_1](img/get_servicios_token.PNG)

<br>

# Paso 3 - Nuevo servicio POST
- Agregar un nuevo servicio mediante Peticiones POST y agregando un cuerpo en Body de tipo JSON

```cmd
{
 "nombre": "Ciberseguridad",
 "entidad": "DEFENSA",
 "prioridad": "ALTA"
}

```

<br>

![img_1](img/post_agregar_servicio_token.PNG)

<br>


<br>

![img_1](img/put_editar_servicio_token.PNG)

<br>


<br>

![img_1](img/delete_borrar_servicio_token.PNG)

<br>



