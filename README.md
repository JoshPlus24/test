# whitehough
Whitehough Wordpress site based on Bedrock and the _s theme. Uses lando for local development and webpack for asset bundling

## Prerequisites
* Lando (and docker)
* Yarn (and node)
* Composer

## Installation
1. Clone repository
2. Create .env file based on this guide - https://roots.io/guides/dockerize-local-bedrock-and-sage-development-with-lando/
3. Run 'composer install' in project root
4. Traverse to theme directory then run 'yarn install'
5. To start the server run 'lando start' in the project root

## Asset compilation
1. Traverse to theme directory then run 'yarn run dev' to start the file watcher