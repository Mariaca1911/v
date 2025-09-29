# ViveMedellin-f4

Proyecto base en Spring Boot para CommunityApp.

## Dependencias principales
- Spring Web
- Spring Security
- H2 Database
- Lombok

## Estructura de paquetes
- com.communityapp.auth.controller
- com.communityapp.auth.service
- com.communityapp.auth.config
- com.communityapp.group.controller
- com.communityapp.group.service
- com.communityapp.group.model
- com.communityapp.common


## Endpoints
- POST /api/groups/create

## 🚀 Cómo ejecutar

### Requisitos
- JDK 17 o superior
- Maven 3.6+



**Para ejecutar**
mvn spring-boot:run


**Aplicación disponible en:** http://localhost:8080


##  Credenciales de acceso
- **Usuario:** `user`
- **Contraseña:** `password`

## Probar login

$body = '{"username":"user","password":"password"}'
$response = Invoke-WebRequest -Uri "http://localhost:8080/api/auth/login" -Method POST -Body $body -ContentType "application/json"
$response.Content





