# Comandos
## Instalar dependencias
`pip install --no-cache-dir --upgrade -r requirements.txt`
## Ejecutar el servicio
`uvicorn app.main:app --host 0.0.0.0 --port 8000`
## Ejecutar pruebas unitarias
`python -m unittest discover tests`
## Compilar Docker
`docker build -t flexon1992/test1:latest .`