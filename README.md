AppIot Eva 2

Nombre: Romina Baeza
Carrera: Analista Programador
Asignatura: Aplicaciones Móviles para IoT
Docente: Felipe Oyarzún  
Fecha: 21 de Octubre 2025  

Eva2AppIoT — Aplicación Android IoT

Es una aplicación móvil desarrollada en **Android Studio con Kotlin** como parte de la evaluación II 
Su propósito es simular un sistema de autenticación de usuarios con interfaz moderna y funciones básicas de inicio de sesión, registro y recuperación de cuenta.

---
Funcionalidades principales
Inicio de sesión:** permite validar el acceso del usuario.  
Registro de nuevos usuarios:** interfaz para crear una cuenta.  
Recuperar contraseña:** envío simulado de correo de recuperación.  
Pantalla Splash personalizada:** muestra el logo de la app al iniciar.  
Diseño moderno:** con colores y estilos basados en Material Design 3.  

---

Estructura del proyecto

app/
├── manifests/
│ └── AndroidManifest.xml
├── java/
│ └── com.example.eva2appiot/
│ ├── Splash.kt
│ ├── Login.kt
│ ├── Register.kt
│ └── Recover.kt
├── res/
│ ├── layout/
│ │ ├── activity_login.xml
│ │ ├── activity_register.xml
│ │ ├── activity_recover.xml
│ │ └── activity_splash.xml
│ ├── drawable/
│ │ ├── logoromina.png
│ │ └── logoapp.png
│ └── values/
│ └── strings.xml
└── build.gradle

Tecnologías utilizadas:

- Lenguaje: Kotlin  
- Entorno: Android Studio  
- SDK: Android 13 (API 33)  
- Librerías:
  - Material Components  
  - ConstraintLayout  
  - CardView  
  - AlertDialog  
