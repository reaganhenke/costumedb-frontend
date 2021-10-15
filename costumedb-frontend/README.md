# CostumeDB Frontend

This folder contains the frontend site for CostumeDB. Generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Deploy

The site is deployed with Github Pages and uses [Angular CLI GithubPages](https://www.npmjs.com/package/angular-cli-ghpages). To deploy, run `ng deploy --base-href=/costume-db/` from the frontend branch.

This will create an auto generated commit in the gh-pages branch and will be live automatically.

## TODO
- [x] read parameter on theme page
- [x] create text search results page
- [x] sanitize search
- [x] create shared service for text search and theme search
- [x] create a shared component for displaying costume results
- [x] add a link to fandom or wherever the image was sourced in costume tile
- [x] make share costume form
- [x] better mobile responsiveness - opening the menu should freeze scroll and cliking off it should close it. should reset whenever closed. 
- [x] prevent dropdown part of themes menu from staying open on scroll
- [x] update mock data to match model
- [x] loading icon
- [x] add loading for iframes
- [x] add "not found" illustration
- [x] add origin to costume tiles
- [x] add caching for theme results
- [x] flesh out text on homepage
- [x] set up deploy with github pages
- [x] buy domain
- [x] add name field
- [x] rename hair field

- [ ] add google analytics
- [ ] add privacy policy
- [ ] add terms of use
- [ ] fill out credits
- [ ] update themes to be correct
- [ ] source database images
- [ ] fix web manifest
- [ ] reduce scss size for group search and header