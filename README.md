En este repositorio se hara entrega del taller 4 y 5, los cuales consistian en conexion de base de datos y encriptado y desencriptado, mas adelante se veran los resultados
de las conexiones de la base de datos y el ejercicio de encriptar y desencritar una contraseña:

TALLER 4 CONEXION BASE DE DATOS
En este apartado se veran las 4 maneras de conectar una base de datos desde la peor hasta la mejor:
![Conexion 1](https://user-images.githubusercontent.com/113126709/236562660-0df6a86d-75db-442d-ba95-724f20317426.png)
en la imagen se ve la primera forma de conectar una base de datos a un proyecto, es la forma mas basica que exite que es usando una clase de java llamada BasicConnection
en la cual se llama a la base de datos y al usuario de aquella base de datos 

![Conexion 2](https://user-images.githubusercontent.com/113126709/236562879-7142f1ac-6d5c-46a1-8bc0-d4eecf295e64.png)
En la segunda forma se utiliza una clase de java llamada BasicConnectionWithResources donde tambien se llama a la base de datos con un usuarui y una contraseña

![Conexion 3](https://user-images.githubusercontent.com/113126709/236563548-94af0247-db65-4cbd-a9ad-5a37a4477ed1.png)
En la tercera forma se utiliza dos clases de java una es BasicConnectionSingleton y la otra UseBasicConnectionSingleton, lo que hace diferente esta forma es que 8usa 2 
archivos para conectar y usar la base de datos 

![Conexion 4](https://user-images.githubusercontent.com/113126709/236563830-6fc1957e-563a-474a-994f-922328015416.png)
La cuarta forma cosiste en agregar una dependencia en el archivo pom.xml en la cual se especificara la version de nuestro gestor de base d datos y crear una clase java
llamada ConnectionPool en la cual se llamara a la base de datos con el usuario y contraseña

TALLER 5 ENCRIPTADO Y DESENCRIPTADO

Lo primero que nos pide este taller es cambiar el valor de la contraseña de varchar a varbinary
![TALLER 5 MODIFICACION DE DATO](https://user-images.githubusercontent.com/113126709/236564486-24873daa-a87b-40e9-b5f0-cbdfc6ca7a3b.png)

luego ingresar un usuario con su respecriva contraseña, pero a esta contraseña se le añadira un hash de encriptacion
![Taller 5 encriptado](https://user-images.githubusercontent.com/113126709/236565010-86f205c9-1540-4f2a-97db-7c95a04864d9.png)

Luego de agregar el hash y encriptar la contraseña vamos a desencriptar la contraseña que pusimos 
![taller 5 descencriptado](https://user-images.githubusercontent.com/113126709/236565119-e0bfcbcf-bb06-4c5e-bdcb-ab27076756b4.png)

y este seria el resultado de los talleres 4 y 5 

Gracias Por Su Atencion
