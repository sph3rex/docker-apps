### Some dockerized applications. List includes at the moment:
- aws-cli
- aws-logs
- jq
- json2yaml
- yaml2json
- serverless

Please note that some of the images use the `config` folder for getting their environment namely the aws credentials at the moment. Please do not use quotes around values of the aws credentials.

If you want to use them without using the docker run you can source the aliases file. Should be compatible(partially tested) with both zsh and bash.

#### Exposed aliases:
- slsd which is an alias of docker-serverless
- jqd which is an alias of docker-jq
- json2yamld which is an alias of docker-json2yaml
- noded which is an alias of docker-nodejs
- npmd which is an alias of docker-npm
- awslogsd which is an alias of docker-aws-logs

#### TODO: 
Add project urls for all of the dockerized apps