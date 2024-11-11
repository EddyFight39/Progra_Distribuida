# Usar una imagen base de Python 3.12
FROM python:3.12-slim

# Establecer el directorio de trabajo en el contenedor
WORKDIR /app

# Copiar los archivos del proyecto al contenedor
COPY numeroaleatorio.py /app/
COPY requirements.txt /app/

# Instalar las dependencias
RUN pip install --no-cache-dir -r requirements.txt

# Ejecutar el script de Python
CMD ["python", "numeroaleatorio.py"]
