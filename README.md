# 💬 Chat-App (Real-Time)

Esta es una aplicación de chat en tiempo real diseñada para ofrecer una experiencia de comunicación fluida y directa. Construida con **Spring Boot** para el robustez del backend y **WebSockets** para garantizar la bidireccionalidad de los mensajes.

---

## ✨ Características

* **Mensajería Instantánea:** Envío y recepción de mensajes en tiempo real sin recargar la página.
* **Gestión de Presencia:** Notificaciones automáticas cuando un usuario entra o sale de la sala.
* **UI Minimalista:** Interfaz de usuario limpia, intuitiva y fácil de usar.
* **Persistencia Ligera:** Uso de base de datos en memoria para agilidad en el desarrollo.

---

## 🛠️ Tecnologías Utilizadas

### **Backend**
* ![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat&logo=openjdk&logoColor=white) - Lenguaje principal.
* ![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=flat&logo=spring-boot&logoColor=white) - Framework base.
* **Spring WebSocket**: Implementación de protocolos para tiempo real.
* **Spring Data JPA**: Abstracción de persistencia de datos.
* **H2 Database**: Base de datos SQL en memoria.
* **Maven**: Gestión de dependencias y ciclo de vida del proyecto.

### **Frontend**
* ![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat&logo=thymeleaf&logoColor=white) - Motor de plantillas.
* ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) - Tecnologías web estándar.
* **StompJS**: Cliente para comunicación vía WebSocket.

---

## 📁 Estructura del Proyecto
.
├── src
│   ├── main
│   │   ├── java/com/cwa/chatapp
│   │   │   ├── config        # Configuración de WebSockets y eventos
│   │   │   ├── controller    # Endpoints de API y controladores web
│   │   │   ├── entity        # Modelos de datos (User, Message)
│   │   │   ├── repository    # Interfaces de Spring Data JPA
│   │   │   └── service       # Lógica de negocio
│   │   └── resources
│   │       ├── static        # Estilos (CSS) y scripts (JS)
│   │       └── templates     # Vistas HTML con Thymeleaf
│   └── test                  # Pruebas unitarias
└── pom.xml                   # Configuración de Maven

---



## 🚀 Cómo Ejecutar el Proyecto

### Requisitos previos
* **Java 21** o superior instalado.
* **Maven 3.2+** instalado.
  

### Pasos a seguir
1. **Clonar el repositorio:**
   ```bash
 git clone [https://github.com/James14k/chat-app.git](https://github.com/James14k/chat-app.git)

 2. *cd chat-app
 3. **./mvnw spring-boot:run
 4. **Abre tu navegador en: http://localhost:8080
 
