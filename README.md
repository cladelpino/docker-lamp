This branch has a reduced fork of a docker lamp stack https://github.com/jersonmartinez/docker-lamp

It will generate a persistent volume creating a database for each sql dump.

To start: 

./init.sh 

If you want to regenerate the volume reading the dumps again:

./init.sh --fresh
