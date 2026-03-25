<h1>1. Install <i>NVM</i> with install script</h1>
in the terminal type:
<code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash </code>

<h1>2. Install node.js</h1>
<i>You will have to close then reopen the terminal to use nvm</i>

  <code>nvm install node</code>

  or

  <code>nvm install --lts</code>

  to install node.js lts


<h1>3. Create folder for the server.</h1>
  Download this repo, unzip it and name the folder somthing

  then go into the folder with:

  <code>cd FOLDERNAME</code>

  **# or change "FOLDERNAME" into the folder name where the unzipped contents are**

 
  
  <h1>4. Initialize NPM </h1>
  <i>npm is included in the node.js package so you don't have to seperatly install it</i>

  <code>npm init -y</code>

  <i>-y applies default settings</i>

  This will create the package.json and initallize NPM (node package manager)

  <h1>5. Install fastify with npm</h1>

  <code>npm install fastify</code>

<h1>6. Generate https keys</h1>

run the script genKeys.sh with

<code>bash ./genKeys.sh</code>

<h1>7. Start the server</h1>

run start.sh with

<code>bash ./start.sh</code>
