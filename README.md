# 🚀 Proyecto Final DevOps

Aplicación web desarrollada con FastAPI y desplegada mediante Docker.
El proyecto utiliza GitFlow, GitHub Actions y Docker Hub.

## Integrantes
- Marcela Baldeón
- César Jácome

## Grupo
GRUPO 1

## Tecnologías
- Python 3.12
- FastAPI
- Uvicorn
- Docker
- Git y GitFlow
- GitHub Actions
- Docker Hub

## Estructura
```text
app/
├── main.py
└── templates/index.html
```

## Ejecución local
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## Imagen Docker
```bash
docker pull MarchelitaBG/proyecto-final-devops:v1
```

## Ejecución del contenedor
```bash
docker run -d --name proyecto-final-devops \
  -p PUERTO_HOST:8001 \
  -e GROUP_NAME="Grupo 1" \
  -e GROUP_MEMBERS="Marcela Baldeón, César Jácome" \
  -e COURSE_NAME="Devops utilizando tecnologías clave como Docker y Gitflow - GAD DMQ" \
  marchelita/proyecto-final-devops:v1
```

## Endpoints
- `/`
- `/health`
- `/info`
- `/metrics`
- `/docs`

## Enlaces
- GitHub: https://github.com/MarchelitaBG/proyecto-final-devops
- Docker Hub: PEGAR_URLproyecto-final-devopsproyecto-final-devops
