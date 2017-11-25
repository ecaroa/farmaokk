Farmasoft
====================
Introduccion
---------------
Sistema de consultas por alumnos del IFST 18, el objetivo 
fue actualizar el programa que venia utilizando una drogueria. 
+ Alumna: Eliana Carolina Aguilera
+ Profesor: Leandro E. Colombo Viña.


 Flujo del Programa
  ----------------
Como pagina de bienvenida se puede ver la barra de navegacion que estará en todas las paginas del sitio, la misma mostrara donde los usuarios registrados pueden ingresan con su nombre
de usuario y clave y la posibilidad de registrarse para los usuarios nuevos.
Una vez logueado, se muestran las últimas ventas,se pueden realizar cualquiera de las 4 consultas:Productos por Cliente,Clientes por Producto, Productos más vendidos, 
Clientes que más gastaron.


Estructura del Programa
----------------

principal.py : Archivo principal de la aplicacion, contiene los enrutamientos del programa.

formulario.py: Archivo que contiene todos los formularios utilizados en la aplicacion

archivo.py : Archivo que lee la base de datos y busca errores

templates: Carpeta que contiene los archivos htmls utilizados.

csv: Carpeta que contiene la base de datos y el csv donde se guardaran los datos de los usuarios que se registraran.


Requisitos
------------------

Tener Python 3 y Flask nuestro sistema operativo, con las siguientes extensiones:
+ Flask-Bootstrap
+ Flask_WTF
+ Flask-Script
+ VirtualEnv 
