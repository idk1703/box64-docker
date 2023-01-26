# box64-docker
Docker image for run x64 binaries on arm64 CPUs with box64

## Usage
cmd:
```bash
docker run -it idk1703/box64:latest
```

Dockerfile:
```dockerfile
FROM idk1703/box64:latest
...
CMD ["box64", "binary"]
```