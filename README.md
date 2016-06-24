# clevertools

cleverbuild: (a) trys to build something new and (b) if success then tags git repo

cleverscript: runs a script against an already existing git tag

# Examples

cleverpet-behaviorlayer..
1. cleverbuild might build a .bin file;
2. cleverscript might deploy that .bin file to the particle dashboard

cleverpet-cloud..
1. cleverbuild might do nothing (or run unit tests);
2. cleverscript might run appcfg.py update

cleverpet-new-android-app..
1. cleverbuild might build a .apk file;
2. cleverscript might upload the .apk file to play store as "alpha";
3. cleverscript might promote apk from alpha to beta or from beta to production

= Tips

clevertools scripts should be "fail fast", e.g., use #!/bin/sh -e
