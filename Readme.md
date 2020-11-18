## Vat verifier service

## Deployment
# Docker
1.Build current springboot app image:
```
docker build -t vat-verifier-app:1.0.0 .
```
2.Start the container:

```
docker run -d -p 8080:8080 -t vat-verifier-app:1.0.0
```
