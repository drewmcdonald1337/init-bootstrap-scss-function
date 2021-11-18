# Overview
This is an example repo that utilizes a SASS function that takes a map of colors to extend Bootstrap 5's theming and generates utility classes and shades for those colors.

## Using in your project
This repo is a simple example of the function in action, if you want to use the function I don't have a fancy way of doing that. Just copy the `sass/utilities/_init-bootstrap.scss` file and plop it in wherever your SASS files live, and import it into your app the way it's done in the example `styles.scss` file.

## Running Locally
* Install `npm` packages with `npm install`.
* Run `npm run watch-sass`.
* Open the `index.html` file in your browser. Sorry, no hot reload, this repo focuses on the Bootstrap SASS Theme Utility extensions so there's not a proper build pipeline.

## Contributing
If you like what this script does and you think it's not that pretty or you know of some way it could better integrate into projects (npm?), feel free to cut a branch and submit a PR!
