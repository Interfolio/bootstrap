# Project Status (please read)
Due to [Angular](https://angular.io)'s continued adoption, our creation of [the Angular version of this library](https://ng-bootstrap.github.io), and the the project maintainers' moving on to other things, this project is considered feature-complete and is no longer being maintained.

We thank you for all your contributions over the years and hope you've enjoyed using this library as much as we've had developing and maintaining it.  It would not have been successful without them.

---

### UI Bootstrap - For Interfolio Devs
Here are the steps you need to take to modify this library:

1. Clone the Interfolio angular-ui-bootstrap repo
1. Install local packages `npm install`
1. Install grunt if you don't already have it `npm i -g grunt-cli`
1. CD into the MC directory of the FE you're working with
1. Remove the local angular-ui-bootstrap directory `rm -rf node_modules/angular-ui-bootstrap`
1. Create a symlink to your local angular-ui-bootstrap `ln -s ~/Interfolio/angular-ui-bootstrap node_modules/angular-ui-bootstrap`
1. Go back to the angular-ui-bootstrap repo, 
1. To compile JS you will need to run `grunt build`
1. To compile HTML you will need to run `grunt before-test build` and recompile your FE as templates get cached
1. To run the build once you are done making all your changes, just use the default task `grunt`. This will run all the UTs and all the build process.
1. You will need to create a tarball of the project before deploying it to GemFury.
