#Artifactory Integration with Travis CI using Artifactory CLI

[![Build Status](https://travis-ci.org/Shahbrothers/travisci-generic-artifactory.svg?branch=master)](https://travis-ci.org/Shahbrothers/travisci-generic-artifactory)

`To make this integration work you will need to have running Artifactory-pro/Artifactory SAAS/Artifactory Enterprise which is acccessible form outside.`

##Steps to Integrate Travis CI with Artifactory.

Step 1:

copy `.travis.yml` file to your project.

Step 2:

Enable your project in TravisCI.

![screenshot](img/Screen_Shot1.png)

Step 3:

add Environment Variables ARTIFACTORY_URL, ARTIFACTORY_USERNAME and ARTIFACTORY_PASSWORD in build settings of CircleCI.

![screenshot](img/Screen_Shot2.png)

Step 5:

You should be able to see published artifacts in artifactory.

![screenshot](img/Screen_Shot3.png)

Step 6: 

Check build info in build section of Artifactory.

![screenshot](img/Screen_Shot4.png)
