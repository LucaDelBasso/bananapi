#!/bin/bash

export FLASK_APP="__init__.py"
echo $FLASK_APP
FLASK_ENV=
case $1 in
    -d | --dev )    FLASK_ENV="development"
                    echo $FLASK_ENV
                    export FLASK_ENV
                    flask run
                    ;;

    * )             echo "invalid" ;;
esac


