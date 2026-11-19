# Proyectos para el portfolio

Aportes medidos por commits en el historial de GitHub (noviembre 2026). Los commits no miden todo el trabajo, pero sirven para saber qué parte es mía.

## Candidatos fuertes

### 1. herramienta_xAI (Trabajo Final, en curso)
Entorno interactivo para analizar modelos con IA Explicable (XAI) sobre imágenes médicas. Con Laura Stadler, para LPI y LABI (ICYTE).
- Mi aporte: 20 de 38 commits. Esqueleto del backend (FastAPI como monolito modular), esqueleto del frontend (Next.js + TS + shadcn), carga y preprocesamiento de imágenes PNG/JPG/DICOM, tests con PostgreSQL descartable (Testcontainers), decisiones de arquitectura (Redis + SSE, TensorFlow solo al subir modelos).
- Diferencial: desarrollo guiado por specs con agentes de IA (arnés SDD: spec aprobado → implementación con tests → review).
- Repo privado: felipesantiago002/herramienta_xAI
- Pendiente: confirmar con Laura y los directores qué se puede mostrar antes de defenderla. Capturas o demo cuando haya visualizaciones.

### 2. Virtual Pet (e-commerce, equipo de 5)
E-commerce de productos para mascotas (Mar del Plata): API, web de clientes, backoffice de depósito y app de repartidores.
- Stack: FastAPI, SQLAlchemy, Alembic, JWT con roles, WebSockets, Docker + nginx, S3, Railway; React + Tailwind + Zustand; Expo/React Native.
- Mi aporte:
  - Backend (26 de 59 commits, el que más aportó): chatbot de facturación con Gemini (guardrails, límites, tests), arreglo de una vulnerabilidad IDOR en el chatbot, broadcast de estados de pedidos por WebSocket, migraciones y desacople de módulos.
  - App móvil de repartidores (11 de 19 commits, el que más aportó): WebSocket con heartbeat, historial de entregas en tiempo real, builds de APK con EAS.
  - Backoffice de depósito (6 de 19): tablero de pedidos, cancelaciones, reconexión de WebSocket.
- Repos: LauStadler/Backend-VirtualPet, tomitomitomi3/virtual-pet-mobile, tomitomitomi3/virtual-pet-deposito, tomitomitomi3/virtual-pet-frontend, LauStadler/VirtualPet
- Pendiente: presentarlo como un solo proyecto con diagrama de arquitectura y la sección "qué hice yo".

### 3. Bot de trading algorítmico
Bot en Python que opera en Alpaca (paper trading) con estrategia de tendencia + cruce de MACD, tres entradas escalonadas y órdenes bracket.
- Corre con GitHub Actions; panel web en FastAPI que edita los parámetros como Variables del repo (los parámetros son datos, no código) y muestra estadísticas.
- Tests unitarios de estrategia, indicadores y estadísticas.
- Repo privado: felipesantiago002/bot_trading (proyecto propio, 100% mío)
- Pendiente: README. Si se hace público, revisar antes que no haya claves en el historial. Aclarar que es paper trading.

### 4. Test capilar para Liberata Hair Store (cliente real)
Test interactivo que diagnostica el cabello, recomienda una rutina con productos en stock, envía el resultado por email (Resend) y guarda el lead en Perfit. Front estático + función serverless en Vercel, claves solo en el servidor.
- Repo privado: felipesantiago002/liberata-hair-test (100% mío)
- Pendiente: confirmar con el cliente que se puede mostrar. Link al test en producción y capturas.
- Valor: es trabajo para un cliente real, no un TP.

### 5. KipuBankV3 (Solidity)
Contabilidad en USDC vía Uniswap V2, protección contra slippage, oráculo de precios, OpenZeppelin.
- Repo: felipesantiago002/KipuBankV3
- Pendiente: mostrar solo V3.

### 6. Detección de residuos con YOLOv8 (TACO)
- Repo: felipesantiago002/TPFINAL_ia
- Pendiente: README, métricas (mAP), imágenes de detecciones, quitar ruta absoluta del YAML.

## Secundarios
- Pomodoro en Next.js + TS (TP Sistemas Distribuidos): Palodeaza/TPFinal--SSDD. 8 de 18 commits, el que más aportó (timer e importación de rutinas).
- tcheg, marketplace TCG: tomitomitomi3/tcheg. 2 de 6 commits. Solo si se deploya y tiene README.

## Por revisar (fuera de GitHub o sin encontrar)
- Overlay de ARAM Mayhem
- CRM de WhatsApp con agente IA
- App de gimnasio

## Futuro: laboratorios de ciberseguridad
Se van a agregar más adelante, como categoría propia junto a los proyectos de desarrollo.
- Formato tentativo por lab: objetivo, herramientas, pasos clave, qué aprendí. Capturas sin datos sensibles.
- Plataformas: si son de HTB o similares, publicar solo writeups permitidos (por ejemplo, máquinas retiradas).
- El sitio tiene que estar preparado para esto desde el principio: categorías/filtros en el carrusel y páginas de detalle con soporte para bloques de código.

## Fuera
- TP de AyDs en Java (30 de 115 commits): académico, poco vistoso.
- Máquina virtual en C (2024): TP de primeros años, con varias versiones sueltas del main.
- Progra 3 (14 de 68), BPM / BPM2 (diagramas), SistemasDistribuidos (vacío), forks (harness-sdd, NuvioTV).

## Otros pendientes
- Actualizar README del perfil (dice "4to año").
