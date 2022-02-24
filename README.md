## Getting Started - resume template

This project is based on Tim Baker's resume template: https://github.com/tbakerx/react-resume-template.
Follow the instruction there and make your own CV.

## test and deployment

In the project directory, run

### `npm isntall`
first to install the dependencies.

### `npm start`

to start the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

Once you are satisfied with the local run,

### `npm run build`

to build the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `npm run deploy`

to run the build above then publish contents in ./build to github default `gh-pages` branch.


*this might be obsolete now though, as github pages now has an option to select hosting directory set to /doc.
Probably `npm run build` can save output to ./doc instead of ./build, and we can include this dir to push, and let github.io host the page out of the main branch.
