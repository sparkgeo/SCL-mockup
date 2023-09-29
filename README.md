# This is an html mockup for the SCL site.

# NOT FOR PRODUCTION

## Dependencies for local development
- [live-server](https://www.npmjs.com/package/live-server) (NPM)
- [Sass](https://sass-lang.com)

##  Makefile 
To start it locally, run `go` in the `Makefile`, this will
- Start a live-server instance on an available port if 8080 is already in use
- live-server will watch for any changes to the file system and live-update the browser
- Sass will watch for changes in `/scss` and compile it to css in `/public/styles/css`
These process will run in the background.

## Deployment
Any changes pushed to the `main` branch will be deployed to github pages and available at 
https://sparkgeo.github.io/SCL-mockup/public


 