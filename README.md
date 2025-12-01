Since the node_modules is included in .gitignore, you should do below;

Pre-requisites:
Active NodeJS LTS (Long Term Support) version and associated supported NPM version. (See https://nodejs.org)
################### Need to execute in terminal ################### 
Execute these: 

npm install --global @ui5/cli

npm i -D @ui5/cli ui5 init

ui5 use OpenUI5 

ui5 add sap.ui.core sap.m themelib_sap_horizon
