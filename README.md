# tasker-managerTask Manager Pro
Task Manager Pro es una aplicación web diseñada para ayudarte a organizar tareas, realizar cálculos rápidos y tomar notas, todo en un solo lugar. La aplicación incluye características como un gestor de tareas, una calculadora simple y una función de notas adhesivas, todo estilizado con un tema oscuro para una apariencia limpia y moderna.

Características
Gestor de Tareas: Te permite agregar, ver y completar tareas. Puedes seleccionar varias tareas para marcarlas como completadas.
Calculadora: Una calculadora simple para operaciones matemáticas básicas como suma, resta, multiplicación y división.
Notas Adhesivas: Un editor de texto para escribir y guardar notas, con una barra de herramientas personalizable.
Diseño Responsivo: Optimizado tanto para dispositivos de escritorio como móviles.
Tecnologías Usadas
HTML: Estructura de la página web.
CSS: Estilo personalizado, incluyendo diseños de cuadrícula, transiciones y diseño responsivo.
Quill.js: Un editor de texto enriquecido utilizado para las notas adhesivas.
JavaScript: Para gestionar las funcionalidades de la lista de tareas y las operaciones de la calculadora.
Instrucciones de Uso
Para comenzar con Task Manager Pro:

Abre el archivo index.html en tu navegador: Simplemente abre el archivo index.html en cualquier navegador moderno para comenzar a usar la aplicación.

Personalización:

Puedes modificar las funcionalidades de las tareas y la calculadora editando las funciones de JavaScript.
Personaliza la apariencia de la aplicación modificando las variables CSS definidas en la etiqueta <style>.
Características Disponibles
Gestor de Tareas
Agrega nuevas tareas escribiendo en el campo de entrada y haciendo clic en el botón "Agregar Tarea".
Marca las tareas como completadas usando el botón "Completar tareas seleccionadas".
Calculadora
Realiza operaciones matemáticas básicas usando los botones de números y los cuatro botones de operación.
Limpia la pantalla usando el botón "C".
Notas Adhesivas
Usa el editor Quill.js para agregar, editar y dar formato a tus notas.
El editor viene con una barra de herramientas personalizable y soporta funciones de texto enriquecido como negrita, cursiva, entre otros.
Personalización
Para modificar la paleta de colores o el estilo de la aplicación, puedes actualizar las variables CSS definidas en la sección :root:

css
Copiar
Editar
:root {
    --primary-color: #4CAF50;  /* Color principal */
    --primary-hover: #45a049;  /* Color al pasar el ratón */
    --bg-dark: #121212;        /* Fondo oscuro */
    --bg-card: #1E1E1E;        /* Fondo de la tarjeta */
    --text-primary: #ffffff;   /* Color del texto principal */
    --text-secondary: #B0B0B0; /* Color del texto secundario */
    --border-color: #333333;   /* Color de los bordes */
}
Puedes ajustar fácilmente los colores o agregar estilos CSS adicionales para adaptarlos a tus necesidades.

Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
