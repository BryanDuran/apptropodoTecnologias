# apptropodoTecnologias
# proyecto tecnologias web 2023 - Bryan Alberto Duran Cuellar 
 ![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/ebf858cf-737a-41e4-813d-810bcde8013e)


Esta es un app móvil que consume los servicios de un CRUD en java, el objetivo principal es agregar, editar, eliminar, modificar información de artropodos, se utilizo la nueva tecnología de bases de datos en la nube
llamada FIREBASE con la finalidad de tener una app que pueda utilizar los servicios en cualquier parte con el simple hecho de tener una conexión.

# Manual De Usuario

1.- Registro

Para poder utilizar esta aplicación Móvil debemos estar registrados con:
* Nombre
* Correo institucional
* Contraseña que supere los 6 caracteres

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/e7fc081c-9ed1-4dda-8efa-eed7fe0db134)

2.- Iniciar Sesión

Para poder acceder al sistema es tan sencillo simplemente tienes que seguir los siguientes pasos:
* Poner el correo institucional
* Poner Contraseña
* Darle al botón INGRESAR

Si no estas registrado basta con Selecciona el botón REGISTRARME

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/1466d40d-733c-4264-8074-e2668eb7e561)

3.- Menú 

Dentro del menú nos despliega aquellos artropodos que estan dados de alta, como podemos ver se muestran sus:
* Nombre
* Nombre Cientifico
* Clasificación 
* No. Patas

Para ello se utilzo un RecyclerView que almacena que extrae los datos de la base de datos en la nube, Como podemos ver tenemos la opcion de eliminar, editar, agregar otro artropodo e incluso una sección de busqueda para ser
más optimizada la busqueda.

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/4eae1d78-e10b-40e5-b041-cd2d45994132)

A continuación una muestra de como buscar un artropodo y vemos como se encuentra solamente el que buscamos en base a su nombre

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/8b563cb8-5767-4ffa-8968-347227dceccb)

4.- Registrar Artropodo

Para registrar un artropodo utilice un fragmento dentro de AndroidStudio con la finalidad de hacer mas sencillo el registro de este artropodo para los usuarios y tener que estar navegando entre pantallas.
Te pide los siguientes datos:

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/a0a44ab7-a77b-4d7a-b4fe-6b8984f65bf8)


5.- Modificar Artropodo

Para modificar el artropodo hacemos una petición como en las demas y obtenemos los datos del artropodo desde aquí podremos modificarlos a nuestro antojo, así como eliminar o cargar una imagen desde nuestro
dispositivo móvil esta opción fue un extra pues le da mejor visibilidad a los usuarios de los artropodos. 

Se selecciona el boton UPDATE despues de terminar y se modificaran los datos automaticamente

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/9b746439-6b41-4547-b4cf-9fbb82c410fe)

# BASE DE DATOS FIREBASE

para la base de datos se creo una con nuestra cuenta de google y android studio tiene la facilidad de tener una conexión entre ellas y hacer el consumo de los servicios mediante un adaptador que lo hace más sencillo

1.- Se creo el proyecto llamado artropodos

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/a6245f98-745b-461b-857b-451e9be6adc5)

2.- Creamos Dos coleeciones una para los artropodos y otra para los estudiantes con sus respectivos atributos

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/02ec7994-56ed-4bb2-adb5-4cdf07d9a7c2)

![image](https://github.com/BryanDuran/apptropodoTecnologias/assets/56562805/711fa181-62fe-42fa-9716-a567a7ff80fe)


# A continuación se muestra un video del uso de la app en Youtube:

https://youtu.be/M7BeI22O7fk

Muchas Gracias por su atención.

