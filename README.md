# Milvus Local

Runs Milvus vector database locally via Docker Compose.

## Services

| Service | Port |
|---------|------|
| Milvus  | 19531 |
| Attu (UI) | 8002 |
| MinIO (console) | 9002 |

## Usage

```sh
make up    # start
make down  # stop
```

Attu UI: http://localhost:8002
