
# Base de datos: Trabajo Practico final

---
## Requisitos
Para poder ejecutar este proyecto se necesita
- Docker (en particular, `docker_compose`)
- NodeJS

---

## Como iniciarlo
Primero clone el repositorio en su computadora, y vaya a su ubicacion.

### Back-end
Vaya a la carpeta del back-end:
```bash
cd ./bbd-tp-back
``` 

Inicia los contenedores docker:
```bash
docker-compose up -d
``` 

Instala las dependencias del servidor back-end:
```bash
npm install
``` 

Inicia el servidor back-end:
```bash
npm start
```

### Front end
Instala las dependencias del front-end:
```bash
npm install
``` 

Inicia el front-end:
```bash
npm start
```
