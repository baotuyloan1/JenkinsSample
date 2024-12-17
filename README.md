Installing Jenkins using Docker Compose

# Step 1

Build the Jenkins Docker image
```cmd
docker build -t my-jenkins .
```

# Step 2

Start Jenkins:
```cmd
docker compose up -d
```