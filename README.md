# Plex

A self-hosted application for managing plex.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/plex/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/plex" ~/.local/srv/docker/plex
cd ~/.local/srv/docker/plex
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install plex
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
