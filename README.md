<a name="readme-top"></a>

<div align="center">
    ## Hub MegaPeliculas

   
    
    Este proyecto fue generado con Angular CLI versión 18.1.0
</div>

![Badge in progress](https://img.shields.io/badge/STATUS-DONE-green)

<details>
    <summary>Tabla de contenido</summary>

    - [Descripcion del proyecto](#descripcion-del-proyecto)
    - [Objetivos](#objetivos)
    - [Programas utilizados](#programas-utilizados)
    - [Instrucciones para descargar y ejecutar](#instrucciones-para-descargar-y-ejecutar)
    - [Descripcion del como se hizo](#descripcion-del-como-se-hizo)
    - [Diagrama Entidad-Relacion](#diagrama-entidad-relacion)
    - [Posibles mejoras futuras](#posibles-mejoras-futuras)
    - [Sprint review](#sprint-review)
    - [Imagenes de testing](#imagenes-de-testing)
    - [Documentacion de la API](#documentacion-de-la-api)
    - [Contribuyentes al proyecto](#contribuyentes-al-proyecto)

</details>

# Descripcion del proyecto

El presente trabajo, realizado en colaboración con un equipo de compañeros, expone el desarrollo completo de un Hub de Películas, desde su desarrollo inicial hasta su implementación final. Este hub fue desarrollado utilizando una API en ASP.NET con C# como lenguaje principal, y los datos se gestionaron a través de una base de datos en SQL Server. Se realizaron pruebas exhaustivas mediante Swagger para garantizar la correcta funcionalidad y la estabilidad del sistema. Este proyecto fue creado desde sus cimientos, permitiendo un enfoque integral en cada etapa del desarrollo, lo que permitió asegurar una implementación robusta y eficiente.

# Objetivos
* Implementar un proyecto productivo con Kubernetes.
* Mejorar el Hub de películas.  
* Normalización de la BD.
* Realizar una Api con ASP .net o Net core.
* Aplicación de Docker.

# Programas utilizados
* Angular 18
* Tailwind CSS
* C# Asp.net
* SQL Server
* JWT
* Swagger

# Instrucciones para descargar y ejecutar

### Angular
El primer paso, y el más importante, es clonar el repositorio remoto para ejecutarlo localmente.

```
git clone [URL del repositorio]
```

A continuación, el siguiente paso será instalar las dependencias y módulos necesarios para que el proyecto funcione correctamente.

```
npm install o npm i
```

Para ejecutar la funcionalidad principal del programa, deberás ejecutar el siguiente comando en la terminal:

```
ng serve --open
```

### ASP.NET
Como primer paso es clonar el repositorio.

```
git clone [URL del repositorio]
```


# Para el Backend
Se coloca el backend que fue trabajado en equipo y colocamos el link de Hub ya que es demasiado pesado.
https://github.com/AldairOrtiz-Kanako/Back_Peliculas_2.0.git


# Para el Front
Se coloca el front que fue trabajado en equipo y colocamos el link de Hub ya que no se podia subir el repo aparte 
https://github.com/AldairOrtiz-Kanako/Hub_Peliculas_2.0

# Descripcion del cómo se hizo

1. Planificación Inicial: El proyecto comenzó con una sesión de brainstorming en la que se acordaron las características esenciales del Hub de Películas. Se definieron las funciones clave y se dividió el trabajo entre los miembros del equipo para maximizar la eficiencia y cumplir con los plazos establecidos.
2. Diseño y Desarrollo de la Base de Datos: Se diseñó una base de datos en SQL Server que incluyó stored procedures para optimizar el rendimiento y asegurar la integridad de los datos. También se implementó una función de hashing para las contraseñas de los usuarios, garantizando así la seguridad de la información almacenada. La base de datos fue normalizada para evitar redundancias y asegurar la consistencia de los datos.
3. Se desarrolló el backend utilizando C# con .NET Core. Para asegurar su correcto funcionamiento, se añadieron las credenciales, módulos y controladores necesarios. Posteriormente, se realizaron pruebas en Swagger, las cuales confirmaron que todo operaba de manera satisfactoria.
4. Se trabajó en el frontend utilizando Angular, mejorando los componentes y realizando ajustes para optimizar la experiencia visual. Además, se estableció la conexión con la API, lo que permitió visualizar los archivos almacenados en la base de datos. Por otro lado, se implementaron funciones en el módulo de inicio de sesión y registro para garantizar la seguridad de los datos ingresados. Se verificó también que las funciones implementadas guardaran correctamente la información en la base de datos.
5. Se realizaron pruebas (testing) en el proyecto de Angular, lo que nos permitió mejorar los resultados.
6. En el uso de Docker, se implementaron todos los requisitos necesarios para construir las imágenes; sin embargo, no se logró cumplir completamente con los objetivos previstos.
7. No se pudo implementar el uso de Kubernetes.

# Diagrama Entidad-Relación

Relaciones:
- Usuarios -> Favoritos: Relación uno a muchos. Un usuario puede tener múltiples favoritos.
- Películas -> Favoritos: Relación uno a muchos. Una película puede estar en la lista de favoritos de varios usuarios.
- Series -> Favoritos: Relación uno a muchos. Una serie puede estar en la lista de favoritos de varios usuarios.
- Películas -> Director: Relación muchos a uno. Una película tiene un director, pero un director puede tener varias películas.
- Series -> Director: Relación muchos a uno. Una serie tiene un director, pero un director puede dirigir varias series.
- Películas -> Género: Relación muchos a uno. Una película pertenece a un género, pero un género puede aplicarse a varias películas.
- Series -> Género: Relación muchos a uno. Una serie pertenece a un género, pero un género puede aplicarse a varias series.

Este modelo es útil para una aplicación que maneja información sobre películas y series, permitiendo a los usuarios agregar contenido a su lista de favoritos, y categorizando dicho contenido por género y director.

![entidad-relacion](https://github.com/user-attachments/assets/481f24e9-32e9-42f7-ba7b-0385d538b9dd)




# Creacion de la BD

![creacionBD](https://github.com/user-attachments/assets/79119ee9-ee01-4059-b8bc-5804b3d9e375)





# Funcionamiento de Swagger
 ![SWAGGER](https://github.com/user-attachments/assets/f7782d18-1858-4557-a2f8-04451b50da88)
 ![Funcionamientoswagger](https://github.com/user-attachments/assets/95db54b8-d457-492e-a386-05dce3ad9ac5)



# Funcionamiento del Hub
![1](https://github.com/user-attachments/assets/223186c2-4c29-456e-9040-7ddb87aa813a)
![2](https://github.com/user-attachments/assets/782b3c52-0f07-4853-a373-7b8f9aa81523)
![3](https://github.com/user-attachments/assets/f6426d2c-66c3-41fd-acd3-0145ad67da4f)
![4](https://github.com/user-attachments/assets/34ee2911-db6b-4ad2-b827-44cd70471955)
![5](https://github.com/user-attachments/assets/6b0e7754-6157-451a-94c0-c085b8a19d81)
![6](https://github.com/user-attachments/assets/5f01ebdd-a78e-4a79-9117-ba8912f8efd9)
![7](https://github.com/user-attachments/assets/7c7d3df1-5000-4bb1-b209-3a2115f93ac3)



# Posibles mejoras futuras

1- Que se agreguen las peliculas correctamente a favoritos y poder Eliminarlas
2- implementar un modal para al dar click en la pelicula se amplie y muestre la sinopsis completa
3- implementar la barra de busqueda
4- Implementar el boton de recordar cpassword

# Sprint review
  ¿Qué Salió Bien?    
  El aspecto de nuestra aplicacion mejoro bastante ya que las entregas que hicimos anteriormente era muy simple, funciono ya nuestro backend correctamente, ya podemos registrarnos y loggearnos correctamente
  asi como tambien mostrar todas las peliculas  y series que se encuentran en nustra base de datos 
 
 ¿Qué Puedo Hacer Diferente? 
   Puedo implementar mejores fucniones dentro de nuestro hub de peliculas , asi como tambien usar correctamente docker y kubernetes 
 
 ¿Qué No Salió Bien? 
 Implementar las imagenes de docker y kubernetes , ya que al momento de crear las imagenes de DockerFile nos arrojaba error a la hora de querer cargarlas
 No agregamos la barra de busqueda dentro de nuestro Hub de peliculas , asi como tambien nos falta implementar correctamente el boton de agregar a favoritos 

# Error de docker
![imagen error docker](https://github.com/user-attachments/assets/9c4c7b4c-c0f8-41dd-82f9-cf3f43950f16)

# Documentacion de la API

<img src="Captura de pantalla 2024-08-25 192909.png" alt="Karma" whith="5vw">

Code coverage 

<img src="coverage.png" alt="coverage" whith="5vw">
>>>>>>> b37fcbad23d445baad56bf66c81b748c963bbff9

# Contribuyentes al proyecto

| [<img src="https://avatars.githubusercontent.com/u/116055107?v=4" width=115><br><sub>Montserrat Aguilar Valle</sub>](https://github.com/montsegv-2) | [<img src="https://avatars.githubusercontent.com/u/175365956?v=4" width=115><br><sub>Carlos Aldair Ortiz</sub>](https://github.com/AldairOrtiz-Kanako) | [<img src="https://avatars.githubusercontent.com/u/175587873?v=4" width=115><br><sub>K. Julieta Jiménez García</sub>](https://github.com/Julieta171) | [<img src="https://avatars.githubusercontent.com/u/179277918?v=4" width=115><br><sub>Emmanuel Salcedo</sub>](https://github.com/EmmanuelDev97)
| :---: | :---: | :---: | :---: |


<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
