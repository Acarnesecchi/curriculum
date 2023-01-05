# My curriculum Vitae hosted in FireBase

In order to easily deploy a static website on Firebase you have to start by:

* First of all create a FireBase project or import FireBase over a GCP project
* Install the Firebase CLI by running ```npm install -g firebase-tools``` in your terminal
* Initialize your Firebase project by running ```firebase init``` in the root directory of your project.
* Select a Firebase project 
* Choose the public directory that contains the static files (images, files, index.html, css and js in my case)
* Use ```firebase deploy``` to deploy your site
* If you want to deploy automatically the new changes added on github you have to first create a new service account from GitHub Actions and push the ```firebase-hosting-merge.yml``` and ```firebase-hosting-pull-request.yml``` files that firebase creates for you.


