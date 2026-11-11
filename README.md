# ERP-academico
🍞 PamPam — Sistema Integral de Gestión para Panaderías

PamPam es una solución de software de gestión integral desarrollada para la empresa Bakehouse & Co. El sistema integra en una sola plataforma la automatización del punto de venta, la deducción inteligente de inventario a partir de recetas, el control de costos por desperdicio y la predicción asistida para la producción diaria.


😮Características Principales

El sistema está estructurado bajo tres niveles de sistemas de información:

1. Sistema de Procesamiento de Transacciones (TPS)

Ventas en Caja: Registro rápido de transacciones diarias.

Inventario Automatizado: Descuento automático de materia prima (harina, huevos, azúcar, etc.) según las recetas vinculadas a cada producto vendido.

2. Sistema de Información Gerencial (MIS)

Control de Mermas: Registro de productos no vendidos al finalizar la jornada.

Costeo de Desperdicio: Cálculo del impacto monetario exacto generado por las mermas operativas.

3. Sistema de Soporte a Decisiones (DSS)

Planificación de Producción: Algoritmo de recomendación que analiza el historial de ventas para sugerir la cantidad óptima de pan a hornear al día siguiente, reduciendo la sobreproducción.


📁 Estructura del Proyecto

PamPam/

├── pampam_app.py                # Aplicación principal y punto de entrada de la interfaz/lógica

├── usuarios.py                  # Módulo de administración de usuarios, roles y autenticación

├── test_login.py                # Script de pruebas para validación del inicio de sesión

├── pampam.db                    # Base de datos principal en SQLite

├── pampam_respaldo_20261101.db  # Copia de seguridad de la base de datos

├── README.md                    # Documentación del proyecto

└── __pycache__/                 # Archivos de caché compilados de Python



🛠️ Requisitos del Sistema

Lenguaje: Python 3.10 o superior (Probado en Python 3.14).

Base de Datos: SQLite3 (incluido en la biblioteca estándar de Python).

Dependencias: Verificadas e integradas mediante la sintaxis nativa de Python.


💻 Instalación y Ejecución

Clonar o descomprimir el proyecto:
Asegúrate de tener todos los archivos dentro del directorio PamPam/.

Ejecutar la aplicación:
Abre una terminal en la carpeta del proyecto y ejecuta:

python pampam_app.py


Ejecutar pruebas de inicio de sesión:
Para verificar la funcionalidad de autenticación y roles de usuario:

python test_login.py



🏢 Organización

Cliente / Proyecto: Bakehouse y Co.
