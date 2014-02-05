Getting satred with Grunt. 

• Install Node, buy clicking install: http://nodejs.org/
• (create a package.json file) In terminal, navigate to the project folder, and run 'touch package.json'
• Paste the following into package.json file
    {
      "name": "example-project",
      "version": "0.1.0",
      "devDependencies": {
        "grunt": "~0.4.1"
      }
    }

• (install node package manager) In Terminal run: 'npm install'
• (install Grunt via node package manager) In Terminal run: 'npm install -g grunt-cli'
• (customize files) Go into the Gruntfile.js and update file path accordingly to you images directory / scss & css / files to watch etc...

• (start up grunt & watch) In Terminal run: 'grunt'
• (start up grunt server - not necessary, but nice to have if you're using typekit) In Terminal run: "grunt connect". In your browser go to http://localhost:3000

All installed packages can be seen in the package.json file, and installation customizations are taken care of in the Gruntfile.js. Search for other packages and instillations here: https://npmjs.org/


