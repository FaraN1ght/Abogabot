# Abogabot

## Descripción del Caso

Un despacho de abogados (Abogabot) requiere un aplicativo web para automatizar las demandas de sus clientes utilizando un formulario para la captura de datos y un sistema de pagos posterior al llenado de datos para finalizar la transacción.
<hr/>

## Análisis de Requerimientos

La aplicación deberá contar con 2 roles: `Administrador y Cliente` y para su desarrollo se tienen las siguientes historias de usuario.
<br/>

  * ### Administrador
  1. Como Administrador requiere `recibir, ver, listar y actualizar` las notificaciones de demandas de los clientes.
     * *Al recibir la notificación se deberá crear automáticamente el documento legal en formato Word con los datos enviados al formulario.*
     * *Se deberá poder actualizar el estado de la demanda y agregar comentarios en cada actualización.*

  2. Como Administrador requiere `recibir, ver y listar` los pagos realizados por los clientes.
     * *Estos pagos se deberán mostrar en un Dashboard para análisis de ingresos recibidos.*

  * ### Cliente
  1. Como Cliente requiere poder `registrar` su información de demanda en un formulario bien definido y estructurado.
  2. Como Cliente requiere poder `pagar` su pedido en el aplicativo web de forma segura.
  3. Como Cliente requiere poder `ver y listar` las actualizaciones de su proceso legal (pedido/solicitud).
     * *Cada vez que un administrador haga una actualización, le deberá llegar una notificación al cliente.*

  * ### Todos los Usuarios
  1. Como Usuario requiere tener una `página responsive` para poder verla desde diferentes pantallas/dispositivos.
  2. Como Usuario requiere poder `registrar` una cuenta de usuario o `conectarse` en caso de que ya tenga una en la plataforma web.
