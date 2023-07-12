# Examen-T-2023-web

Puntos a considerar:
http://localhost:8080/api/usuarios/

Para ingresar datos
{
    
    "nombre": "Ingresar Nombre",
    "correo": "correo@correo.cl",
    "password": "masde6digitos",
    "rol": "USER_ROLE"
}

#Ojo, los user role están desglosados en:
{
ADMIN_ROLE
USER_ROLE
VENTAS_ROLE
}

de todas formas, se pueden modificar en mongodb de acuerdo a los paráms que uno quiera

los datos se eliminan de acuerdo a el "user ID"
para obtener los usuarios, es lo mismo
ah, y en el caso de obtener la cantidad de usuarios, se desglosa también (tiene contador y paginador)

#Conectada a MongoDB
