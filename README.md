# Proyecto Final Git
# Hay un cambio remoto
# Proyecto Final – Git y GitHub  
Electiva Profesional – Ingeniería de Sistemas

## Descripción del Proyecto
Este proyecto fue desarrollado como parte de la electiva profesional de GitHub. Su objetivo es aplicar todas las prácticas recomendadas de control de versiones, colaboración, manejo de ramas, resolución de conflictos y documentación profesional.

El proyecto incluye ejemplos reales de:
- Creación y gestión de ramas (feature, fix, documentation)
- Issues y etiquetado
- Uso de Projects tipo Kanban
- Pull, Push, Merge y manejo de conflictos
- Pull Requests 
- Documentación mediante README.md y BITACORA.md

## Estructura del Proyecto


## Flujo de Trabajo Utilizado
### 1. Ramas
Se implementó el siguiente estándar:

- `main` → rama principal  
- `feature/*` → nuevas funcionalidades  
- `fix/*` → correcciones y ajustes  
- `documentation/*` → documentación del proyecto  

### 2. Issues
Se crearon issues para:
- Estructura inicial  
- Creación de funcionalidades  
- Correcciones  
- Documentación  
- Conflictos    
- Project Kanban  

###  3. Project Kanban
Se configuró un tablero Kanban con columnas:
- **To Do**
- **In Progress**
- **Done**

Cada Issue fue vinculado para gestión visual del flujo.

### 4. Pull Requests
Cada cambio fue integrado a través de PRs con revisión previa.

### 5. Resolución de Conflictos
Se simuló un conflicto controlado en `README.md`, el cual fue resuelto manualmente.

## Comandos Git Usados Frecuentemente
```bash
git init
git clone <url>
git checkout -b feature/nueva-funcionalidad
git add .
git commit -m "mensaje descriptivo"
git pull origin main
git push -u origin feature/nueva-funcionalidad
git merge
git revert
git reset




