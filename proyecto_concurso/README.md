🐉 MIMWU – Wallet Inteligente

Proyecto desarrollado por Quetzal Dragons

👥 Integrantes del equipo

Nombre	Rol

Christopher Jue Mora Sánchez	Director del proyecto, programador full-stack, creador de la arquitectura

Ghandi Alexis Ornelas Martínez	Diseñador gráfico, creador del logo y branding visual

Quetzal Dragons	Equipo responsable del desarrollo y conceptualización del proyecto

💡 ¿Qué es MIMWU?

MIMWU es una billetera virtual inteligente diseñada para ayudar a los usuarios a administrar sus finanzas personales mediante:

Registro de cuentas bancarias simuladas

Control de ingresos y gastos

Análisis financiero inteligente

Gráficas dinámicas basadas en movimientos

Administración completa de tarjetas y transferencias

Es una herramienta educativa que simula de forma realista el funcionamiento de una wallet moderna.

🧩 Problema que resuelve

Muchas personas enfrentan dificultades para:

Llevar control de sus gastos

Visualizar sus movimientos financieros

Entender cómo se distribuye su dinero

Realizar transferencias o administrar cuentas de manera simple

MIMWU resuelve esto con un panel intuitivo que muestra tus cuentas, transacciones, análisis y gráficos de manera clara.

🚀 Funcionalidades principales

🔐 Autenticación

Registro de usuarios

Inicio de sesión seguro (hash de contraseñas)

💳 Gestión de cuentas

Crear cuentas bancarias simuladas

Listado dinámico de cuentas

Cálculo automático de saldos

💳 Gestión de tarjetas

Registrar tarjetas de débito y crédito

Establecer límites de crédito

Administración centralizada

🔄 Transferencias

Simulación de movimientos entre cuentas

Cálculo automático de saldos actualizados

📊 Visualización financiera

Gráficos dinámicos generados con Chart.js

Gastos por categoría

Ingresos por categoría

Saldo total por cuenta

🤖 Inteligencia financiera

Análisis automático de transacciones

Sugerencias de ahorro

Lectura de patrones financieros

🛠️ Tecnologías utilizadas
Frontend

HTML5

CSS3

JavaScript

Chart.js (gráficas)

Fetch API

Backend

Python

Flask

Flask-CORS

Werkzeug (hash de contraseñas)

Base de Datos

MySQL (local con XAMPP)

Estructura de Proyecto

MIMWU/

├── BACKEND/

├── app.py

├── analisis.py

├── db.py

├── schema.sql

├── seed.sql

└── venv/

└── FRONTEND/

├── login.html
    
├── register.html
    
├── dashboard.html
    
├── style.css
    
└── dashboard.js


▶️ Instrucciones para ejecutar MIMWU

📌 Requisitos previos

Antes de iniciar, necesitas tener instalado:

✔ Python 3.10+
✔ MySQL (XAMPP)
✔ Navegador web
✔ Visual Studio Code (opcional)

🖥️ 1. Configurar Base de Datos

Inicia XAMPP → activa MySQL

En phpMyAdmin, crea la BD:

CREATE DATABASE mimwu;


Importa los archivos:

schema.sql → crea las tablas

seed.sql → inserta datos iniciales

🐍 2. Instalar dependencias del backend

En la carpeta:

MIMWU/BACKEND/


Ejecuta:

python -m venv venv
venv\Scripts\activate
pip install flask flask-cors mysql-connector-python werkzeug

🚀 3. Iniciar Backend

Dentro de:

MIMWU/BACKEND/


Ejecuta:

python app.py


Debes ver:

Running on http://127.0.0.1:5000


Esto significa que el servidor está activo.

🌐 4. Ejecutar el Frontend

Abre el archivo:

MIMWU/FRONTEND/login.html


O usa “Live Server” de VS Code.

El frontend corre en:

http://127.0.0.1:5500


Y se comunica con el backend en:

http://127.0.0.1:5000

🎯 5. Probar funcionalidades

Regístrate como nuevo usuario

Inicia sesión

Agrega cuentas bancarias

Registra tarjetas

Haz transferencias

Observa las gráficas dinámicas

Ejecuta análisis financiero

Todo en un dashboard centralizado.

⭐ Contribuciones

Proyecto académico desarrollado por Quetzal Dragons.

📜 Licencia

Uso educativo / demostrativo.
