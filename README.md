# Gestor de Tareas en Azure con Flask

Aplicación web simple para gestionar tareas mediante operaciones CRUD. Fue desarrollada con Flask y desplegada en Azure App Service, conectada a una base de datos Azure SQL Database.

## Descripción

La aplicación permite agregar, visualizar, marcar como completadas y eliminar tareas. El propósito del proyecto es demostrar el despliegue de una aplicación web en la nube usando servicios de Azure for Students.

## Tecnologías utilizadas

- Python
- Flask
- HTML/CSS
- Azure App Service
- Azure SQL Database
- GitHub

## Servicios de Azure utilizados

| Servicio | Propósito |
|---|---|
| Azure App Service | Alojamiento de la aplicación web |
| Azure SQL Database | Almacenamiento de las tareas |
| Resource Group | Organización de los recursos del proyecto |

## Variables de entorno

La aplicación usa las siguientes variables:

- SQL_SERVER
- SQL_DATABASE
- SQL_USERNAME
- SQL_PASSWORD

## Cómo ejecutar localmente

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py