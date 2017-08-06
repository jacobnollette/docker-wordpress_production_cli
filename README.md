# docker-wordpress_production_cli

This repository realise on the following resource for build...
[dockerhub/jnollette/wordpress_production](https://hub.docker.com/r/jnollette/wordpress_production)
[github/jnollette/docker-wordpress_production](https://github.com/jnollette/docker-wordpress_production)

This docker file also uses the Wordpress CLI file, which is a PHP *.phar executable - [wp-cli](http://wp-cli.org/).

Here is an example docker-compose file - (gist)[https://gist.github.com/jnollette/426221102fc577a0686a32f518664404].

To use, simply run: 
	docker-compose up -d;

	docker-compose run --rm wordpress wp <command>;
	or
	docker-compose -f <yaml-file> run --rm wordpress wp <command>;


This project was forked from this (tutorial)[https://medium.com/@tatemz/using-wp-cli-with-docker-21b0ab9fab79]
Please feel free to fork and use for your own projects. 
