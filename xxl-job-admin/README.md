# 跨平台构建

## Amd64 & Amd64

```bash
docker buildx build --platform linux/arm64,linux/amd64 -t registry.cn-beijing.aliyuncs.com/dc3/dc3-job:2024.1.1.dev . --push
```