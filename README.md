# evol-app
🚀 Instalación y Configuración
1. Clonar el repositorio
cd evol-app
2. niciar con Docker Compose
# Construir e iniciar todos los servicios
docker-compose up --build
La aplicación estará disponible en:

Frontend: http://localhost:5173
Backend API: http://localhost:3000/api
PostgreSQL: localhost:5432

📁 Estructura del Proyecto
todo-app/
├── docker-compose.yml
├── backend/
│   ├── src/
│   │   ├── tasks/          # Módulo de tareas
│   │   ├── tags/           # Módulo de etiquetas
│   │   ├── database/       # Configuración de BD
│   │   └── common/         # Utilidades compartidas
│   └── test/
└── frontend/
    ├── src/
    │   ├── app/            # Store de Redux
    │   ├── components/     # Componentes React
    │   ├── features/       # Slices de Redux
    │   ├── hooks/          # Custom hooks
    │   ├── services/       # Servicios API
    │   ├── pages/          # Pages
    │   └── types/          # TypeScript types
    └── tests/
