# Aplicación de servicio y reparto a domicilio

## Definición del proyecto y requisitos básicos

Nuestra aplicación será un página web dedicada al servicio de comida a domicilio, con un apartado de reseñas y valoraciones de los usuarios registrados, en la cual habrá diferentes roles de usuarios que puedan acceder a ella:

- Administrador: tendrá control total sobre la aplicación, en cuanto al código de la aplicación.

- Cliente registrado: podrá comprar los productos que él quiera, añadir productos a la cesta, con las compras que haga se le guardará unos descuentos, añadir restaurante o tiendas a favoritos y ver el seguimiento de su pedido.

- Desarrollador de contenido: Podrá crear el restaurante, añadirá, editará productos y eliminar.

- Invitado: sólo los restaurantes y tiendas, ver las reseñas de los restaurantes/tiendas, pero no podría comprar ni comentar.

## Casos de uso para la V1.0 - Definición básica​
-Registrar usuario: Un usuario puede registrarse en la plataforma proporcionando su nombre, apellidos, email y contraseña.
-Iniciar sesión: Un usuario registrado puede iniciar sesión en la plataforma proporcionando su email y contraseña.
-Cerrar sesión: Un usuario puede cerrar su sesión en la plataforma en cualquier momento.
-Editar perfil: Un usuario registrado puede editar su perfil, actualizando su nombre, apellidos, email o contraseña.
Registro de 1 solo restaurante.
-Ver Productos/Restaurantes: Un usuario registrado puede ver un listado de los restaurantes que hay disponibles y sus respectivos productos y puede comprarlo. El usuario invitado solo podrá ver los respectivos restaurantes y sus productos.
-Publicar comentario: Un usuario con el perfil de registrado puede publicar una reseña de cómo ha ido la compra y decir su opinión sobre el servicio
-Ver/Editar usuarios: Un administrador puede ver una tabla con todos los usuarios que hay registrados y editar la información, incluido el ROL de usuario.
-Eliminar usuario: Un administrador puede eliminar cualquier usuario registrado en la plataforma

![Imagen Caso de Usos](casoUso.png)

