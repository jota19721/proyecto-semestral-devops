# Proyecto Semestral DevOps

Aplicación desplegada mediante Docker, Docker Compose y AWS EC2.

## Servicios

- Frontend despacho
- Backend ventas
- Backend despachos
- Base de datos MySQL ventas
- Base de datos MySQL despachos

## Tecnologías utilizadas

- Docker
- Docker Compose
- Spring Boot
- React
- MySQL
- AWS EC2
- Docker Hub
- GitHub

## Puertos

- Frontend: 80
- Backend ventas: 8081
- Backend despachos: 8082

## Ejecución local

```bash
docker compose up -d

Endpoints

http://IP_PUBLICA

http://IP_PUBLICA:8081/api/v1/ventas

http://IP_PUBLICA:8082/api/v1/despachos

Evidencias realizadas
Contenerización de frontend y backends.
Publicación de imágenes en Docker Hub.
Despliegue en AWS EC2.
Configuración de Security Groups.
Validación de APIs REST.
Prueba de persistencia con MySQL.
Después en la terminal ejecuta:

git add README.md
git commit -m "Agrega documentacion del proyecto"
git push


Y reemplaza:
`IP_PUBLICA`

por:

`54.243.24.2`

Luego:
- Guarda
- Abre terminal
- Ejecuta:

```powershell
git add README.md
git commit -m "Agrega README del proyecto"
git push
```