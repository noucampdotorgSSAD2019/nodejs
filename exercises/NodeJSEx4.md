# Node.js Exercise 4 – npm Packages
		
> Complete ALL the exercises in this section.

## Fetch latest Repository Branch

```
$ cd /DRIVE/xampp/htdocs/nodejs
$ git pull --no-edit https://github.com/noucampdotorgSSAD2019/nodejs.git latest
$ git status

```

1.	In ``htdocs/nodejs`` create a new project folder called ``myUC``

1.	Create a ``package.json`` file for the new project using ``npm init`` command

1.	Add the *npm* package ``uppercase`` to the project

1.	View the ``packages.json`` file to ensure there are dependencies for the package just installed

1.  Create a ``index.js`` file in the ``myUC`` folder with this code:

    ```javascript
    // index.js
    var uc = require('upper-case');
 
    console.log(uc("hello, world"));
    ```

1.  Run the ``index.js`` file to test everything works.

1.  Push your code to your private repository on GitHub. Type these commands into your Git Bash client:

    ```
    $ cd /<DRIVE>/xampp/htdocs/nodejs
    $ git status
    $ git add .
    $ git commit -m "Exercise 4 - DONE|PARTIAL|HELP"
    $ git push origin master
    $ git status
    ```
