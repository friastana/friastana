# friastana.com

Laravel 10 with Inertia.js

## Installation

Use [docker](https://www.docker.com/) and [wsl](https://learn.microsoft.com/en-us/windows/wsl/install) for windows user

```bash
docker run --rm \
    -u "$(id -u):$(id -g)" \
    -v "$(pwd):/var/www/html" \
    -w /var/www/html \
    laravelsail/php82-composer:latest \
    composer install --ignore-platform-reqs

npm ci
```

## Usage

```bash
./vendor/bin/sail up
```
