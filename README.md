# LocalDB AI 🐘🤖

Entorno de base de datos local con IA integrada, 100% privado sin datos en la nube.

## Stack

| Tecnología | Versión | Rol |
|-----------|---------|-----|
| Debian | 13.5 Trixie | Sistema operativo |
| PostgreSQL | 17 Alpine | Base de datos |
| pgAdmin | 4 latest | Administración visual + AI Assistant |
| Ollama | latest | Servidor LLM local |
| qwen2.5-coder | 3b | Modelo de IA para SQL |
| Docker Compose | - | Orquestación de contenedores |

## Características

- 🤖 **AI Assistant** en pgAdmin — genera SQL en lenguaje natural
- 📊 **Reportes automáticos** de seguridad, performance y diseño de schema
- 🔍 **AI Insights** para análisis de EXPLAIN plans
- 🔒 **100% local** — ningún dato sale de tu máquina
- 🐳 **Docker Compose** — levanta todo con un solo comando

## Requisitos

- Docker y Docker Compose instalados
- Mínimo 4GB de RAM
- ~3GB de espacio en disco para el modelo

## Inicio rápido

```bash
