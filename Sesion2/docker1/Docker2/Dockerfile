#Imagen Base de python
FROM python:3.8-slim 

#Establecer nuestro espacio de trabajo
WORKDIR /app

#Mover mis archivos a mi espacio de trabajo
COPY requirements.txt ./

#Instalar los paquetes 
RUN pip install --no-cache-dir -r requirements.txt

#Copiar todos los archivos al espacio de trabajo
COPY . .

EXPOSE 5000

