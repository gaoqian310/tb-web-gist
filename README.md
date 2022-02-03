# tb-web-gist

# Docker
Download and install Docker. Once installed, run it:
docker compose build

Once Docker is running:
docker compose up -d
-d will discount terminal/command propomt with docker, you can run docker up command without -d.

This will take some time the first time it runs. It builds the custom PHP image, as well as downloads the other ones needed for this to work (MariaDB/Redis/Mailcatcher).

You can take down the container with following command:
docker compose down

# PHP artisan
Open CLI from docker to bring up the terminal;
Type cd .. and enter;
Type pwd and enter. You should see /var/www;
Type php artisan and enter;
Type php artisan migrate:fresh;
Go to your web browser and type 127.0.0.1  -  you should see "Prototype Test Project"
Go to http://127.0.0.1/nova  - you should see login page
