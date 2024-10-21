# Usar una imagen oficial de Python como base
FROM python:3.9-slim

#Establecer el directorio de trabajo en el contenbedor
WORKDIR /app

#Copiar los archivos de la aplicacion al contenedor
COPY . .

#Instalar las dependencias
RUN pip install -r requirements.txt

#Exponer el puerto 5000 para Flask
EXPOSE 5000

#Comando para ejecutar la aplicacion
CMD [ "python","app.py"]