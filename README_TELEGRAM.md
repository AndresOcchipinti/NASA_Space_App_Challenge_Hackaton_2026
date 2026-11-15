
# AETHER - Asistente Médico y Logístico Espacial (Telegram Bot)

**AETHER** es un bot de Telegram inteligente impulsado por la API de Google Gemini y respaldado por una arquitectura serverless en **Supabase** (mediante Edge Functions). Su propósito principal es servir como un puente de comunicación y consulta de datos críticos entre los **doctores** y los **astronautas** en misiones espaciales.

---

## 🚀 ¿Cómo encontrar y probar el bot?

Puedes interactuar directamente con AETHER en Telegram a través del siguiente enlace:
👉 **[t.me/AETHER_NASA_BOT](https://t.me/AETHER_NASA_BOT)**

---

## 🌟 Funcionalidades Principales

AETHER está diseñado con roles diferenciados para optimizar la atención médica y la gestión a bordo de la nave:

### 1. Para el Personal Médico (Doctores)
* **Monitoreo de Tripulación:** Consulta rápida de los signos vitales y datos biométricos de los astronautas (presión arterial, ritmo cardíaco, etc.).
* **Evaluación Asistida por IA:** Uso de la API de Gemini para analizar tendencias de salud y facilitar la toma de decisiones clínicas a distancia.

### 2. Para los Astronautas
* **Autoconsulta de Salud:** Los tripulantes pueden buscar y verificar sus propios registros médicos y métricas de bienestar personal.
* **Inventario y Logística:** Consulta en tiempo real del stock disponible a bordo (suministros, equipamiento, raciones).
* **Gestión de Puntos de Nave:** Seguimiento y consulta del sistema de puntos y actividades de la tripulación en la nave.

---

## 🛠️ Arquitectura y Stack Tecnológico

Dado que el bot está desplegado en un entorno moderno y sin servidores tradicionales:
* **Modelo de Inteligencia Artificial:** API de Google Gemini para procesamiento de lenguaje natural y respuestas contextuales.
* **Backend / Lógica:** Supabase Edge Functions (ejecutándose en serverless TypeScript/JavaScript).
* **Interfaz de Usuario (Telegram):** Interfaz de chat directa con comandos optimizados para la tripulación y el cuerpo médico.
