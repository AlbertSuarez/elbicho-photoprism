# El Bicho: PhotoPrism

📸 Self-hosted version of the PhotoPrism for my workstation (El Bicho)

## Requirements

- Docker-compose

## Usage

### Docker-compose command reference

See more information [here](https://docs.photoprism.app/getting-started/docker-compose/#command-line-interface).

```
Start    | docker-compose up -d
Stop     | docker-compose stop
Update   | docker-compose pull
Logs     | docker-compose logs --tail=25 -f
Terminal | docker-compose exec photoprism bash
Help     | docker-compose exec photoprism photoprism help
Config   | docker-compose exec photoprism photoprism config
Reset    | docker-compose exec photoprism photoprism reset
Backup   | docker-compose exec photoprism photoprism backup -a -i
Restore  | docker-compose exec photoprism photoprism restore -a -i
Index    | docker-compose exec photoprism photoprism index
Reindex  | docker-compose exec photoprism photoprism index -f
Import   | docker-compose exec photoprism photoprism import
```
