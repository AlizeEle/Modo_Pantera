# Modo_Pantera
Descripcion del Proyecto
 
Modo pantera es una aplicacion mocilla desarrollada en Flutter para estudiantes y coaches del gimnasio de la Universidad Panamericas. La aplicacion permitira gestionar rutinas, registrar progreso, calcular 1RM y gemerar reports de entrenamiento.

Esctructura del Proyecto 

lib / - Contiene todo el codigo principal de la aplicacion Flutter
core/ - Esta carpeta contien components reutilizables en toda la aplicacion
core/theme - Define la apariencia visual de la app. En esta se configuran los siguientes 
puntos:
- Colores
- Tipografia
- Estilos de botones
- Estilos de cardd
- Estilos de AppBar 

Esto garantiza que toda la aplicacion tenga una identidad visual consistente con la Universidad Panemricana

Ejemplo de archivos:

app_theme.dart
colors.dart
typography.dart

core/widgets/ - Contiene widgets reutilizables que se usan en varias pantallas

Ejemplos 

exercise_card.dart
progress_card.dart
custom_button.dart
stat_card.dart

features/ - Aqui se organizan las funcionalidades principals de la aplicacion(cada mulo representa una 
parte importante del Sistema

features/auth/ - Sistema de autenticacion de usuarios. En este se maneja:
- Registro
- Inicio de Sesion
- Seleccion de rol ( estudiante o coach) 

Ejemplo:
login_screen.dart
register_screen.dart

features/dashboard/ - Pantalla principal de la aplicacion. Contiene:
- Rutina del dia 
- Accesos rapidos 
- Informacion del usuario 

features/routines/ - Gestion de rutinas de entrenamiento. En esta seccion se implementa:
- Crear rutinas
- Editar rutinas
- Asignar rutinas
- Visualizar rutina del dia 

features/exercises/ - Biblioteca de ejercicios del gimnasio. Incluye:
- Lista de ejercicios
- Descripcion del ejercicio 
- Grupo muscular
- Guia visual o video 

features/progress/ - Seguimiento del progreso del usuario 
- Historial de entrenamientos 
- Progreso de peso 
- Volumen total 
- Graficas 

features/profile/ - Informacion del usuario. Incluye: 
- Datos personales
- Peso
- Altura 
- Objeto de entrenamiento 
- Configuraciones de cuenta 

database/ - Aqui se manejara la base de datos local (SQLite)
Contendra archivos que permiten: 
- Crear tablas 
- Guardar datos
- Consultar datos
- Actualizar registros

Ejemplos:
database_helper.dart
exercise_repository.dart
routine_repository.dart
progress_repository.dart

models/ Define las estructuras de datos de la aplicacion
user.dart
exercise.dart
routine.dart
progress.dart

Cada modelo representa un objeto de la base de datos
Exercise
Routine
User
WorkoutLog

