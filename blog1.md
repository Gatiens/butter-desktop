Starting to work with Butter Project
====================================

Artifact 1. Installation Instructions on Linux (CS50)
--------------------------------------------------

### This was the given instructions

1. git clone https://github.com/Gatiens/butter-desktop.git
2. sudo npm install -g grunt-cli bower
3. npm start

sudo not listed as requirement but it was.
step 3 gave me errors

### Next steps tried

1. sudo ./make_butter.sh

sudo again not listed as required.
again i was given errors, by npm "sh: 1: node: not found"

### Next they have more granular installation instructions

1. npm install -g grunt-cli bower
2. npm install
3. grunt build
4. grunt start

step 2 gave me errors

### last steps listed for if i had troubles with previous steps

1. sudo npm install -g bower grunt-cli
2. cd desktop
3. npm install
4. bower install
5. grunt lang
6. grunt nwjs
7. grunt css
8. grunt start

step 1.sudo listed as required for first time
step 2. this gave me error because there is no package.json file on desktop. don't know why they asked to do this.

npm install again gave me errors "ENOENT, open '/home/ubuntu/Desktop/package.json'"

I believe npm did not like the older version of ubuntu that CS50 is running

### I know moved to windows

Artifact 2. Installation Instructions on Windows 10 64-bit
----------------------------------------------------------

### first installing a bash enivronment on windows
1. install https://git-scm.com/download/win
2. run Git-2.7.3-64-bit.exe

### run bash commands to install butter project
1. git clone https://github.com/Gatiens/butter-desktop.git
2. cd butter-desktop/
3. npm install -g grunt-cli bower
i already had jode.js on my machine. can be downloaded at https://nodejs.org/en/
4. npm start
this step took a very long time (45 minutes), npm threw out a lot of warnings, but completed without errors.


Artifact 3: Revisting CS50 to get butter-project to run (bonus)
---------------------------------------------------------------

After running npm install and looking at the errors, the version of node.js that is preinstalled on CS50 is to outdated for this project.
