## web-part-plus-app-customizer

This is where you include your WebPart documentation.

### Building the code

```bash
git clone the repo
npm i

## Description of Issue

This project was intialized with a single HelloWorld web part.

I then added an application customizer using yo.

I incremented the version number of the package and republished the solution.  The application customizer is present, the web parts are no longer present.

This is caused by the fact that web parts out of the box do not require a feature definition in pacakge-solution.json.  Adding the application customizer, adds a feature and caused the web parts to deploy.

As a user, you may try to add a separate feature for the web part but that will cause issues with previous version of the code being loaded when you do future deployments.  

See issue on sp-dev-docs project.

https://github.com/SharePoint/sp-dev-docs/issues/3199
