El proyecto se encuentra modularizado en diferentes actividades y componentes reutilizables:

```
MiAplicacion/
├── app/
│   ├── build.gradle                                    # Configuración SDK y dependencias (RecyclerView, CardView, Material)
│   └── src/
│       └── main/
│           ├── AndroidManifest.xml                     # Declaración de componentes y actividades del sistema
│           ├── java/com/example/miaplicacion/
│           │   ├── MainActivity.java                   # Menú principal y demostración de Layouts base (Act. 1.3)
│           │   ├── MainActivity2.java                  # Implementación oficial Pauta 1.4 (Widgets y Containers)
│           │   ├── RegisterActivity.java               # Desafío 1: Formulario de registro con validaciones y ProgressBar
│           │   ├── WelcomeActivity.java                # Desafío 1: Pantalla de confirmación y bienvenida de usuario
│           │   ├── CourseModel.java                    # Desafío 2: POJO (Modelo de datos) para cursos
│           │   ├── CourseAdapter.java                  # Desafío 2: Adaptador RecyclerView con patrón ViewHolder
│           │   └── CourseListActivity.java             # Desafío 2: Pantalla con RecyclerView y lista de cursos
│           └── res/
│               ├── drawable/
│               │   ├── ic_avatar_student.xml           # Recurso vectorial para avatar de alumnos en tabla
│               │   ├── ic_course_icon.xml              # Recurso vectorial para tarjetas de cursos
│               │   ├── bg_table_border.xml             # Fondo y contornos estilizados para TableLayout
│               │   ├── bg_card.xml                     # Bordes redondeados y fondos de tarjetas
│               │   └── bg_header_gradient.xml          # Gradiente institucional Santo Tomás (#006847)
│               ├── layout/
│               │   ├── activity_main.xml               # Layout principal con navegación integrada
│               │   ├── activity_main2.xml              # Layout Pauta 1.4: CalendarView, Bars y TableLayout
│               │   ├── activity_register.xml           # Layout Desafío 1: Formulario con RadioGroup y ProgressBar
│               │   ├── activity_welcome.xml            # Layout Desafío 1: Resumen de datos registrados
│               │   ├── activity_course_list.xml        # Layout Desafío 2: Contenedor RecyclerView
│               │   └── card_layout.xml                 # Layout Desafío 2: Tarjeta CardView reutilizable
│               └── values/
│                   ├── colors.xml                      # Paleta cromática corporativa y semántica
│                   ├── strings.xml                     # Recursos de texto internacionalizables
│                   └── themes.xml                      # Estilos base Material Components
```
