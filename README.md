# To-Do App - Java Swing

Aplicación de escritorio desarrollada en Java Swing que permite gestionar tareas mediante una interfaz gráfica.
El sistema permite crear, eliminar y actualizar tareas usando una tabla interactiva.

---

# Cómo ejecutar el proyecto

Para ejecutar la aplicación, siga los siguientes pasos:

1. Clonar el repositorio:

git clone https://github.com/Exodial1111/todo-app-java-swing.git

2. Abrir el proyecto en el entorno de desarrollo:

NetBeans 13

3. Ejecutar la clase principal:

MainForm.java

4. La aplicación se abrirá automáticamente.

---

# Funcionalidades completadas

Las siguientes funcionalidades fueron implementadas en el sistema:

* Agregar nuevas tareas ingresando título, descripción y estado.
* Validación del campo título como obligatorio.
* Visualización de tareas en una tabla (JTable).
* Selección de tareas desde la tabla.
* Mostrar el título de la tarea seleccionada.
* Eliminación de tareas seleccionadas con confirmación previa.
* Cambio de estado de tareas seleccionadas.
* Evitar seleccionar el mismo estado actual.
* Ordenamiento automático de columnas en la tabla.

Estados disponibles:

* Pendiente
* En progreso
* Completada

---

# Decisiones tomadas durante el desarrollo

Durante el desarrollo del proyecto se tomaron las siguientes decisiones técnicas:

Uso de JTable

Se utilizó JTable para mostrar las tareas debido a que permite manejar información estructurada en filas y columnas. Además, facilita la selección de tareas y el ordenamiento automático de columnas.

Uso de DefaultTableModel

Se utilizó DefaultTableModel para gestionar los datos de la tabla. Esta estructura permite agregar, eliminar y modificar tareas de forma dinámica.

Se decidió evitar la edición manual de celdas para mantener el control del flujo del sistema mediante botones.

Validación del campo título

Se implementó una validación que evita agregar tareas sin título. Esta decisión se tomó porque el título representa el identificador principal de cada tarea.

Si el título está vacío, se muestra un mensaje de error utilizando JOptionPane.

Confirmación antes de eliminar tareas

Se agregó una ventana de confirmación antes de eliminar una tarea con el objetivo de evitar eliminaciones accidentales por parte del usuario.

Cambio de estado controlado

Se implementó un mecanismo que permite seleccionar un nuevo estado para la tarea, evitando que el usuario seleccione el mismo estado actual. Esto mejora la lógica del sistema y evita redundancias.

---

# Tecnologías utilizadas

* Java JDK 8 (1.8)
* Java
* Java Swing
* NetBeans 13
* JTable
* DefaultTableModel
* JOptionPane

---

# Estructura del proyecto

src/
├── MainForm.java
└── Otros archivos generados por NetBeans

---

# Objetivo del proyecto

El objetivo de este proyecto fue aplicar conceptos relacionados con:

* Desarrollo de interfaces gráficas con Java Swing
* Manejo de eventos
* Manipulación de tablas (JTable)
* Validación de datos
* Interacción con el usuario mediante ventanas emergentes

---

# Autor

Ever Gonzalez

