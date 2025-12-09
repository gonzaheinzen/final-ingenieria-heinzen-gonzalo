# Final Ingeniería de Software – Gonzalo Heinzen

Este es un proyecto mínimo para la consigna del examen.

## Contenido
- `index.html`: página con nombre y legajo.
- `Dockerfile`: para contenerizar la aplicación.

## Comandos utilizados

mkdir final-ingenieria-heinzen-gonzalo
cd final-ingenieria-heinzen-gonzalo
docker build -t final-ingenieria-heinzen-gonzalo .
docker run -d -p 8080:80 --name final-container final-ingenieria-heinzen-gonzalo


## Cómo ejecutar
1. Clonar el repositorio:
   
   ```bash
   git clone https://github.com/gonzaheinzen/final-ingenieria-heinzen-gonzalo.git
   
2. Acceder a la carpeta:
   
   ```bash
   cd final-ingenieria-heinzen-gonzalo

3. Construir la imagen:
   
   ```bash
   docker build -t final-ingenieria-heinzen-gonzalo .

4. Ejecutar el contenedor:
   
   ```bash
   docker run -d -p 8080:80 --name final-container final-ingenieria-heinzen-gonzalo

5. Abrir el navegador en:
   
   ```bash
   http://localhost:8080
