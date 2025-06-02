# 🧾 SpeedOrder AI

**SpeedOrder AI** es una aplicación móvil construida con Flutter que digitaliza órdenes de servicio físicas mediante inteligencia artificial. Captura una foto de una hoja de orden, extrae automáticamente los datos importantes y los guarda en una base de datos como Google Sheets, Firebase o Supabase.

## 🚀 Funcionalidades

- 📸 Captura de imagen desde la cámara del dispositivo.
- 🧠 Reconocimiento de texto (OCR) usando `google_ml_kit`.
- 🧾 Identificación automática de campos clave:
  - Cliente
  - Fecha
  - Folio
  - Descripción del servicio
- ☁️ Envío automático de datos estructurados a una base de datos externa.

## 📱 Tecnologías

- **Flutter** – Framework para desarrollo multiplataforma.
- **google_ml_kit** – Reconocimiento óptico de caracteres (OCR).
- **Dart** – Lenguaje de programación principal.
- **(opcional)** Supabase / Firebase / Google Sheets – Almacenamiento de datos.

## 📌 Objetivo

Simplificar y automatizar el proceso de digitalización de órdenes de servicio para técnicos, pequeños negocios y profesionales independientes, reduciendo errores manuales y eliminando el uso de papel.

## 🛠️ Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/speedorder-ai.git
   cd speedorder-ai
   
2. Instala dependencias:
   ```bash
    flutter pub get

3. Corre en iOS:
    ```bash
    open ios/Runner.xcworkspace

Asegúrate de tener configurado tu bundle identifier y permisos de cámara.

📦 Roadmap (próximas funciones)
 Producción de Ordenes de Servicio Digitales.

 Reconocimiento de firmas en la hoja.
 
 Integración con correo para enviar al cliente.

🧠 Créditos
Desarrollado por Pedro Librado — proyecto en curso.

Este proyecto está en fase inicial. ¡Se aceptan sugerencias y contribuciones!
