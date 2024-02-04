# React_Introduction
This repository is an introductory guideline on how to create a React Repository on a local machine.

1. Install VSCode
2. Create a project folder name "React_Introduction"
3. Install Node.js
4. Open a terminal in VSCode
5. Type "npm config get prefix" in the VSCode Terminal
6. Type "sudo chown -R $(whoami) $(npm config get prefix)/{lib/node_modules,bin,share}"
7. Enter Password for the local machine in the VSCode Terminal
8. Type "npx create-react-app myfirstapp" in the VSCode Terminal
9. Press/Enter 'y'
10. Type "cd myfirstapp"
11. Type "npm start"
# This will open a webpage with a React logo showing up
12. Update the original files App.js and Index.js in the folder "React_Introduction/src" to the new versions attached in this resipotory
13. Delete the unnecessary files in the "React_Introduction/src" folder by typing
    "rm src/App.css src/App.test.js  src/index.css src/logo.svg src/reportWebVitals.js  src/setupTests.js"
# The webpage should automatically update once the js files are saved
# if not, terminate the app by the command "CTrl+C" and type "npm start" again to restart the app
# The webpage should display a text message and an updating local time and date
