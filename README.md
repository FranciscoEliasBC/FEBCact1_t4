Alumno: Bautista Centeno Francisco Elias
Materia: Programación Web
Maestra: Martínez Nieto Adelina

# Proyecto Actividad 1 - Tema 4 (Spring Boot API Rest)

Este proyecto es una aplicación web desarrollada con **Java** y **Spring Boot** que expone diferentes endpoints de pruebas e información utilizando controladores REST.

---

## Estructura del Proyecto

```text
act1_t4/
├── .mvn/                  # Archivos del wrapper de Maven
├── .vscode/               # Configuración del entorno Visual Studio Code
├── src/
│   ├── main/
│   │   ├── java/com/act1_t4/demo/
│   │   │   ├── DemoApplication.java       # Clase principal para ejecutar Spring Boot
│   │   │   ├── AdicController.java        # Controlador REST adicional
│   │   │   ├── InfoController.java        # Controlador REST de información
│   │   │   └── ProyectoController.java    # Controlador REST de gestión de proyecto
│   │   └── resources/
│   │       ├── static/                    # Archivos estáticos
│   │       ├── templates/                 # Plantillas de vista
│   │       └── application.properties     # Configuración de la aplicación
│   └── test/                          # Pruebas unitarias e integración
├── pom.xml                # Configuración de dependencias de Maven
├── mvnw / mvnw.cmd        # Scripts ejecutables de Maven Wrapper
└── README.md              # Documentación del proyecto
```

## Tecnologías Utilizadas

Lenguaje: Java

Framework: Spring Boot

Gestor de Dependencias: Maven

IDE: Visual Studio Code 

## Requisitos Previos
Antes de ejecutar el proyecto, asegúrate de contar con los siguientes elementos instalados:

Java Development Kit (JDK): Versión 17 o superior.

Maven: (Opcional, ya que el proyecto incluye el wrapper ./mvnw).

## Instalación y Ejecución
Clonar el repositorio o descargar el código fuente:

git clone <URL_DEL_REPOSITORIO>
cd act1_t4

Compilar el proyecto:

DOS
mvnw.cmd clean package

Ejecutar la aplicación:

DOS
mvnw.cmd spring-boot:run

## Controladores y Rutas
La aplicación cuenta con tres controladores principales mapeados en el paquete com.act1_t4.demo:

AdicController: Gestiona endpoints adicionales de prueba.

InfoController: Proporciona endpoints informativos del sistema/usuario.

ProyectoController: Maneja la lógica asociada a las operaciones del proyecto.
