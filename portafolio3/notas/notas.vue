<template>
    <div>
      <h2>Levantar el servidor</h2>
      <p>Para levantar el servidor, ejecutaremos el siguiente comando:</p>
      <code>npm run serve</code>
  
      <h2>Definir las rutas en Laravel</h2>
      <ul>
        <li><strong>routes/api.php:</strong> En este archivo se definen todas las rutas de las APIs que puede tener nuestra aplicación.</li>
        <li><strong>routes/channels.php:</strong> Aquí definimos los canales de transmisión de eventos, como notificaciones en tiempo real.</li>
        <li><strong>routes/console.php:</strong> En este archivo definimos comandos de consola que interactúan con el usuario u otro sistema.</li>
        <li><strong>routes/web.php:</strong> Aquí definimos todas las rutas de nuestra aplicación web accesibles desde la barra de direcciones del navegador.</li>
      </ul>
  
      <h2>Tipos de rutas en Laravel</h2>
      <ul>
        <li>Route::get($uri, $callback)</li>
        <li>Route::post($uri, $callback)</li>
        <li>Route::put($uri, $callback)</li>
        <li>Route::patch($uri, $callback)</li>
        <li>Route::delete($uri, $callback)</li>
        <li>Route::options($uri, $callback)</li>
      </ul>
  
      <h2>Rutas en el archivo web.php</h2>
      <p>En el archivo web.php, podemos definir nuestras rutas:</p>
      <code>Route::get('/', () => { // Código de la ruta raíz });</code>
  
      <h2>Ruta con parámetro</h2>
      <p>Podemos agregar un parámetro a una ruta:</p>
      <code>Route::get('/usuarios/{id}', (id) => { // Código de la ruta con parámetro });</code>
  
      <h2>Rutas con parámetros opcionales</h2>
      <p>Podemos tener rutas con parámetros opcionales:</p>
      <code>Route::get('/usuarios/{id?}', (id) => { // Código de la ruta con parámetro opcional });</code>
  
      <h2>Controladores en Laravel</h2>
      <p>Para generar un controlador en Laravel, puedes usar el siguiente comando:</p>
      <code>php artisan make:controller ControladorUsuario</code>
  
      <h2>Enlazar ruta a un controlador</h2>
      <p>Para enlazar una ruta a un controlador, puedes hacer lo siguiente:</p>
      <code>Route::get('/usuarios', 'ControladorUsuario@index');</code>
  
      <h2>Validaciones en formularios</h2>
      <p>Antes de crear la validación, muestra la migración correspondiente:</p>
      <pre><code>Muestra aquí la migración correspondiente</code></pre>
  
      <p>A continuación, abre el controlador correspondiente, específicamente en el método <code>store()</code> que es donde se controlan los errores de validación del formulario, y es aquí donde agregarás el código de validación.</p>
    </div>
  
  
  