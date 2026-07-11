# SynckIA Backend Test

## Instalación

Crear entorno virtual:

```bash
python -m venv venv
```

Activar entorno:

```bash
venv\Scripts\activate
```

Instalar dependencias:

```bash
pip install -r requirements.txt
```

Ejecutar proyecto:

```bash
uvicorn main:app --reload
```

## Endpoints

### POST /upload
Permite subir un archivo Excel `.xlsx` y validar la información.

### GET /records
Permite consultar los registros almacenados con paginación.

Ejemplo:

```text
GET /records?page=1&page_size=20
```

## Tecnologías usadas

- Python
- FastAPI
- SQLAlchemy
- SQLite
- OpenPyXLs