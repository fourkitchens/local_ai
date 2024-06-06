# Local AI Builder + Drupal
Install Drupal,Lando, MongoDB Atlas, and the things you need to start working on AI locally.

## At A Glance
|   |                                                     |
|---|-----------------------------------------------------|
| Local Environment | <a href='https://github.com/lando/lando/'>Lando</a> |
| PHP | 8.3                                                 |
| Core Distribution | Drupal (10)                                         |

## Dependencies and Requirements

* [Lando](https://docs.devwithlando.io/)
* [NVM](https://github.com/nvm-sh/nvm)
* [NodeJS v20+ LTS](https://nodejs.org/en/)
* [Drush 12+](https://github.com/drush-ops/drush)
* [Mongo Atlas](https://account.mongodb.com/account/login)

## Installation

1. Clone this repository.
2. Run `lando start` to start the Lando environment.
3. Run `lando atlas atlas auth login` to authenticate with MongoDB Atlas.
4. Run `lando atlas deployments setup` to create a new deployment locally of atlas.
5. Run `composer install --ignore-platform-reqs` to install everything even without mongodb installed on your local machine.
