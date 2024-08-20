# Aplicación Web de Venta de Productos Informáticos

## Descripción

Esta es una aplicación web desarrollada para la venta de productos informáticos. 
Permite a los usuarios registrarse, iniciar sesión, ver productos, y realizar pedidos. 
La aplicación está construida con Python, Flask, y SQLAlchemy, y utiliza una base de datos SQL para gestionar los datos de los usuarios y los pedidos.


## Funcionalidades

- **Registro de usuarios:** Los usuarios pueden crear una cuenta y acceder a su perfil.
- **Visualización de productos:** Los usuarios pueden ver una lista de productos con descripciones e imágenes.
- **Carrito de compras:** Los usuarios pueden añadir productos al carrito y realizar pedidos.
- **Gestión de pedidos:** La aplicación gestiona el estado de los pedidos y proporciona detalles a los usuarios.
- **Modo Administrador:** Los administradores pueden acceder a un panel de administración para:
  - **Modificar la información de los productos**
  - **Añadir nuevos productos**
  - **Eliminar productos existentes**
  - **Gestionar pedidos y usuarios**


## Requisitos

- Python 3.x
- Flask
- SQLAlchemy
- Otras dependencias listadas en `requirements.txt`


## Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/carlosguzman1991/app-venta-productos-informaticos.git


2. **Instala las Dependencias**

Asegúrate de tener pip instalado, luego ejecuta:     pip install -r requirements.txt


3. **Configura la Base de Datos**

Crea una base de datos SQL (yo lo hice con DB Browser) y ajusta la configuración de conexión en el archivo de configuración de tu proyecto (generalmente config.py o similar).


4. **Ejecuta la Aplicación**

Ejecuta el servidor de desarrollo con:     python app.py


Estructura del Proyecto
app.py: Archivo principal que ejecuta la aplicación.
requirements.txt: Lista de dependencias necesarias para el proyecto.
config.py: Archivo de configuración de la base de datos y otras configuraciones.
static/: Archivos estáticos como CSS, imágenes y JavaScript.
templates/: Plantillas HTML para la aplicación.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

