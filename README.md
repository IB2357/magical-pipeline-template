## This repo 
contains a Docker Compose template for: 
- Dockerfile
- docker-compose.yml

to create these services:
- mage.ai (it already has dbt built in)
- postgres
- pgadmin4


___
You can start by cloning the repo:

```bash
git clone https://github.com/IB2357/magical-pipeline-template.git
```

Navigate to the repo:

```bash
cd magical-pipeline-template
```

Rename `example.env` to  `.env` and write your secrets

```bash
mv example.env .env
```

build the container

```bash
docker compose build
```

start the Docker container:

```bash
docker compose up
```

navigate to http://localhost:6789 for mage.ai
navigate to http://localhost:5050 for pgadmin4
