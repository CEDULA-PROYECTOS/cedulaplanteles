**1.- SISTEMA WEB DENOMINADO CEDULA DE PLANTELES**

**Dependencia Estatal:** Instituto de Estudios de Bachillerato del Estado de Eaxaca (IEBO)

**Link: http://sistemas.iebo.edu.mx/cedulaplanteles/**

**Descripción del sistema:** Gestionar la información de infraestructura, equipamiento, datos de las comunidades, localización de planteles, proyectos productivos, albergues, cocinas comunitarias, datos del predio, la seguridad, geográfica e imágenes donde se ubican cada uno de los 262 planteles del IEBO. Así mismo permite la generación de consultas, reportes y graficas de los datos e información almacenada en el sistema.

**2.- USUARIOS (BENEFICIOS):**

**1.- Directores de planteles:** Les permite acceder a la información relacionada con el plantel a su cargo, para actualizarla o validarla de forma anual o semestral.  
**2.- Administrativos:** Le permite generar gestionar usuarios, contraseñas, así como consultas, reportes y gráficas para articular los elementos y mecanismos necesarios para conocer la operación, desarrollo, fortalecimiento y mejora de los planteles IEBO en el Estado. Esto contribuye a la integración de propuestas de mejoras para los planteles a través de los diferentes programas de financiamiento tanto federales, estatales y municipales.  
**3.- Usuarios de consulta:** Les permite acceder a la información de cada plantel, también para generar consultas o reportes de datos de los planteles desde cualquier lugar con acceso a internet; y así contribuir con información en los procesos administrativos.

**3.- CARACTERÍSTICAS DEL SISTEMA:**

1.- Se genera una bitácora en el sistema para el control de actualizaciones realizadas por los directores de planteles, registrando el campo y valor asignado, así como la fecha y hora realizada, permitiendo evaluar el desempeño y puntualidad de los directores. 

2.- Proveer de información sobre los planteles a los usuarios administrativos o de consulta para la toma de decisiones.

3.- Contribuye a la generación e integración de propuestas de mejoras en infraestructura y equipamiento para los planteles a través de los diferentes Programas de Financiamiento tanto Federales, Estatales, Municipales u organizaciones privadas. 

**4.- TECNOLOGIAS UTILIZADAS:**

**1.- Frontend:**
* HTML5
* CSS3
* JavaScript 
* jQuery 1.2.6
* highcharts: https://www.highcharts.com/
* Bootstrap (En formato general) https://getbootstrap.com/

**2.- Backend:**
* PHP 8.3.14
* MySQL 9.1
* Servidor HTTP Apache  


**5.- CONFIGURACIÓN DE LA BASE DE DATOS:**   
1.- Nombre de la base de datos: **cedulaplanteles**  
2.- Cotejamiento: **utf8mb4_0900_ai_ci**  	

**6.- ESTRUCTURA DEL PROYECTO**

**cedulaplanteles/**

├───2014A   
├───Bibliotecas  
│&emsp; &emsp; ├───code     
│&emsp; &emsp; ├───css  
│&emsp; &emsp; └───js         
├───clases  
├───css  
│&emsp; &emsp; └───images  
├───documentos  
│&emsp; &emsp; ├───18  
│&emsp; &emsp; ├───19  
│&emsp; &emsp; ├───20  
│&emsp; &emsp; └───21  
├───images  
│&emsp; &emsp; └───css  
│&emsp; &emsp; &emsp; &emsp;  └───images  
├───importar_datos  
├───js  
├───librerias  
│&emsp; &emsp; ├───blueimp  
│&emsp; &emsp; │&emsp; &emsp;  ├───images  
│&emsp; &emsp; │&emsp; &emsp;  ├───tests  
│&emsp; &emsp; │&emsp; &emsp;  └───example  
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&ensp;├───files  
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&ensp;├───thumbnails           
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&ensp;└───scripts  
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───archivos_oficios                
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───archivos_programas_federales     
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───documentos_juridicos     
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───formato_predio  
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───fotos_danos_plantel  
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───guion_proyectos         
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───macrolocalizacion     
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;├───microlocalizacion  
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;└───proyecto_productivo          
│&emsp; &emsp; ├───ckeditor  
│&emsp; &emsp; │&emsp; &emsp;├───adapters  
│&emsp; &emsp; │&emsp; &emsp;├───images  
│&emsp; &emsp; │&emsp; &emsp;├───lang  
│&emsp; &emsp; │&emsp; &emsp;├───plugins     
│&emsp; &emsp; │&emsp; &emsp;├───skins  
│&emsp; &emsp; │&emsp; &emsp;│ &emsp; &emsp;&ensp;├───kama  
│&emsp; &emsp; │&emsp; &emsp;│ &emsp; &emsp;&ensp;│&emsp;&emsp;└───images  
│&emsp; &emsp; │&emsp; &emsp;│ &emsp; &emsp;&ensp;├───office2003  
│&emsp; &emsp; │&emsp; &emsp;│ &emsp; &emsp;&ensp;│&emsp;&emsp;└───images  
│&emsp; &emsp; │&emsp; &emsp;│ &emsp; &emsp;&ensp;└───v2  
│&emsp; &emsp; │&emsp; &emsp;│ &emsp; &emsp;&emsp; &emsp;&emsp;└───images  
│&emsp; &emsp; │&emsp; &emsp;├───themes  
│&emsp; &emsp; │&emsp; &emsp;│ &emsp; └───default  
│&emsp; &emsp; │&emsp; &emsp;├───_samples     
│&emsp; &emsp; │&emsp; &emsp;└───_source  
│&emsp; &emsp; │&emsp; &emsp; &emsp; ├───adapters  
│&emsp; &emsp; │&emsp; &emsp; &emsp; ├───core     
│&emsp; &emsp; │&emsp; &emsp; &emsp; ├───lang  
│&emsp; &emsp; │&emsp; &emsp; &emsp; ├───plugins  
│&emsp; &emsp; │&emsp; &emsp; &emsp; ├───skins         
│&emsp; &emsp; │&emsp; &emsp; &emsp; └───themes             
│&emsp; &emsp; ├───datagrid  
│&emsp; &emsp; ├───editinplace  
│&emsp; &emsp; │&emsp; &emsp;  ├───demo  
│&emsp; &emsp; │&emsp; &emsp; │&emsp; &emsp;&nbsp;├───css  
│&emsp; &emsp; │&emsp; &emsp; │&emsp; &emsp;&nbsp;├───images  
│&emsp; &emsp; │&emsp; &emsp; │&emsp; &emsp;&nbsp;└───js  
│&emsp; &emsp; │&emsp; &emsp; └───src  
│&emsp; &emsp; ├───eyedatagrid-1.1  
│&emsp; &emsp; │&emsp; &emsp;  └───images  
│&emsp; &emsp; ├───facyBox  
│&emsp; &emsp; │&emsp; &emsp;  ├───demo  
│&emsp; &emsp; │&emsp; &emsp;  └───images  
│&emsp; &emsp; ├───grafica _css  
│&emsp; &emsp; │&emsp; &emsp;  ├───images  
│&emsp; &emsp; │&emsp; &emsp;  └───stylesheets  
│&emsp; &emsp; ├───jquery.ad-gallery  
│&emsp; &emsp; │&emsp; &emsp;  └───images  
│&emsp; &emsp; │&emsp; &emsp; &emsp; &emsp;&nbsp;└───thumbs  
│&emsp; &emsp; ├───jquery_lightbox  
│&emsp; &emsp; │&emsp; &emsp;  ├───assets  
│&emsp; &emsp; │&emsp; &emsp;  ├───examples  
│&emsp; &emsp; │&emsp; &emsp;  ├───help      
│&emsp; &emsp; │&emsp; &emsp;  ├───javascript     
│&emsp; &emsp; │&emsp; &emsp;  └───psd  
│&emsp; &emsp; ├───map  
│&emsp; &emsp; │&emsp; &emsp;  └───images         
│&emsp; &emsp; ├───pro_dropdown_2  
│&emsp; &emsp; ├───subir-fotos  
│&emsp; &emsp; │&emsp; &emsp;  └───phpuploader         
│&emsp; &emsp; ├───subir-fotos2  
│&emsp; &emsp; │&emsp; &emsp;  ├───css  
│&emsp; &emsp; │&emsp; &emsp;  ├───fonts  
│&emsp; &emsp; │&emsp; &emsp;  ├───images     
│&emsp; &emsp; │&emsp; &emsp;  └───js  
│&emsp; &emsp; └───tokeninput  
│&emsp; &emsp; &emsp; &emsp;  ├───examples  
│&emsp; &emsp; &emsp; &emsp;  ├───src  
│&emsp; &emsp; &emsp; &emsp;  └───styles  
├───municipios_oaxaca  
│&emsp; &emsp; ├───css  
│&emsp; &emsp; ├───images  
│&emsp; &emsp; ├───js  
│&emsp; &emsp; └───librerias   
├───proyectos_educativos  
│&emsp; &emsp; └───informacion_geografica  
└───reportes  
&emsp; &emsp; ├───font      
&emsp; &emsp; ├───fpdf     
&emsp; &emsp; ├───fpdf-2      
&emsp; &emsp; ├───tcpdf      
&emsp; &emsp; └───tmp  
  
**Configuración de permisos:**
cd /var/www/html
git clone https://github.com/hugosantiagoiebo/cedula_planteles

**7.- ESTABLECER PERMISOS DE LECTURA Y ESCRITURA:**  

**Para actualizar campos desde un archivo .CSV**  
cedulaplanteles/importar_datos

**Carpeta General: para subir y eliminar imágenes, archivos pdf, word y Excel**  
cedulaplanteles/librerías/blueimp/example

**Subcarpetas:**
cedulaplanteles/librerías/blueimp/example/files

cedulaplanteles/librerías/blueimp/example/scripts
cedulaplanteles/librerías/blueimp/example/scripts/archivos_oficios
cedulaplanteles/librerías/blueimp/example/scripts/archivos_programas_federales
cedulaplanteles/librerías/blueimp/example/scripts/documentos_juridicos
cedulaplanteles/librerías/blueimp/example/scripts/formato_predio
cedulaplanteles/librerías/blueimp/example/scripts/fotos_danos_plantel
cedulaplanteles/librerías/blueimp/example/scripts/guion_proyectos
cedulaplanteles/librerías/blueimp/example/scripts/macrolocalizacion
cedulaplanteles/librerías/blueimp/example/scripts/microlocalizacion
cedulaplanteles/librerías/blueimp/example/scripts/proyecto_productivo


**8.- CONTACTO:**  
Dirección de Planeación y Vinculación Educativa  
Departamento de Apoyo a Proyectos Educativos   
Actualización y seguimiento de información en el sistema informático “Cedula de planteles”.  
L.I. Alejandro Jacinto Sierra.   
Email: enlace_planeacion@iebo.edu.mx  



