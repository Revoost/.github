# 🛠 Guía de Estilo de Contribución

¡Hola! 👋 Para mantener un historial de proyecto limpio, legible y fácil de seguir, seguimos la convención de **Conventional Commits**. Por favor, asegúrate de clasificar tus cambios según las siguientes categorías:

### 📝 Estándares de Commits

| Prefijo | Tipo de Cambio | Descripción |
| --- | --- | --- |
| ✨ **feat** | Característica | Añade una nueva funcionalidad al código. |
| 🐛 **fix** | Corrección | Soluciona un error o bug. |
| ⚙️ **refactor** | Refactorización | Cambios en el código que ni corrigen errores ni añaden funciones. |
| 🚀 **perf** | Rendimiento | Mejora el rendimiento del software sin cambiar su lógica. |
| 🎨 **style** | Estilo | Cambios visuales o de formato (espacios, puntos y coma, etc.). |
| 🧪 **test** | Pruebas | Añadir pruebas que faltaban o corregir pruebas existentes. |
| 📚 **docs** | Documentación | Cambios solo en la documentación (como este README). |
| 🏗️ **build** | Construcción | Cambios que afectan el sistema de construcción o dependencias. |
| 🛠️ **ops** | Operaciones | Cambios en infraestructura, despliegue o CI/CD. |
| 🧹 **chore** | Tareas | Tareas mundanas que no alteran el código (ej: `.gitignore`). |

---

### 💡 Ejemplo de uso

Para realizar un commit correctamente, usa el formato:
`tipo: descripción breve en minúsculas`

* `feat: add user authentication via OAuth2`
* `fix: resolve memory leak in data parser`

> [!TIP]
> **¿Por qué hacemos esto?**
> Un historial de commits estandarizado permite generar *changelogs* automáticos y facilita la revisión de código para todo el equipo.
