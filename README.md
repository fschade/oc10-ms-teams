# OC-10 MS-Teams ENV

## Prepare
```shell
$ git clone https://github.com/fschade/oc10-ms-teams.git --recursive
$ cd oc10-ms-teams
```

## Openidconnect
* see - https://github.com/fschade/openidconnect/tree/ms-teams
* register and setup app - https://portal.azure.com/ 

## MS-TEAMS App
* see (TBD) - https://github.com/fschade/oc-ms-teams-app-generator

## Run
```shell
$ cp config/openid.config.php.dist config/openid.config.php
$ docker-compose up
```