# CV Agent 🤖

Agente conversacional que responde preguntas sobre un CV en PDF, con soporte de voz.

## Demo en vivo

👉 [Pruébalo aquí](https://adriancrevillen.github.io/cv-agent)

## ¿Qué hace?

- Sube cualquier CV en PDF y hazle preguntas en lenguaje natural
- Responde sobre experiencia, tecnologías, formación o fit para un puesto
- Soporta entrada por voz (Web Speech API) además de texto

## Tecnologías

- HTML + JavaScript vanilla (sin frameworks)
- [pdf.js](https://mozilla.github.io/pdf.js/) — extracción de texto del PDF en el navegador
- [Groq API](https://groq.com/) — LLM (LLaMA 3.3 70B) para las respuestas
- Web Speech API — reconocimiento de voz nativo del navegador
- Desplegado en GitHub Pages

## Para developers — ejecutar localmente

1. Clona el repositorio
2. Consigue una API key gratuita en [console.groq.com](https://console.groq.com)
3. Sustituye `TU_API_KEY_DE_GROQ_AQUI` en `index.html` por tu key
4. Abre `index.html` en Chrome
