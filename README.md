# autoversion
Example code used to automate version updates using Bitbucket Pipelines. Sample of CI used in www.contractclub.ca. Go to https://bitbucket.org/Scfast/pipelines-autoversion to test out this set-up.

### What is this repository for? ###

* A quick example of how to use pipelines to automate version upgrades
* updates the patch version in package.json file
* automatically tags the commit with the updated version number
* Version - 0.0.n where n is determined by how many times pipelines is run

### How do I get set up? ###

* clone/copy this repo into your own repository
* clone/copy the docker image: https://hub.docker.com/r/shanepaper/autoversion/
* In bitbucket - go to settings > Environment Variables and set the variables to match your own credentials

### Who do I talk to? ###

* Shane Fast
* email: shane@get-paper.com
* twitter: @shanecfast
* see https://medium.com/@shanecfast/automate-versioning-using-bitbucket-pipelines-nodejs-220d2a4c3168 for additional info