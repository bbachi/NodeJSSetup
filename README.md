# NodeJSSetup

    
    This is the node js setup guide accross all platforms.

## Local/Windows 7

### Step 1: Install node.js
 
 #### Installation Overview
 
 installing node js on windows is pretty straightforward, just download windows installer and follow the prompts.
 
 #### Installation Steps
 
 1. Download windows installer from https://nodejs.org/en/. Install the version **v6.10.1 LTS** since the major version IBM AIX supports is this version.
 2. Run the installer (.msi) and follow the prompts as shown in the following figure.
 
 ![Install wizard](/nodeinstall.PNG)
 
 3. Restart the computer to run the Node.js.
 
 
 #### Test Node.js
  Please make sure you have both Node and NPM (node package manager) installed successfully by running following commands and run the simple test.
  
  1. **Node Test:** please open a command prompt and run this command `node -v`, this should print current verison you installed.
  2. **NPM Test:** NPM is the node package manager which installs all dependencies by reading through package.json at the root level of the project. please open a command prompt and run this command `npm -v`, this should print current verison you installed.
  3. Make sure set the environment variable to run node globally
  ![environemnt var](/nodeenv.png)
  
