# 🤖 Antigravity AI

Sistema Multi-Agente basado en Google Gemini 2.5 Flash.

---

## Características

✅ Generación automática de código

✅ Revisión de arquitectura

✅ Análisis de errores

✅ Seguridad

✅ Corrección automática

✅ Generación de pruebas

✅ Documentación

✅ Memoria

✅ FastAPI

---

# Arquitectura

```
Usuario
    │
    ▼
Orchestrator
    │
────────────────────────────
│      │      │      │
▼      ▼      ▼      ▼
Generator
Analyzer
Security
Debugger
│
▼
Reviewer
│
▼
Tester
│
▼
Documentation
│
▼
Proyecto Final
```

---

# Instalación

Crear entorno virtual

Windows

```bash
python -m venv .venv
```

Activar

```bash
.venv\Scripts\activate
```

Instalar dependencias

```bash
pip install -r requirements.txt
```

Configurar

Crear un archivo `.env`

```env
GOOGLE_API_KEY=TU_API_KEY
MODEL_NAME=gemini-2.5-flash
```

Ejecutar

```bash
python app.py
```

---

# Agentes

## Code Generator

Genera proyectos completos.

---

## Analyzer

Analiza arquitectura.

---

## Security

Busca vulnerabilidades.

---

## Debugger

Encuentra errores.

---

## Reviewer

Evalúa calidad.

---

## Tester

Genera pruebas unitarias.

---

## Documentation

Genera README y documentación.

---

## Memoria

Cada interacción queda almacenada para que los agentes aprendan del contexto del proyecto.

---

# Tecnologías

- Python 3.12
- Google Gemini
- FastAPI
- Rich
- GitPython
- Pytest
- Bandit
- Black
- Isort

---

# Próximamente

- Docker
- MCP
- GitHub Actions
- CI/CD
- Multi Workspace
- Web UI
- Agentes paralelos