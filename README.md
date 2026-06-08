Portal Academico - Tarea 1
De que trata el proyecto
Este es el proyecto que tengo que entregar para la primera unidad de la diplomatura. La idea fue armar desde cero la interfaz de registro para un Campus Virtual o Portal Académico. Para el diseño busque separar la pantalla en dos columnas mediante una distribución limpia: el bloque de la izquierda se mantiene volando sobre el fondo gris claro para guiar al usuario de forma visual, mientras que el bloque de la derecha tiene el formulario estructurado como una tarjeta flotante blanca con sombras sutiles y esquinas redondeadas. 

Que tecnologias y conceptos aplique
Para la estructura use HTML5 Semantico implementando las etiquetas correspondientes como header, main, footer y article para que el documento este bien ordenado y sea accesible. En la parte de Formularios e Inputs meti validaciones nativas, agrupe campos como Nombre/Apellido y Contrasenas en filas simetricas usando contenedores logicos, y conecte los label con sus respectivos input mediante los atributos for, id y name.  
En cuanto a CSS3, declare variables globales en el root para manejar la paleta de colores institucional y la tipografia base desde un archivo externo. Tambien use Flexbox para lograr una maquetacion responsive que alinea el contenido en columnas en pantallas grandes y se acomoda solo en vertical si se abre desde un celular. Diseñe los estados interactivos con pseudoclases como hover en los enlaces del menu y el boton, y focus para meter el anillo celeste de luz en los campos de texto activos. La imagen de la tablet respeta el limite de ancho maximo de 300px y tiene los bordes redondeados como pide la consigna.  

Estructura de archivos
El proyecto esta compuesto por el archivo index.html que contiene la estructura semantica de la pagina , el archivo style.css que es la hoja de estilos externa con las variables de diseño , el archivo app.js que esta enlazado para meter la logica de interacciones del lado del cliente, y la carpeta public que funciona como contenedor de assets donde guardo la imagen de la tablet. 

Como clonar y abrir el proyecto
Para correr el sitio de forma local en la PC primero abris la terminal y clonas el repositorio usando el comando git clone https://github.com/santiagosessa/Tarea-1.git. 
Despues entras a la carpeta que se creo y abris el archivo index.html en tu navegador.  
  
Mis datos de autor
Mi nombre es Santiago Sessa y curse la Unidad 1 del Módulo 1 en el curso Antes de React.  

Bibliografia consultada
Para el desarrollo de la interfaz consulte las referencias oficiales de HTML y CSS en MDN Web Docs , el estándar general de HTML Living Standard (2025) de WHATWG , y el libro HTML & CSS: Design and Build Websites de Jon Duckett publicado en 2011.  

![Vista final del Portal Academico](public/pagina-terminada.png)