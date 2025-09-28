# 🎵 Son1kVers3 Enhanced - Backend

Sistema de generación musical avanzado con IA - Backend API

## 🚀 Características

- **FastAPI** - Framework web moderno y rápido
- **Python 3.12** - Última versión de Python
- **Web Audio API** - Procesamiento de audio en tiempo real
- **Voice Cloning** - Clonación de voz con so-VITS y Bark
- **Nova Post Pilot** - Análisis de redes sociales con IA
- **Ghost Studio** - Analizador de audio avanzado
- **Stealth System** - Sistema de evasión de detección

## 🔧 Instalación

```bash
pip install -r requirements-simple.txt
```

## 🚀 Ejecución

```bash
python3 -m uvicorn main:app --host 0.0.0.0 --port 8000
```

## 📋 Variables de Entorno

- `NODE_ENV=production`
- `PYTHON_VERSION=3.12`
- `HOST=0.0.0.0`
- `PORT=8000`
- `JWT_SECRET_KEY=tu_secret_key`
- `DATABASE_URL=sqlite:///./son1kvers3.db`

## 🌐 Endpoints

- `GET /` - Health check
- `GET /health` - Estado del sistema
- `GET /docs` - Documentación API
- `POST /api/music/generate` - Generar música
- `POST /api/voice/clone` - Clonar voz
- `POST /api/social/analyze` - Analizar redes sociales

## 🚀 Deploy en Railway

1. Conecta este repositorio a Railway
2. Railway detectará automáticamente `railway.json`
3. Deploy automático

## 📦 Estructura

```
├── main.py                 # Aplicación principal
├── requirements-simple.txt # Dependencias
├── railway.json           # Configuración Railway
├── services/              # Servicios de IA
├── api/                   # Endpoints REST
└── utils/                 # Utilidades
```

## 🔗 Enlaces

- **Frontend:** https://github.com/nov4-ix/son1kvers3-enhanced
- **Railway:** https://railway.app
- **Documentación:** `/docs`

---

**Son1kVers3 Enhanced v2.0** - Sistema completo de generación musical con IA
