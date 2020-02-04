# Git/Github Classwork 1

In this classwork you will practice using Git/Github from the terminal along with the Google Chrome development console.

1. Change to the directory `~/CodeSchool`
1. Create a new subdirectory under `~/CodeSchool` called `scratch/git`
1. Change to the `~/CodeSchool/scratch/git` directory
1. Create a new local git repository
1. Create a new file called `index.html` using the `touch` command
1. Open `index.html` in Visual Studio Code and copy/paste code below (don't forget to save):

    ```
    <!DOCTYPE html>
    <html>
    <head>
      <title>Sample HTML/JavaScript</title>
    </head>
    <body>
        <script>
            let x = '2', y ='2';
            let msg_overkill = `I'd love ${x} try ${y} code something up for the platform`;
            console.log(msg_overkillit);
        </script>

        <h1>Top Header for a Sample HTML Page!</h1>
    </body>
    </html>
    ```

1. Stage the new file to your local git repository (hint: add)
1. Commit your changes to the git repository with the message `Initial checkin of index.html`
1. Login to your Github account and create a new remote repository called `scratch_remote_repo`
1. Back on your local machine, add your existing project files to your new Github remote repository
1. Push your `index.html` file to your new remote repository

1. Open `index.html` in the Chrome web browser
1. In Chrome, display the developer console 
1. Use the developer console to find the JavaScript error
1. Fix the error in Visual Studio Code (reload and test in the browser!)
1. Use the git command to check the status of changes
1. Use the git command to view the differences between your current `index.html` and the prior version
1. Stage the modified `index.html` to your local git repository
1. Commit your changes to the git repository with the message `Fixed variable reference in JavaScript`
1. Push your modified `index.html` file to your remote Github repository
1. Pull up your remote Github repository in the browser, verify the changes were committed
1. View the diff in Github and capture a print screen of the differences (hint: PrtSc)
1. Add the screen capture image to *this* git assignment repository
1. Commit and push the changes to *this* git assignment repository

