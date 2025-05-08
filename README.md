
# 🧠 FenrirAI

**FenrirAI** es una solución de automatización construida con [n8n](https://n8n.io/) que integra múltiples herramientas de inteligencia artificial para facilitar la gestión de tareas comunes en clases, como:

- 📩 Leer y enviar correos automáticamente.
- 🎥 Generar vídeos con inteligencia artificial.
- 💬 Interactuar mediante un chatbot conversacional.
- 🔗 Conectarse a APIs externas como Google, Groq y HuggingFace.

---

## 🚀 Tecnologías utilizadas en las Plantillas

**FenrirAI** aprovecha las capacidades de n8n para integrarse con una amplia variedad de herramientas y servicios, facilitando la automatización de tareas en entornos educativos. Algunas de las integraciones más destacadas incluyen:

### 📊 Productividad y Gestión de Datos

- **Google Sheets**: Automatiza la lectura y escritura de datos en hojas de cálculo.
- **Notion**: Gestiona bases de datos y páginas de contenido.
- **Airtable**: Sincroniza y organiza información en bases de datos relacionales.
- **Google Drive**: Gestiona archivos y carpetas en la nube.

### 💬 Comunicación y Notificaciones

- **Gmail**: Envía y recibe correos electrónicos automáticamente.
- **Slack**: Envía mensajes y notificaciones a canales o usuarios específicos.
- **Telegram**: Interactúa con bots y envía mensajes a chats.
- **Discord**: Gestiona mensajes y eventos en servidores.

### 🤖 Inteligencia Artificial y Automatización

- **HuggingFace API**: Integra modelos de lenguaje y visión para tareas de IA.
- **Groq API**: Utiliza modelos de IA para procesamiento de lenguaje natural.
- **LangChain**: Construye agentes autónomos y flujos de trabajo inteligentes.

### 🧰 Herramientas para Desarrolladores y APIs

- **HTTP Request**: Realiza llamadas a APIs RESTful personalizadas.
- **Webhooks**: Recibe y envía datos en tiempo real entre servicios.
- **MySQL / PostgreSQL**: Conecta y manipula bases de datos relacionales.

### 📈 Marketing y CRM

- **HubSpot**: Automatiza la gestión de contactos y campañas de marketing.
- **Salesforce**: Sincroniza datos de clientes y oportunidades de venta.
- **Mailchimp**: Gestiona listas de correo y envíos masivos.

---

## 🛠 Instalación (en Linux)

Sigue estos pasos para poner en marcha el entorno de N8N:

```bash
# 1. Instalar Node.js y npm (si no lo tienes)
sudo apt update
sudo apt install nodejs npm

# 2. Instalar n8n globalmente
npm install n8n -g

# 3. Iniciar n8n
n8n start
```

### 🌐 Configurar dominio personalizado (opcional)

Si deseas exponer n8n con una URL propia (por ejemplo, usando un servidor o servicio como Ngrok, Nginx, etc.):

```bash
export WEBHOOK_URL=https://tudominio.com/
n8n start
```

---

## 📂 Estado del proyecto

🔒 Proyecto privado por ahora. Planeado para hacerse público en próximas versiones.

---

## ✍️ Autor

**FenrirAI** ha sido desarrollado por Cristian Vázquez.

---

## 📌 Notas adicionales

- Este proyecto está en constante desarrollo.
- Se recomienda tener conocimientos básicos de automatización con n8n para aprovecharlo al máximo.

---
