## Melvin Monitoring

This repository contains the files to create a Grafana monitoring dashboard for the melvin server.

### Requirements
- Linux based OS
- Docker
- [Optional] Nvidia GPU with Cuda installed for GPU analytics

### Installation
1. Replace the password in the .env.example with your own
2. Remove the ".example" from the .env file
3. Run `docker compose -p melvin-monitoring up -d`

### Customisation
You can change some settings in the .env file.

- Admin username
- Domain for the Grafana dashboard
- Grafana instance name

### Connect
Visit http://localhost:3030 or your custom domain