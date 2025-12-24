# nginx-dummy-proxy
Alternative for not opening ports other than 22, 403 and 80.

### **.env** file
```markdown
# Port of your service that will be proxied to 443
APP_PORT=8888

# Service name (container name) of your app
APP_SERVICE_NAME=stroke-jupyter

# Network name (already using the existing one)
NETWORK_NAME=stroke-predict-spark-feast_stroke-network
```

### Certificate must be created with sudo - sudo make ssl

### make up

### make down




