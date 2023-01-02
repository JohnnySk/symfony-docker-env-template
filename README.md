# symfony-docker-env-template

Usage

* clone current repository to the directory where you're planning to develop a local project with php8.2, mysql, nginx
* remove .git dir (rm -rf .git), because you will use custom repo for your project
* run next command in your project's dir: docker-compose up -d —build

That's it, your containers ready to install symfony inside php82-service container (via composer or symfony-cli) and build your app as you want.
