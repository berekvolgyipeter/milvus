# Milvus Local

Runs Milvus vector database locally via Docker Compose.

## Services

| Service | Port |
|---------|------|
| Milvus (gRPC) | 19531 |
| Milvus (metrics) | 9092 |
| Attu (UI) | 8002 |
| MinIO (API) | 9002 |
| MinIO (console) | 9003 |

## Usage

```sh
make up    # start
make down  # stop
```

Attu UI: http://localhost:8002
