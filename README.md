# ESLINT-config-file

To use this feature first install eslint using node package manager (npm).
command : npm i -g eslint 
-g is used to install it globally on the local system.

Now everytime in order to use eslint in the react project being built use the following command,
command: eslint --init
Select the option that says "To check syntax, problems and code styles"
For the format of the config file select JavaScript

After this an .eslintrc.js configuration file will be generated.
Copy and paste the contents of the file in the repository under the same name for the "rules" of the file as they are an essential part.

After this hold cmd+shift+P, in the VS code window and that will open up the command palette, now type " open Settings(JSON) " and open it.

Now add the lines from the settings.json file in your file. This will allow auto correct upon saving.

