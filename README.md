USAGE

1. Clone docker laravel inside your project
2. Open nginx/sites/laravel.conf edit your domain
    server_name [DOMAIN];
    root /var/www/laravel/public;
3. Add file host: 127.0.0.1 [DOMAIN]
4. Go to [PROJECT_FOLDER]/docker
5. Run command: docker-compose -d up nginx mysql