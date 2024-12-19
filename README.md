# application

# Install Docker
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh

# Install Docker Compose
sudo apt install docker-compose-plugin



# Clone your repository
git clone <your-repo-url>
cd <your-repo-name>

# Build and start containers
docker compose up -d --build


# View logs
docker compose logs -f

# Stop application
docker compose down

# Update application
git pull
docker compose up -d --build

# Check container status
docker compose ps
