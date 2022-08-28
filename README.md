# Sandbox by Karpec

### Build the containers

    docker-compose up -d --build

### Enter container php bash
    docker-compose exec php /bin/bash

### Enter container database bash
    docker-compose exec database /bin/bash

### Ensure that your setup meets the requirements for a Symfony
    symfony check:requirements
