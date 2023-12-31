# Aplicación de servicio y reparto a domicilio

## Definición del proyecto y requisitos básicos

Nuestra aplicación será un página web dedicada al servicio de comida a domicilio, con un apartado de reseñas y valoraciones de los usuarios registrados, en la cual habrá diferentes roles de usuarios que puedan acceder a ella:

- Administrador: tendrá control total sobre la aplicación, en cuanto al código de la aplicación.

- Cliente registrado: podrá comprar los productos que él quiera, añadir productos a la cesta, con las compras que haga se le guardará unos descuentos, añadir restaurante o tiendas a favoritos y ver el seguimiento de su pedido.

- Desarrollador de contenido: Podrá crear el restaurante, añadirá, editará productos y eliminar.

- Invitado: sólo los restaurantes y tiendas, ver las reseñas de los restaurantes/tiendas, pero no podría comprar ni comentar.

## Casos de uso para la V1.0 - Definición básica​
- Registrar usuario: Un usuario puede registrarse en la plataforma proporcionando su nombre, apellidos, email y contraseña.
- Iniciar sesión: Un usuario registrado puede iniciar sesión en la plataforma proporcionando su email y contraseña.
- Cerrar sesión: Un usuario puede cerrar su sesión en la plataforma en cualquier momento.
- Editar perfil: Un usuario registrado puede editar su perfil, actualizando su nombre, apellidos, email o contraseña.
Registro de 1 solo restaurante.
- Ver Productos/Restaurantes: Un usuario registrado puede ver un listado de los restaurantes que hay disponibles y sus respectivos productos y puede comprarlo. El usuario invitado solo podrá ver los respectivos restaurantes y sus productos.
- Publicar comentario: Un usuario con el perfil de registrado puede publicar una reseña de cómo ha ido la compra y decir su opinión sobre el servicio
- Ver/Editar usuarios: Un administrador puede ver una tabla con todos los usuarios que hay registrados y editar la información, incluido el ROL de usuario.
- Eliminar usuario: Un administrador puede eliminar cualquier usuario registrado en la plataforma

![Imagen Caso de Usos](casoUso.png)

## Diseño de Bocetos
### Home y menús usuarios
![Imagen Boceto Home](bocetos/home.jpg)

Hemos didivido la interficie en 3 zonas, un header, un main y un footer.

* En el header vamos a alojar una barra superior fija con: el logo y nombre de la web, un menú central genérico (para acceder a contacto) y a la derecha un menu para iniciar sesión o registrarte.
* El main albergará el contenido de las páginas. Será la sección que vaya cambiando dependiendo de la página que carguemos. La página contará con un buscador y con el logo de la aplicación. Una vez en el buscador pongas el tipo de comida que quieras pedir, cambiará la página enseñando un listado de restaurantes, con su foto, una valoración de los clientes e información del restaurante. 
* El footer será meramente informativo.

![Imagen Boceto buscador](bocetos/buscado.jpg)

### Regitro de un usuario
![Imagen Boceto Registro](bocetos/registro.png)
### Iniciar Sesión
![Imagen Boceto Iniciar Sesión](bocetos/sesion.png)
### Editar mi Perfil
![Imagen Boceto Editar Perfil](bocetos/editarPefil.png)

Editar perfil será una ventana modal, es decir, se mostrará la ventana y el fondo se volverá oscuro.

Esta ventana de edición permitirá, además de modificar los datos del usuario, añadir una imagen de avatar. Por el momento, en esta primera versión, podremos añadir el link de una imagen que esté alojada en un servidor.

### Vista de las secciones del restaurante
![Imagen Boceto vista restaurante](bocetos/vistaRestaurante.png)

En esta página podemos ver las secciones del restaurante seleccionado. Estas secciones se podrán ver o en parte izquierda de la página o deslizando la página hacía abajo.

### Vista dentro de una sección
![Imagen Boceto vista sección](bocetos/vistaSeccion.jpg)

Una vez hayamos entrado en alguna sección veremos un listado de productos relacionados con el tipo de comida que haya en esa sección, con una foto del producto, el nombre, y su precio. Este listado será completamente clicable.

### Elección producto
![Imagen Boceto vista producto](bocetos/vistaProducto.jpg)

Si el usuario que está viendo la información de un proyecto en concreto es el autor de dicho proyecto, aparecerá un icono para la edición del mismo.

### Nuevo proyecto / Editar un proyecto
![Imagen Boceto nuevo/editar proyecto](bocetos/nuevo.jpg)

Esta vista sirve tanto para crear un nuevo proyecto como para editarlo.

Si el proyecto es nuevo, el botón mostrará el texto ENVIAR, pero si estamos editándolo aparecerá el texto ACTUALIZAR. Al crear o actualizar el proyecto, la web nos reenvía a la vista 'Detalle de proyecto'.

### Editar/Añadir Restaurante
![Imagen Boceto administracion proyectos](bocetos/editarRestaurante.jpg)

Si tienes el rol 'administrador' aparecerá el item 'Panel administración' en el menú superior específico. Este item nos permite cargar la vista 'Panel administración de proyectos'. Desde esta vista también podemos acceder al 'Panel administración de usuarios'.

Esta vista permite editar o borrar cualquier proyecto haciendo click en los iconos correspondientes. La opción editar nos llevará a la vista 'Editar proyecto'

### Panel administración de usuarios
![Imagen Boceto administracion usuario](bocetos/panel2.jpg)

Esta vista permite editar los datos de los usuarios. Por supuesto es solo accesible para los administradores.
