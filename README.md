# Cliente PHP
Cliente PHP básico para poner en marcha una completa web de clasificados gracias a AnunciosClasificadosYa.com API

# Configuración
Una vez descargado el cliente hay que configurar un parámetro básico para su correcto funcionamiento:

**Fichero: /anucya_client/inc/config.php**
>
```php
<?php 
define("API_KEY","TuAuth-TokenDeApi"); 
$config = array(
	'base_file_path' => '/front/anuncios/',
```
>

Donde base_file_path será la ruta path de la url donde alojaremos el cliente.

# Personalización
Los ficheros de estilos se podrán encontrar en la carpeta: **/anucya_client/assets** para que puedan modificarse al gusto.
