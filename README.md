# Sistemas-de-Menu-Kimberly-Vinces-Melgar-

![WhatsApp Image 2024-06-14 at 11 14 36 PM](https://github.com/Kimberly168888/Sistemas-de-Menu-Kimberly-Vinces-Melgar-/assets/169225018/cf84f6c8-bcda-4ebf-8dcb-62d1e84bc964)

Explicación del código:

Se construye una interfaz de usuario que incorpora una barra de menú (menuBar) con tres menús principales: "Archivo", "Editar" y "Ayuda". Cada menú incluye varios elementos de menú (MenuItem) y algunos de estos están separados por separadores (SeparatorMenuItem) para mejorar la organización visual.

Cada MenuItem tiene una acción específica asociada mediante expresiones lambda. Por ejemplo, al seleccionar "Nuevo" en el menú "Archivo", se imprime un mensaje en la consola.

La estructura de la interfaz se organiza usando un BorderPane (borderPane) como contenedor principal, y la MenuBar se coloca en la parte superior del BorderPane (setTop).

Para la opción "Acerca de" en el menú "Ayuda", se define un método llamado mostrarAcercaDe(), que muestra un cuadro de diálogo (Alert) cuando se selecciona esta opción.

En el método main, la aplicación se inicia llamando a launch(args), lo que lanza la interfaz y maneja las interacciones del usuario.

