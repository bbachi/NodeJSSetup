# NodeJSSetup

    
    This is the node js setup guide accross all platforms.

## Local/Windows 7

### Step 1: Install node.js
 
 #### Installation Overview
 
 installing node js on windows is pretty straightforward, just download windows installer and follow the prompts.
 
 #### Installation Steps
 
 1. Download windows installer from https://nodejs.org/en/. Install the version **v6.10.1 LTS** since the major version IBM AIX supports is this version.
 2. Run the installer (.msi) and follow the prompts as shown in the following figure.
 
 ![Install wizard](/images/nodeinstall.PNG)
 
 3. Restart the computer to run the Node.js.
 
 
 #### Test Node.js
  Please make sure you have both Node and NPM (node package manager) installed successfully by running following commands and run the simple test.
  
  1. **Node Test:** please open a command prompt and run this command `node -v`, this should print current verison you installed.
  
  2. **NPM Test:** NPM is the node package manager which installs all dependencies by reading through package.json at the root level of the project. please open a command prompt and run this command `npm -v`, this should print current verison you installed.
  
  3. Make sure set the environment variable to run node globally.
  
  ![environemnt var](/images/nodeenv.png)
  4. take this file `testnode.js` and run it in command prompt `node testnode.js`. Please take a look at the image below.
  
   ![Node Test](/images/testnode.png)
   
   
   ## IBM AIX Setup
   
   ### Step1: Install Node.js
   
   #### Installation Overview
   
   installing node js requires IBM SDK for node.js provided by IBM Developer works. f your application requires any third-party Node.js modules, ensure that they are installed correctly.Check that the system PATH variable includes the directory location of the IBM SDK for Node.js executable program. If the PATH variable does not contain the installation directory, your system cannot find the executable program, and your application cannot run.
   
   #### Installation Steps
    
  1. Download IBM SDK for Node.js, Version 6 from this url https://developer.ibm.com/node/sdk/v6/ and select the AIX on Power Systems          64-bit and click on i agree link on the next page will download ibm-6.10.0.0-node-v6.10.0-aix-ppc64.bin. please follow the images below.
  
  2. it can be downloaded directly from this root folder of this project.
  https://github.com/bbachi/NodeJSSetup/blob/master/ibm-6.10.0.0-node-v6.10.0-aix-ppc64.bin
  
  ![select aix](/images/downloadaix.png)
  
  ![a agree](/images/iagree.png)
  
  ![a agree](/images/downloadfolder.png)
  
  3. once downloaded, make a directory with the following command in unix shell.
  `mkdir /apps01/nodeJS/nodeAIX-6.10.0.0`
