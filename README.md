# Session-1-con-Django

Proyecto Django de la Sesión 01: desarrollo de aplicaciones empresariales con Python y Django.

## Contenido

- **`/`** — Presentación interactiva sobre Python + Django (navegación con flechas ← →).
- **`/inicio/`** — Landing page de ejemplo.
- **`/admin/`** — Panel de administración de Django.

## Estructura

```
Sesion-01/
├── manage.py
├── config/        # configuracion del proyecto (settings, urls)
├── core/          # app registrada en INSTALLED_APPS
└── requirements.txt
```

## Requisitos

- Python 3.13+
- Django 6.1

## Instalación

```powershell
virtualenv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Abrir http://127.0.0.1:8000/

## Superusuario del admin

```powershell
python manage.py createsuperuser
```