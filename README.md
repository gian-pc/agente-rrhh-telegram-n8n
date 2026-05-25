# Agente de RR.HH. en Telegram con n8n

Agente conversacional de Recursos Humanos desplegado en Telegram, 
construido con n8n, Cohere, Vector Store y MySQL en Railway.

## Demo

![Conversación en Telegram](images/telegram.jpeg)

## Arquitectura del Workflow

![Workflow en n8n](images/n8n.png)

## Base de Datos

![MySQL en Railway](images/MySQL.png)

## Stack Tecnológico

- **n8n** — orquestación del agente
- **Cohere** — modelo de lenguaje (LLM)
- **Simple Vector Store** — búsqueda semántica (RAG)
- **MySQL en Railway** — base de datos de empleados en producción
- **Telegram** — interfaz conversacional
- **Simple Memory** — contexto de conversación

## ¿Qué hace el agente?

- Saluda al empleado y solicita su nombre
- Consulta la base de datos de empleados en tiempo real
- Responde preguntas de RR.HH. usando búsqueda semántica
- Mantiene el contexto de la conversación
- Desplegado y funcional en producción vía Telegram

## Certificado

![Certificado Inmersión Agentes de IA](images/certificado.pdf)

Inmersión Agentes de IA — Oracle ONE + Alura (2026)