# Miranda Clinics Website

Static clinic website with a modern landing page and doctor schedule sections.

## Run locally

```bash
docker-compose up --build
```

Then open http://localhost:8080

## Deploy with Docker

Build the image:

```bash
docker build -t miranda-clinics .
```

Run the container:

```bash
docker run -d -p 8080:80 --name miranda-clinics miranda-clinics
```

## GitHub Actions

Pushing to the main branch triggers a workflow that builds and publishes the Docker image to GitHub Container Registry.
