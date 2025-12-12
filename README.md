This is My First Repositry that i commited and my personal website that was given as task from hack club This is not responsive to phones and only works on computers and tablets

To build it
1. you need to set up the basic html structure
2. create some divs and then add basic p ans span tag and give classes and id's to them
3. then create css files and as many as pages you want and attach to the main file a
4. then style as you wish

will later be made responsive for phones also

To set up a local environment for a website that is built with HTML, CSS, and deployed via Vercel (and is hosted on GitHub), you will need to clone the repository to your local machine and possibly install some dependencies if you're using any build tools or frameworks. Below are the general steps to run this locally:

Step 1: Install Prerequisites

Before you begin, ensure you have the following installed on your local machine:

Git – to clone the repository.

Download Git
 and follow the installation steps.

Node.js and npm (if the project has Node.js dependencies, like bundlers, compilers, or local dev servers). If the project is just plain HTML/CSS without JS dependencies, you might not need this.

Download Node.js
 and follow the installation steps.

Step 2: Clone the GitHub Repository

You need to clone the repository where the website's code is stored.

Go to your project on GitHub.

Click the green Code button and copy the repository URL.

Open a terminal/command prompt on your computer.

Run the following command to clone the repository to your local machine:

git clone https://github.com/your-username/your-repository.git


Replace your-username/your-repository with the actual repository path.

Step 3: Navigate to the Project Directory

Once the repository is cloned, navigate to the project directory:

cd your-repository

Step 4: Check for Dependencies (if applicable)

If your project uses any dependencies, you'll usually find a package.json file in the root of the project. This means you might need to install those dependencies with npm (Node Package Manager) or yarn.

Check for package.json: If there’s a package.json file, run the following command to install the necessary dependencies:

npm install


or, if you're using Yarn:

yarn install

Step 5: Run the Local Development Server

If the project includes a local server (like for a framework such as React, Vue, etc.):

Check the documentation or package.json file for scripts (such as start or dev).

For instance, if the package.json has a start script, you can run:

npm start


or

yarn start


This will start a local development server. Typically, this would make the site accessible at http://localhost:3000 (or whatever port is specified).

If it’s just a static HTML/CSS website, you may not need a server. You can simply open the index.html file in your browser. If you want to live reload and test changes, you might use an extension or a tool like Live Server (VS Code extension) or http-server (npm package).

Live Server (VS Code Extension):

If you're using VS Code, you can install the Live Server extension.

Right-click on index.html and select Open with Live Server.

Using http-server:
If you want to quickly start a local static server with Node.js, you can install the http-server package globally:

npm install -g http-server


Then run the following to start the server:

http-server


This will start a local server on http://localhost:8080.

Step 6: Test the Site Locally

Once the server is running, open a browser and navigate to http://localhost:3000 (or whatever port your server is running on). You should be able to view the website as it appears locally.

Step 7: Sync Changes with GitHub

Once you make any changes to the website (e.g., modifying HTML, CSS, or JS), you can commit and push those changes to GitHub:

Add and commit the changes:

git add .
git commit -m "Your commit message"


Push changes to GitHub:

git push origin main


Replace main with the appropriate branch name if you're using a different branch.

