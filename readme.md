# LEMP Stack docker-compose

A simple docker-compose setup for running a LEMP stack site. Made to resurrect a site from high school.

Just `docker-compose up` to start the site. Use `docker exec` on the db container to load the mysql file.

Security hasn't been done (nothing has been deployed to the web), so beware of the database configuration!

Content is served from `./www`.