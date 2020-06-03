# EnterTube
En este archivo voy a descrivir las piezas de mi proyecto, para que cualquiera que lo lea sepa de que trata cada parte.

El orden de las carpetas es el siguiente:

Nada más entrar estan las siguientes carpetas:

1. admin. pan.
      _css - temas para el panel del admin
      _js - java de las paginas del admin
      _pages - Paginas del panel del admin
      _plugins - "Aplicaciones de la pagina" (animated-css,bootstrap,jquery,etc...) <-- descargados de las paginas oficiales
      _autolad - autoload de la pagina del admin
      _index - acceso al admin panel
      _Licencia - licencia de la pagina
      
2. ajax.
      _archivos PHP
3. app_api
      - v1.0
        - assets
        - api-v1.0-config - Crea unas arrays con los objetos que necesitaremos en la pagina
        - plataform
        - api-v1.0 - carga la configuracion de movil o descktop dependiendo de lo que detecte
4. assets
        _import - Contiene mayormente programacion descargada de otros creadores de codigo
        _includes
               _app_start - Funciones, objetos y configuraciones para que funcione la pagina
               _context_data - ""
               _functions_general - ""
               _functions_one - ""
               _phpMailer_config - "" 
               _tables - ""
        _langs - contiene las lenguas descargadas
        _init - ejecuta una funcion, necesitando cierta configuracion, las cuales son "tablas","funciones_general","funciones_one"
        
5. install
        - index - configuracion de abse de datos
6. nodejs
         - messages
              _incomig - pagina HTML
              _Outgoing - ""
              _user_list - ""
        _mysql
              _DB - carga conexion con la base de datos
        _.htaccess - determina una regla
        _app_start - ajustes para la conexion con la base de datos
        _config - configuracion
        _functions - crea funcionciones a partir de datos recogidos de otros archivos
        _server - carga datos a la DB
7.sources
        _MULTIPLES ARCHIVOS PHP
8.thems - Diseño de la web
9.upload - fotos del diseño

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

