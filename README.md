# badminton_salad_tournament
A web application enabaling to manage your own friendly badminton tournament
The mock-ups of the application can be found under the *design* folder.
The application itself is under *badminton-salad-tournament-app* folder.

# Install the app

You need node.js with the latest version installed.
It can be found here : https://nodejs.org/en/download/ 
You just need to follow the instructions. 

Once it is install, open a command line and you need to upgrade your npm to the latest version by copy/pasting this: 

```
npm install -g npm@latest
```

Then you need to install Angular by copy/pasting this:

```
npm install -g @angular/cli
```

You will also need git to get the repository, so please download: https://gitforwindows.org/

Once it is installed, you will be able to clone the repository. 
Search for Git Bash in you computer and open it:

```
cd path_where_you_want_to_put_the_repository
git clone https://github.com/shtheo/badminton_salad_tournament.git
```

Then install the dependencies. Search for node.js command prompt and execute:

```
cd badminton-salad-tournament-app
npm install
```

Then you can run the server:

```
ng serve --open
```

If everything is ok, a web page should appear with the url : http://localhost:4200