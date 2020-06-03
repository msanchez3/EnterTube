# EnterTube
En este archivo voy a descrivir las piezas de mi proyecto, para que cualquiera que lo lea sepa de que trata cada parte.

El orden de las carpetas es el siguiente:

Nada más entrar estan las siguientes carpetas:

1. admin. pan.
      - css - temas para el panel del admin
      - js - java de las paginas del admin
      - pages - Paginas del panel del admin
      - plugins - "Aplicaciones de la pagina" (animated-css,bootstrap,jquery,etc...) <-- descargados de las paginas oficiales
      - autolad - autoload de la pagina del admin
      - index - acceso al admin panel
      - Licencia - licencia de la pagina
      
2. ajax.
      - archivos PHP
3. app_api
      - v1.0
        - assets
        - api-v1.0-config - Crea unas arrays con los objetos que necesitaremos en la pagina
        - plataform
        - api-v1.0 - carga la configuracion de movil o descktop dependiendo de lo que detecte
        
4. assets
    - import - Contiene mayormente programacion descargada de otros creadores de codigo
    
    
    - includes
          - app_start - Funciones, objetos y configuraciones para que funcione la pagina
          - context_data - ""
          - functions_general - ""
          - functions_one - ""
          - phpMailer_config - "" 
          - tables - ""
        - langs - contiene las lenguas descargadas
        - init - ejecuta una funcion, necesitando cierta configuracion, las cuales son "tablas","funciones_general","funciones_one"
        
5. install
        - index - configuracion de abse de datos
6. nodejs
         - messages
              - incomig - pagina HTML
              - Outgoing - ""
              - user_list - ""
        - mysql
              - DB - carga conexion con la base de datos
        - .htaccess - determina una regla
        - app_start - ajustes para la conexion con la base de datos
        - config - configuracion
        - functions - crea funcionciones a partir de datos recogidos de otros archivos
        - server - carga datos a la DB
7. sources
        - MULTIPLES ARCHIVOS PHP
8. thems - Diseño de la web

9. upload - fotos del diseño

Seguidos con los siguientes archivos (adjunto la explicacionde lo que son a continuacion de su nombre):

.gitgnore - direcciones de archivos

.htacces - Fichero que contiene directivas

admincp - archivo para cargar el panel de control de admin

ajax - Carga ciertos aspectos de la pagina

api - Comprueba si existen API's

config - Archivo para la creacion de la base de datos de EnterTube

entertube - Base de datos de EnterTube (tablas) (los palabras estan sacadas de otro repositorio)

import - Carga procesos de PHP

index - Carga la pagina princiap de la pagina

nginx - Marca la direccion de los datos.

package - Archivo que añade datos de la pagina

package-lock - Registro de packetes

robots - opciones de configuracion

social-login - codigo para conectarse con cuentas de otras aplicaciones.

wo_login - codigo que carga los usuarios





/-----------------------------------------------------------------------------------------------------------------/

Para terminar de explicar como esta montado, me gustaria nombrar a todos los creadores de codigo que han dado codigo para llevar acabo este proyecto.


*Code creators:*

Josh Campbell - https://github.com/joshcam

Alexander V. Butenko - http://smarttechdo.com

Allan Hansen <ahØartemis*dk>  

James Heinrich - https://github.com/JamesHeinrich/getID3 

HybridAuth - http://github.com/hybridauth/hybridauth

Osman Üngür - http://github.com/o/sitemap-php

Nils Adermann - <naderman@naderman.de>, Jordi Boggiano - <j.boggiano@seld.be>

S.C. Chen <me578022@gmail.com>

John Schlick
 
Rus Carroll

@davegandy - http://fontawesome.io

Tambien hay licencias de aplicaciones, como facebook,boostrap,etc..

