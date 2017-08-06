# docker-wordpress_development_cli

This repository realise on the following resource for build...
[dockerhub/jnollette/wordpress_development](https://hub.docker.com/r/jnollette/wordpress_development/)
[github/jnollette/docker-wordpress_development](https://github.com/jnollette/docker-wordpress_development)

This docker file also uses the Wordpress CLI file, which is a PHP *.phar executable - [wp-cli](http://wp-cli.org/).

Here is an example docker-compose file - (gist)[https://gist.github.com/jnollette/426221102fc577a0686a32f518664404].

To use, simply run: 
	docker-compose up -d;

	docker-compose run wordpress wp <command>;
	or
	docker-compose -f <yaml-file> run wordpress wp <command>;

Please feel free to fork and use for your own projects.
