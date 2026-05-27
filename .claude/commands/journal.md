--- 
Name: Journal
Description: Revisar, planificar y llevar a cabo las correcciones solicitadas. 

---

* Dentro de la carpeta /obsidian dentro de esta carpeta, se encuentra un archivo llamado "tareas pendientes.md" Ahí se encuentran todas las tareas nuevas pedidas para la sesión. 
* En la carpeta /obsidian, además, se encuentra documentación técnica y reglas del negocio del proyecto. Idealmente, antes de comenzar a trabajar revisa la documentación y anda revisando puntos relevantes respecto a las tareas escritas en el archivo indicado mas arriba. 
    * Si hay aplicaciones nuevas que crear, o si se debe actualizar alguna, anda modificando o agregando la documentación dentro de la carpeta obsidian, siguiendo la estructura de las vistas en el proyecto web. Por ejemplo, si tienes la vista /ofertas y dentro hay una vista llamada "postulaciones" la ruta dentro de obsidian debiera ser /ofertas/postulaciones.md 
* Antes de comenzar a trabajar, arma una lista de tareas a realizar y luego, cada vez que vayas terminando una tarea, anda tachandola. Así, si se acaban los tokens disponibles se puede retomar nuevamente al usar este comando. La lista debe quedar dentro de "tareas pendientes.md". 
* El orden debe ser : se desarrolla algo localmente y luego se sube al servidor presto, que es donde debe funcionar esta aplicación. 
* Además, dentro del servicio gitea de presto está el proyecto de wunen. 
    * Cada vez que se haga un cambio, se mejora o corrección, se debe ir actualizando el proyecto de gitea. 
    * En caso de que sea una mejora, debes crear una rama bajo la nomenclatura : feature_[descripcion_corta]_ddmmYYYY
    * Si el trabajo es una corrección, la rama debe tener la nomenclatura : fix_[descripcion_corta]_ddmmyyyy
    * En cada caso debes ir haciendo un commit indicando los cambios que se hicieron.
    * La ruta del git es http://gitea.presto/moya.dev/wunen.git . Puedes entrar con el usuario claude y la contraseña Temporal2026! 