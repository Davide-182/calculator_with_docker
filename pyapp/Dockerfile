# Usa un'immagine di base Python con supporto per Flask
FROM python:3.8-slim

# Imposta la directory di lavoro all'interno del container
WORKDIR /pyapp

# Copia i file dell'applicazione nella directory di lavoro
COPY . /pyapp

# Installa Flask
RUN pip install flask

# Comando di avvio dell'applicazione
CMD ["python", "calculator.py"]
