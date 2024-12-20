# Wordpress docker
Template to host dockerized Wordpress websites. This project is only the hosting part of the Wordpress site and by default no actual Wordpress files will be committed to source control.

## Setup (existing Wordpress project)

1. Add the wordpress files to the `./wordpress` folder. Do NOT override the `Dockerfile`
2. If needed, update the Wordpress image in the `./wordpress/Dockerfile`
3. Add the SQL dump file to `./dump.sql`
4. Create an `.env` file, for current parameters reference `.env.example`
5. Run `docker compose up -d` to start the website