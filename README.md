# Aplicación de Inventario Offline-First

Aplicación de inventario para pequeños negocios diseñada para funcionar sin conexión a internet.

## 📋 Características

- ✅ CRUD completo de productos
- ✅ Registro de entradas y salidas  
- ✅ Historial de movimientos por producto
- ✅ Funciona 100% offline
- ✅ Datos persisten entre sesiones
- ✅ Interfaz simple y clara

## 🛠 Stack Tecnológico

- **Frontend**: React 18 + Tailwind CSS
- **Backend**: Python FastAPI  
- **Base de Datos**: SQLite (local)

## 🚀 Instalación Rápida

### Requisitos Previos
- Python 3.9+
- Node.js 16+
- npm o yarn

### 1. Clonar el repositorio
```bash
git clone https://github.com/briandiaz1002-lab/inventory-offline-app.git
cd inventory-offline-app
```

### 2. Configurar Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Configurar Frontend
```bash
cd ../frontend
npm install
```

### 4. Ejecutar la Aplicación

**Terminal 1 - Backend:**
```bash
cd backend
source venv/bin/activate
uvicorn app.main:app --reload --port 8000
```

**Terminal 2 - Frontend:**
```bash
cd frontend
npm start
```

Abrir navegador en: `http://localhost:3000`

## 📚 Documentación

- Backend API Swagger: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`

## 🎯 Criterio de Éxito

✅ Clonar → Instalar → Levantar → Crear producto → Cerrar → Reabrir → Datos intactos

---

**Estado del Proyecto**: ✅ Funcional y listo para uso real
