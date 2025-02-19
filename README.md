# Mi Proyecto Spring Boot
Salauz Hernandez Nerick Francisco 6CV3
Ingenieria de Software - Hurtado Aviles Gabriel

## Descripción
Este es un proyecto básico de Spring Boot que expone un endpoint en `/hello` para devolver un mensaje de saludo.

## Instrucciones para Reproducir el Proyecto

### Requisitos Previos
- Java 17 o superior.
- Maven instalado.
- Git instalado (opcional, para clonar el repositorio).

### Pasos para Configurar y Ejecutar el Proyecto ***bash

1. Clona el repositorio:

   git clone https://github.com/NFrancSH/mi-proyecto-spring-boot.git

2. Navega a la carpeta del proyecto:

    cd mi-proyecto-spring-boot

3. Compila el proyecto con Maven:

    mvn clean install

4. Ejecuta la aplicación:

    mvn spring-boot:run

5. Abre tu navegador y visita:

    http://localhost:8080/hello

Deberías ver el mensaje: ¡Hola, mundo!.

#### Tecnologías Utilizadas
Spring Boot: Framework para aplicaciones Java.

Maven: Gestor de dependencias y construcción del proyecto.

Java: Lenguaje de programación.

##### Estructura del Proyecto
mi-proyecto-spring-boot/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/demo/
│   │   │       ├── MiPrimerSpringBootApplication.java
│   │   │       └── HelloController.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/example/demo/
│               └── MiPrimerSpringBootApplicationTests.java
├── pom.xml
└── README.md

