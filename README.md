
# 🧠 FenrirAI

**FenrirAI** es una solución de automatización construida con [n8n](https://n8n.io/) que integra múltiples herramientas de inteligencia artificial para facilitar la gestión de tareas comunes en clases, como:

- 📩 Leer y enviar correos automáticamente.
- 🎥 Generar vídeos con inteligencia artificial.
- 💬 Interactuar mediante un chatbot conversacional.
- 🔗 Conectarse a APIs externas como Google, Groq y HuggingFace.

---

## 🚀 Tecnologías utilizadas

- [n8n](https://n8n.io/)
- API de Google (Gmail, Calendar, etc.)
- [Groq API](https://console.groq.com/)
- [HuggingFace API](https://huggingface.co/)
- Otras integraciones personalizadas

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
