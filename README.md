# mysd-example-codespace

Entorno de Codespaces / Dev Containers con una base de datos **PostgreSQL 16** lista para usar desde VS Code.

## Iniciar

- **Codespaces:** **Code → Codespaces → Create codespace on main**.
- **Local (VS Code + Docker):** abre la carpeta y ejecuta **Dev Containers: Reopen in Container**.

## Conectarse

Se instala la extensión **PostgreSQL** de Microsoft con la conexión **MYSD PostgreSQL** ya configurada.

1. Abre el icono de **PostgreSQL** en la barra lateral.
2. Selecciona **MYSD PostgreSQL** y conéctate (si pide contraseña: `student`).
3. Abre una consulta nueva (**New Query**) y ejecuta tu SQL.

| Host | Puerto | Base de datos | Usuario | Contraseña |
|------|--------|---------------|---------|------------|
| `localhost` | `5432` | `mysd` | `student` | `student` |

> Credenciales solo para clase. Los datos se conservan entre reinicios del Codespace.
