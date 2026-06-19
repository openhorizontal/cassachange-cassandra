

# 1. Login
<!-- https://github.com/settings/tokens -->
echo <your-github-token> | docker login ghcr.io -u <your-github-username> --password-stdin

# 2. Build
docker build -t ghcr.io/openhorizontal/cassandra-migrations:v1.0.0 .

# 3. Push
docker push ghcr.io/openhorizontal/cassandra-migrations:v1.0.0