# HackerNewsSearchClientHNAlgoliaAngularPaginator

https://slimlime.github.io/hacker-news-search-client-hn-algolia-angular-paginator/

A Hacker News (HN) search client in Angular using the [HN Search API powered by Algolia](https://hn.algolia.com/api).

Task: Query search API on user search input and display articles on the searched
topic in forward/back button-navigable pagination.

Oops was editing this earlier...
A web app that allows users to **search** for **articles** on a specific **topic** and display the results in a **paged** format that is **navigable** through forwards/back button. -- (Perhaps the `page` param exposed by the HN Algolia REST API could bypass the need for some extra service logic pagination here?)

* Constraints are up to interpretation :lion:

![search-client-prototype-wireframe-example](https://raw.githubusercontent.com/slimlime/hacker-news-search-client-hn-algolia-angular-paginator/master/src/assets/hn-search-proto-wireframe-example-sav.png)
*Mockup proto wireframe example given*
<!-- [comment]: [//]<> -- https://raw.githubusercontent.com/slimlime/hacker-news-search-client-hn-algolia-angular-paginator/111eea7050bbc9abb064895327cb408711887174/src/assets/hn-search-proto-wireframe-example-sav.png 
-->
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Deploy

Using `angular-cli-ghpages` for easy deployment to GitHub Pages in `Bash` terminal:
`npm install -g angular-cli-ghpages`

Make sure to set base-href for correct href resource links? e.g. `ng build --prod --base-href ./`?

`ng build --prod --base-href "https://slimlime.github.io/hacker-news-search-client-hn-algolia-angular-paginator/"`

Run angular-cli-ghpages with using the shorthand:

`ngh` -- Angular CLI 6 build outputs to a subfolder under `./dist`. 

Need to point --dir=dist/[PROJECTNAME]  -- found in `angular.json` 

e.g. `ngh --dir="dist/hn-search-client"`


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

-- `ng test --code-coverage`?  May also look into npm `karma-typescript`
## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
