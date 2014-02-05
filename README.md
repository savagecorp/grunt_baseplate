Getting Started with Grunt. 
==========================

1. Install Node, by clicking install [on the Node website](http://nodejs.org/ ) 
2. (create a package.json file) In terminal, navigate to the project folder, and run 'touch package.json'
3. Paste the following into package.json file  


```
  {  
    "name": "example-project",  
    "version": "0.1.0",  
    "devDependencies": {  
        "grunt": "~0.4.1"
    }  
  }
```
    
4. (install node package manager) In Terminal run: `npm install`
5. (install Grunt via node package manager) In Terminal run `npm install -g grunt-cli`
6. (customize files) Go into the Gruntfile.js and update file path accordingly to you images directory / scss & css / files to watch etc...

7. (start up grunt & watch) In Terminal run: `grunt`
8. (start up grunt server - not necessary, but nice to have if you're using typekit) In Terminal run: `grunt connect`. In your browser go to http://localhost:3000

All installed packages can be seen in the package.json file, and installation customizations are taken care of in the Gruntfile.js. Search for other packages and installations
[through the Node Package Manager](https://npmjs.org/).  


