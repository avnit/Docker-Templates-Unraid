# Docker-Templates-Unraid

<!-- ARCH-DIAGRAM:START -->

## Architecture

> Auto-generated architecture diagram. See [`docs/context-map.md`](docs/context-map.md) for the full context map (core application, containers/cloud, and database connections).

```mermaid
flowchart TD
  User([User / Client])
  App["Docker-Templates-Unraid"]
  DB0[("PostgreSQL / AlloyDB")]
  DB1[("MySQL / MariaDB")]
  User --> App
  App --> DB0
  App --> DB1
```

<!-- ARCH-DIAGRAM:END -->
