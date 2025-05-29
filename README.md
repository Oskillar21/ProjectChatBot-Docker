
---

### 🐳 `ProjectChatBot-Docker` → `README.md`

```markdown
# ProjectChatBot-Docker

Proyecto que une múltiples microservicios relacionados con embeddings y procesamiento de lenguaje natural. Usa Docker Compose para orquestar los contenedores de Chroma-DB-Load, Node-API-Bridge y Chroma-DB-EmbeddingsPool.

## Servicios incluidos

- `Chroma-DB-Load`: API para cargar y guardar embeddings
- `Node-API-Bridge`: Puente entre la base de datos y el bot
- `Chroma-DB-EmbeddingsPool`: Procesador de documentos con embeddings

## Uso

```bash
# Clonar el repositorio
git clone https://github.com/Oskillar21/ProjectChatBot-Docker.git
cd ProjectChatBot-Docker

# Construir y levantar los contenedores
docker-compose up --build
