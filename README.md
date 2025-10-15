# TallerLambda
1. Creamos una nueva clase para este taller

![alt text](img/image.png)

2. Le creamos un metodo de prueba, que en este caso es el de login

![alt text](img/image-1.png)

3. En Aws creamos la funcion Lambda

![alt text](img/image-2.png)

4. Una vez creada la funcion lamda subimos el archivo .jar

![alt text](img/image-3.png)

5. cambiamos el controller, para que sepa a que meto debe de dirigirse, como vemos en la imagen, va dirigido a la clase de SecurityUtils y va al metodo login

![alt text](img/image-4.png)

6. una vez hecho hacemos una prubea en la mismo apartado de Lambda

![alt text](img/image-5.png)

7. Podemos ver que si esta correcto la prueba por dos cosas, la primera arroga un stado 200 y retorna la contraseña vacia porque asi la pusimos 

![alt text](img/image-6.png)

8. ahora vamos a crear el apiGateway, pero usamos el que ya tenemos de esta misma clase, por lo que debemos de crear el recurso

![alt text](img/image-7.png)

9. creamos un metodo Get para poder probar

![alt text](img/image-8.png)

10. Le añadimos los parametros de "username" y "password"

![alt text](img/image-9.png)

11. en la plantilla de asignacion, osea el formato JSON, tambien debemos de poner las variables que pusimos anteriormente
 
![alt text](img/image-10.png)

12. Hacemos la prueba en el apiGateway y podemos observar que si funciona

![alt text](img/image-11.png)

