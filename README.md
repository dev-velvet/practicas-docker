# Construir la imagen:
docker build -t dev-velvet/mi-linktree:latest .

# Desplegar contenedor:
docker run -d -p 8080:80 --name linktree dev-velvet/mi-linktree:latest