# MediaHub

### NGINX Static Webpage

## Docker Build multiple images
docker buildx build --push --platform linux/arm/v7,linux/arm64/v8,linux/amd64 --tag edward8e/mediahub:latest .
