# Repository of camel-templates

## CEQ-YAML-REST-APP

Camel on Quarkus REST template for fast prototyping using YAML DSL to define the Camel routes and the REST endpoints and configuration.
The file directory contains two folders: 
    - Camel: this folder is to store the definitves YAML DSL files. There is a YAML DSL example. You can remove the example file.
    - Camel-prototype: this folder is to store YAML DSL files meanwhile you are prototyping. You can run these DSLs through JBang (previously installed in your local environment) and the deploy.sh command (chmod 777 deploy.sh to allow execute). 
### Run template

There are in the root two files depending on the environment you deploy: 
      - deploy_local.sh
      - deploy_openshift.sh

### Test the example

localhost:8084/users


