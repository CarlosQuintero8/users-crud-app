# CRUD de Usuarios <img src="https://img.icons8.com/color/32/000000/javascript--v1.png"/><img src="https://img.icons8.com/color/32/000000/react-native.png"/>

Proyecto desarrollado en [React](https://reactjs.org) que interactua con una API de Users, a través de todos los métodos http (GET, POST, PATCH y DELETE).
El propósito de esta aplicación es LEER, CREAR, ACTUALIZAR y ELIMINAR usuarios como practica de un CRUD.

![App de CRUD de Usuarios](/public/screenshotweb.webp)

## Características principales

- **Diseño Responsive:** Aplicación diseñada para adaptarse a diferentes dispositivos y tamaños de pantalla.
- **Interactividad:** Elementos interactivos y animaciones suaves implementadas para mejorar la experiencia del usuario.

  - Pantalla de carga para indicar que esta cargando el listado de usuarios.
  - Un modal con un formulario para crear y editar usuarios.
  - Una alerta personalizada para indicar cuando un usuario a sido eliminado.
  - Uso de la librería [sonner](https://sonner.emilkowal.ski) para mostrar un toast cuando un usuario es creado o actualizado.
  - Subida de imágenes a [Cloudinary](https://cloudinary.com) para añadir una fotografía a cada usuario desde el ordenador.
  - Generar un avatar por defecto cuando el usuario no añade una fotografía, [avatar.iran.liara.run](https://avatar.iran.liara.run/public) usando el first_name.

- **Tecnologías utilizadas:**
  - <img src="https://img.icons8.com/color/32/000000/html-5--v1.png"/> HTML5 (Con estructura semántica y buenas practicas de accesibilidad)
  - <img src="https://img.icons8.com/color/32/000000/css3.png"/> CSS3 (Con Flexbox y Grid para diseño responsivo)
  - <img src="https://img.icons8.com/color/32/000000/javascript--v1.png"/>Javascript (Como lenguaje de programación del proyecto)
  - <img src="https://img.icons8.com/color/32/000000/react-native.png"/> React (Para añadir funcionalidad e interactividad)
  - <img src="https://svgl.vercel.app/library/cloudinary.svg" width="32" /> Cloudinary (Para la subida de imágenes)
