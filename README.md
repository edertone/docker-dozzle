# docker-dozzle

Small application to check all your Docker container logs in real-time through a web interface.

<https://dozzle.dev/>

## Features

- Real-time log streaming for all running containers
- Accessible at [http://localhost:3007](http://localhost:3007)
- Zero-configuration setup

## Quick Start (Windows)

This repository includes batch scripts for easy management on Windows:

- `win-start.bat`: Starts the Dozzle container in the background.
- `win-stop.bat`: Stops and removes the Dozzle container.
- `win-update-to-latest-version.bat`: Pulls the latest Dozzle image and restarts the container.

## Manual Usage (Docker/Linux/macOS)

If you aren't using the provided Windows scripts, standard Docker Compose commands work:

```bash
# Start Dozzle
docker compose up -d

# Stop Dozzle
docker compose down
```
