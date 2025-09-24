# TareaEvaluacion1
💻 Aplicación de Login en Java Swing
Este proyecto muestra tres versiones diferentes de una interfaz de login desarrollada con Java Swing. La idea es demostrar cómo, a partir de un mismo concepto, se pueden implementar variaciones que van desde lo más clásico hasta lo más creativo e interactivo.

🌟 Versiones incluidas

│   Clásica         │ → Login simple con usuario, contraseña y botón de acceso.  
│   Extendida       │ → Incluye selector de idioma y opción de recordar usuario.  
│   Creativa        │ → Sistema con pestañas (Login / Registro), barra de progreso y spinner de edad.  


🧩 Descripción de cada versión

🔹 Login Clásico
Una versión sencilla y limpia. Incluye:
Campo de usuario y contraseña con JLabel.
Casilla para aceptar términos con JCheckBox.
Botón “Acceder” con JButton.

👉 El diseño se refuerza con un fondo azul claro, márgenes internos y un logotipo textual en grande con fuente Serif y color azul oscuro.

🔹 Login Extendido
Parte del clásico, pero añade más opciones:
JComboBox para elegir idioma (Español, Inglés, Francés).
JRadioButton para “Recordar usuario”.
Campos de texto un poco más amplios para mayor comodidad.

👉 Se conserva la misma línea de colores suaves, pero la interfaz se siente más completa y personalizable.

🔹 Login Creativo
Una propuesta más dinámica e interactiva:
Dos pestañas: Login y Registro.
En “Registro” se añaden:
Campo de edad con JSpinner.
JProgressBar que avanza automáticamente al registrarse.
Mensaje emergente de confirmación mediante JOptionPane.

👉 Es la versión más llamativa, con simulación de proceso y experiencia más moderna.

🎨 Personalizaciones realizadas
Colores de fondo: se usaron tonos de azul claro (new Color(230, 240, 255) y similares) para dar un aspecto agradable y moderno.
Márgenes: se aplicaron bordes internos a los paneles (setBorder) para que los componentes respiren y no queden pegados a la ventana.
Tipografía del logo: fuente grande, negrita y en color azul oscuro para destacar.
Campos de texto: ajustados en anchura (15 o 20 columnas) para mejorar la usabilidad.
Casillas de verificación y radio buttons: se hicieron transparentes (setOpaque(false)) para que se integren con el color del panel.
Botones: etiquetas claras como “Acceder” o “Registrarse”. En la versión creativa se añade una animación con la barra de progreso.

📂 Estructura del proyecto

DII_T1/
TareaEvaluacion1_Clasica.java 

TareaEvaluacion1_Extendida.java

TareaEvaluacion1_Creativa.java

README.md

🚀 Cómo ejecutar
Para compilar y ejecutar cualquiera de las versiones:

javac DII_T1/TareaEvaluacion1_Clasica.java

java DII_T1.TareaEvaluacion1_Clasica

(Sustituir por Extendida o Creativa según la versión que se quiera abrir).
