# CHESS-GAME
To download Node.js modules, you use npm (Node Package Manager), which is included when you install Node.js. Here's a step-by-step guide on how to do it:

Navigate to Your Project Directory: Open a terminal (Command Prompt, Git Bash, or any terminal you prefer), and go to the directory where your Node.js project is located.

bash
Copy code
cd path/to/your/project
Initialize Your Project (if you haven't already): If your project doesn't have a package.json file, you can initialize one by running:

bash
Copy code
npm init
Follow the prompts to set up your project.

Install a Specific Module: To install a specific Node.js module (e.g., Express), run:

bash
Copy code
npm install express
This will download the module and add it to the node_modules folder.

Install All Modules from package.json: If you already have a package.json file with dependencies listed, simply run:

bash
Copy code
npm install
This will install all the modules listed under the "dependencies" section in package.json.

Install a Module Globally (Optional): If you want to install a module globally (so it can be used across projects), use the -g flag:

bash
Copy code
npm install -g nodemon
Once installed, your modules will be located in the node_modules folder in your project
