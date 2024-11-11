# Usar imagen base de Python 3.12
FROM python:3.12-slim

# Establecer el directorio de trabajo
WORKDIR /app

# Copiar los archivos necesarios
COPY numeroaleatorio.py /app/

# Si tienes un requirements.txt, copia y haz el pip install
#COPY requirements.txt /app/
#RUN pip install --no-cache-dir -r requirements.txt

# Ejecutar el script Python
CMD ["python", "numeroaleatorio.py"]
