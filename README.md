# Factory+ Password Manager
This is a basic stack containing a `docker-compose.yml` file for installing a password manager as a stack on the AMRC Factory+ architecture.

## Installation
* Clone the directory
* Rename `env/mysql.env.example` to `env/mysql.env` and change the password
* Rename `env/passbolt.env.example` to `env/passbolt.env` and change the details
* Update the `docker-compose.yml` file for your architecture
* Run `docker stack deploy -c docker-compose.yml passbolt`
