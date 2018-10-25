# Startkit Symfony with API platform

Symfony startkit with API platform for fast developing

## Getting Started

### Requirements
1. Install docker [documentation](https://docs.docker.com/install/#supported-platforms)
2. Install docker-compose [documentation](https://docs.docker.com/compose/install/)

### Prepare project and start project

Clone repository
```
git clone https://github.com/JosipKardum/Startkit-Symfony.git
cd Startkit-Symfony
```

Run docker compose command
```
docker-compose up -d
```
Open docker container
```
docker exec -it -u root project_php bash
```
Go to web directory
```
cd project
```
Composer command
```angular2html
composer install
```

### Go to...

* **Website** - ```http://localhost:8000```
* **API platform** - ```http://localhost:8000/api```
* **Phpmyadmin** - ```http://pma.localhost:8000```
* **Mailhog** - ```http://mailhog.localhost:8000```
* **Traefik Dashboard** - ```http://localhost:8080```

## Author
* **Josip Kardum**
