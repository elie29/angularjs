# angular-formation
   url : https://openclassrooms.com/courses/developpez-vos-applications-web-avec-angularjs/installez-votre-environnement

## Commandes

    npm install -g bower : to install bower globally
    npm install -g yo : to install yo globally
    npm install -g generator-angular : to install angular generator globally as suggested by yeoman
    npm install -g generator-karma : to install karma generator globally
    npm install -g grunt-cli : to be able to run grunt on windows env

## Create app using yo

    `yo app`

## Bower && npm

>npm covers back-end dependencies while bower covers front-end dependencies

    npm init : create package.json file
    npm install karma karma-jasmine karma-phantomjs-launcher --save-dev : Install dependencies and save it in package.json in devDependencies
    bower.init : create bower.json file
    bower install jquery --save : Install jquery as dependency for the front end and save it in bower.json file in dependencies

## Build & development
    Run `npm install`
    Run `bower install`
    Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.
