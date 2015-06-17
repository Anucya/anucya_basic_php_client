# anucya_php_app
App básica para poner en marcha una completa web de clasificados gracias a AnunciosClasificadosYa.com API

# Configuración
Una vez descargago el cliente hay que configurar un parámetro básico para su correcto funcionamiento:

**Fichero: /anucya_client/inc/config.php**
>
```php
<?php 
define("API_KEY","088e1f4279ced08c5645b9c617b74627566fa3175757d91ccaecfd2b0f62dd29"); 
$config = array(
	'base_file_path' => '/front/anuncios/',
```
>

Donde base_file_path será la ruta path de la url donde alojaremos el cliente.
