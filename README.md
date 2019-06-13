# cjw_cv

### Description
The CV of Charles J Wilson in multiple formats, including web and pdf.

### Build
npm is used to comile scss into css.

Run `npm run release` to compile ready for release.
* Compiles the style.css from the style.scss files
* Copies all static content into the `build/` directory
* Generates a PDF based off of the static website content using a headless JS browser

Run `npm run build` to compile CSS without regenerating cv.pdf

Run `npm run watch-css` to dev on scss and compile on change the scss 

### Deployment
This project is currently hosted on github as a public repository. It is deployed to AWS as a static website hosted on S3 using AWS Codedeploy pipeline.