# clevertools

cleverbuild (a) builds something new and (b) tags repo

cleverdeploy deploys something already built (an existing tag)

# Examples

cleverpet-behaviorlayer..
cleverbuild might build a .bin file;
cleverdeploy might deploy that .bin file to the particle dashboard

cleverpet-cloud..
cleverbuild might do nothing (or run unit tests);
cleverdeploy might run appcfg.py update

cleverpet-new-android-app..
cleverbuild might build a .apk file;
cleverdeploy might upload the .apk file to play store as "alpha";
cleverdeploy might promote apk from alpha to beta or from beta to production

= Tips

.cleverbuild scripts should be "fail fast", e.g., use #!/bin/sh -e
