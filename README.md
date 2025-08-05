**SISTEMA WEB DENOMINADO CEDULA DE PLANTELES**

**DEPENDENCIA: INSTITUTO DE ESTUDIOS DE BACHILLERATO DEL ESTADO DE OAXACA (IEBO)**

**LINK: http://sistemas.iebo.edu.mx/cedulaplanteles/**

**DESCRIPCIÓN DEL SISTEMA:** Gestionar la información de infraestructura, equipamiento, datos de las comunidades, localización de planteles, proyectos productivos, albergues, cocinas comunitarias, datos del predio, la seguridad, geográfica e imágenes donde se ubican cada uno de los 260 planteles del IEBO. Así mismo permite la generación de consultas, reportes y graficas de los datos e información almacenada en el sistema. **

**USUARIOS (BENEFICIOS):**

** 1.- DIRECTORES DE PLANTELES: Les permite acceder a la información relacionada con el plantel a su cargo, para actualizarla o validarla de forma anual o semestral.
** 2.- ADMINISTRATIVOS: Le permite generar gestionar usuarios, contraseñas, así como consultas, reportes y gráficas para articular los elementos y mecanismos necesarios para conocer la operación, desarrollo, fortalecimiento y mejora, de los planteles IEBO en el Estado. Esto contribuye a la integración de propuestas de mejoras para los planteles a través de los diferentes programas de financiamiento tanto federales, estatales y municipales.
** 3.- USUARIOS DE CONSULTA: Les permite acceder a la información de cada plantel, también para generar consultas o reportes de datos de los planteles desde cualquier lugar con acceso a internet; y así contribuir con información en los procesos administrativos.

**CARACTERÍSTICAS DEL SISTEMA:**
** 1.- Se genera una bitácora en el sistema para el control de actualizaciones realizadas por los directores de planteles, registrando el campo y valor asignado, así como la fecha y hora realizada, permitiendo evaluar el desempeño y puntualidad de los directores. 
** 2.- Proveer de información sobre los planteles a los usuarios administrativos o de consulta para la toma de decisiones.
** 3.- Contribuye a la generación e integración de propuestas de mejoras en infraestructura y equipamiento para los planteles a través de los diferentes Programas de Financiamiento tanto Federales, Estatales o Municipales. 

** **TECNOLOGIAS UTILIZADAS:**

** 1.- Frontend:
* HTML5
* CSS3
* JavaScript 
* jQuery 1.2.6
* highcharts: https://www.highcharts.com/
* Bootstrap (En formato general) https://getbootstrap.com/

** 2.- Backend:
* PHP 8.3.14
* MySQL 9.1
* Servidor HTTP Apache

** **CONFIGURACIÓN DE LA BASE DE DATOS:** 
**1.- Nombre de la base de datos: cedulaplanteles
Cotejamiento: utf8mb4_0900_ai_ci	


** **ESTRUCTURA DEL PROYECTO**
** cedulaplanteles/

├───2014A
├───Bibliotecas
│   ├───code   
│   ├───css
│   └───js       
├───clases
├───css
│   └───images
├───documentos
│   ├───18
│   ├───19
│   ├───20
│   └───21
├───images
│   └───css
│       └───images
├───importar_datos
├───js
├───librerias
│   ├───blueimp
│   │   ├───example
│   │   │   ├───files         
│   │   │   ├───scripts
│   │   │   │   ├───archivos_oficios              
│   │   │   │   ├───archivos_programas_federales   
│   │   │   │   ├───documentos_juridicos   
│   │   │   │   ├───formato_predio
│   │   │   │   ├───fotos_danos_plantel
│   │   │   │   ├───guion_proyectos       
│   │   │   │   ├───macrolocalizacion   
│   │   │   │   ├───microlocalizacion
│   │   │   │   └───proyecto_productivo       
│   │   │   └───thumbnails
│   │   ├───images
│   │   └───tests
│   ├───ckeditor
│   │   ├───adapters
│   │   ├───images
│   │   ├───lang
│   │   ├───plugins   
│   │   ├───skins
│   │   │   ├───kama
│   │   │   │   └───images
│   │   │   ├───office2003
│   │   │   │   └───images
│   │   │   └───v2
│   │   │       └───images
│   │   ├───themes
│   │   │   └───default
│   │   ├───_samples   
│   │   └───_source
│   │       ├───adapters
│   │       ├───core   
│   │       ├───lang
│   │       ├───plugins
│   │       ├───skins       
│   │       └───themes           
│   ├───datagrid
│   ├───editinplace
│   │   ├───demo
│   │   │   ├───css
│   │   │   ├───images
│   │   │   └───js
│   │   └───src
│   ├───eyedatagrid-1.1
│   │   └───images
│   ├───facyBox
│   │   ├───demo
│   │   └───images
│   ├───grafica _css
│   │   ├───images
│   │   └───stylesheets
│   ├───jquery.ad-gallery
│   │   └───images
│   │       └───thumbs
│   ├───jquery_lightbox
│   │   ├───assets
│   │   ├───examples
│   │   ├───help   
│   │   ├───javascript   
│   │   └───psd
│   ├───map
│   │   └───images       
│   ├───pro_dropdown_2
│   ├───subir-fotos
│   │   └───phpuploader       
│   ├───subir-fotos2
│   │   ├───css
│   │   ├───fonts
│   │   ├───images   
│   │   └───js
│   └───tokeninput
│       ├───examples
│       ├───src
│       └───styles
├───municipios_oaxaca
│   ├───css
│   ├───images
│   ├───js
│   └───librerias 
├───proyectos_educativos
│   └───informacion_geografica
└───reportes
    ├───font    
    ├───fpdf   
    ├───fpdf-2    
    ├───tcpdf    
    └───tmp
  

**Configuración de permisos:**
cd /var/www/html
git clone https://github.com/hugosantiagoiebo/cedula_planteles

**ESTABLECER PERMISOS DE LECTURA Y ESCRITURA:**
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


**Contacto:**
Dirección de Planeación y Vinculación Educativa
Departamento de Apoyo a Proyectos Educativos 
Actualización y seguimiento de información en el sistema informático “Cedula de planteles”.
L.I. Alejandro Jacinto Sierra. 
Email: enlace_planeacion@iebo.edu.mx



