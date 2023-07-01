# Text-Editor
Progressive Web Applications (PWA)

  ![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)

  https://opensource.org/licenses/Apache-2.0

  GitHub: https://github.com/EFP18/Text-Editor
  Deployed on Heroku:


  ## Table of Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Tests](#tests)
  * [Questions](#questions)


  ### Description
  This is a text editor that runs in the browser, but also offline. It is perfect for those who wish to access their notes anytime, anywhere, without worrying about not having service to retrieve them. It achieves this by using a few different technologies, such as offline functionality. 

  ### Installation
  To use the Text Editor, one need only follow the link that will direct them to the website. Alternatively, one can clone this repository on their local machine, type `npm i`, `npm build`, and `npm run dev` to get the repository running, and proceed by going to the following address: `localhost:3000. In that way, a fellow coder can also make updates and improvements to the website and the code, if they wish to. 

  ### Usage
  To give its users a platform where they can write notes, thoughts and more, where they will always be able to access them, even when they're not connected to the Internet. It uses the IndexedDB API which features various useful methods to store and retrieve data, quickly and easily.  

  ### License
  Apache License 2.0
  

  ### Tests
  Using the DevTools on Google Chrome. 

  ### Questions
  * GitHub: http://github.com/https://github.com/EFP18
  * Email: ester.p18@hotmail.com
  



You will deploy this full-stack application to Heroku using the [Heroku Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).


WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)




  * Bundled with webpack

  * Create a service worker with workbox that Caches static assets

  * The application should use babel in order to use async / await

  * Application must have a generated `manifest.json` using the `WebpackPwaManifest` plug-in

  * Can be installed as a Progressive Web Application

### Deployment: 32%

* Application deployed to Heroku at live URL with build scripts




You are required to submit the following for review:

* The URL of the deployed application

* The URL of the GitHub repository, with a unique name and a README describing the project


