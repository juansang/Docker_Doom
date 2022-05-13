# Docker_Doom
## Ejercicio de clase Docker DOOM

El objetivo de este ejercicio es levantar un servidor contiene el juego Doom apartir de un contenedor de docker. Esto lo haremos desde un equipo linux y los pasos
para lograrlo son :

## Paso 1 : Descargar y ejecutar el archivo binario 

Primero de todo hay que descargar el archivo ``https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz`` y descomprimirlo.


Para descomprir el archivo ejecutamos el comando `` tar -xf dockerdoomd.tar.gz ``



## Paso 2 : Ejecutar el docker binario descargado 

Para correr el docker binario que nos hemos descargado, ejecutamos el comando ``./dockerdoomd``
<img width="451" alt="2022-05-13 (4)" src="https://user-images.githubusercontent.com/91699247/168394661-841ce5bc-1ed1-48bc-9253-2dec8fa29d2d.png">




## Paso 3 : Conexión con VNC

Por último nos conectamos con el VNC en el puerto 5900 e introducimos la contraseña 1234, como muestra la imagen 

<img width="452" alt="2022-05-13 (5)" src="https://user-images.githubusercontent.com/91699247/168394794-82e78993-aed1-44e2-9d2a-d373333a18fb.png">



Como vemos el resultado es satisfactorio, hemos levantado el servidor y podemos jugar a Doom

<img width="454" alt="2022-05-13 (6)" src="https://user-images.githubusercontent.com/91699247/168395371-940cdc27-058a-41fb-ab6a-3c62e4f919d0.png">

