# Docker for rustdesk-server

Put HOSTNAME=your-host.name in .env file and run docker-compose up -d.

Keypairs created automatically and stored in ./id_ed25519.pub и ./id_ed25519 of containers volume. To change you need login on container with docker exec -it hbbr bash and edit this files manually.
