# PUDL Infrastructure as Code


You can automatically install and configure PUDL tools with
[docker-compose](https://docs.docker.com/compose/).


## Installation

    $ git clone git@github.com:catalyst-cooperative/infrastructure.git
    $ git submodule init
    $ docker-compose build


## Usage  

Collect latest archives:

    $ docker-compose run scrapers

Details about how to upload zenodo archives:

    $ docker-compose run zen_storage --help # note that within docker,
                                            # --verbose is always enabled
