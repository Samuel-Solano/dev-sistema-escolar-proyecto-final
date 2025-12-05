# Sistema de Gestión Escolar

Este proyecto es una aplicación web completa para la administración y gestión de procesos escolares.

## 🚀 Tecnologías Utilizadas

### Backend

- **Python** (v3.13)
- **Django** (Framework principal)
- **Base de Datos:** MySQL (Gestionada localmente con XAMPP)

### Frontend

- **Angular**
- **HTML5 / SCSS / TypeScript**

## 📂 Estructura del Proyecto

- `/backend`: Lógica del servidor (Django) y conexión a base de datos.
- `/frontend`: Interfaz de usuario (Angular).

## 🔧 Instalación y Configuración

### Pre-requisitos

- Python 3.13+
- Node.js y NPM
- XAMPP (para la base de datos MySQL)

### Pasos para ejecutar localmente

1. **Base de Datos:**

   - Abre XAMPP y enciende el servicio **MySQL**.
   - Crea una base de datos vacía en phpMyAdmin llamada `dev_sistema_escolar_db`

## 💻 Instrucciones de Instalación

### Backend (Django)

1.  Clonar el repositorio:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```
2.  Crear y activar un entorno virtual:
    ```bash
    python -m venv venv
    # Windows: venv\Scripts\activate
    # Linux/Mac: source venv/bin/activate
    ```
3.  Instalar las dependencias:
    ```bash
    pip install -r requirements.txt
    ```
4.  Realizar migraciones y ejecutar el servidor:
    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

### Frontend (Angular)

1.  Navegar a la carpeta del frontend:
    ```bash
    cd frontend
    ```
2.  Instalar dependencias:
    ```bash
    npm install
    ```
3.  Ejecutar el servidor de desarrollo:
    ```bash
    ng serve
    ```
