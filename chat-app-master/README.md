chat-app
Esta es una aplicación de chat en tiempo real construida con Spring Boot y WebSocket.

Características
Mensajería en tiempo real entre usuarios.

Notificaciones de conexión y desconexión de usuarios.

Interfaz de usuario simple e intuitiva.

Tecnologías Utilizadas
Backend:

Java 21

Spring Boot 3

Spring WebSocket para comunicación en tiempo real.

Spring Data JPA para la interacción con la base de datos.

Base de datos H2 para el almacenamiento de datos en memoria.

Maven para la gestión de dependencias.

Frontend:

Thymeleaf como motor de plantillas del lado del servidor.

HTML5, CSS3, JavaScript.

StompJS para la comunicación vía WebSocket.

Cómo Ejecutar
Requisitos previos:

Java 21 o superior.

Maven 3.2+

Clonar el repositorio:

Bash

git clone https://github.com/James14k/chat-app.git
Navegar al directorio del proyecto:

Bash

cd chat-app
Ejecutar la aplicación usando Maven:

Bash

./mvnw spring-boot:run
Acceder a la aplicación: Abre tu navegador web y dirígete a http://localhost:8080

Estructura del Proyecto
.
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── cwa
│   │   │           └── chatapp
│   │   │               ├── config
│   │   │               │   ├── WebSocketConfig.java
│   │   │               │   └── WebSocketEventListener.java
│   │   │               ├── controller
│   │   │               │   ├── ApiController.java
│   │   │               │   ├── ChatController.java
│   │   │               │   └── WebController.java
│   │   │               ├── entity
│   │   │               │   ├── Message.java
│   │   │               │   └── User.java
│   │   │               ├── repository
│   │   │               │   ├── MessageRepository.java
│   │   │               │   └── UserRepository.java
│   │   │               └── service
│   │   │                   ├── MessageService.java
│   │   │                   └── UserService.java
│   │   └── resources
│   │       ├── static
│   │       │   ├── css
│   │       │   │   └── chat.css
│   │       │   └── js
│   │       │       └── chat.js
│   │       └── templates
│   │           ├── chat.html
│   │           └── index.html
│   └── test
└── pom.xml
