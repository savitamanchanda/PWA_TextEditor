# PWA_TextEditor
A text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it also feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](${renderLicenseLink(license))

  ## Table of Contents
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contribution](#contribution)
  * [Tests](#tests)
  * [Questions](#questions)
  * [Credits](#credits)


  ## Description
  
I used a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla. 

  ## Installation 

N/A

  ## Usage 

Please visit at https://damp-taiga-91454.herokuapp.com/ and install the application to use.

  ## License 

  https://opensource.org/licenses/MIT

  To learn more about the mit license, click on the URL provided.

  ## Contributors

  N/A

  ## User Story 


```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

  ## Acceptance Criteria 

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

  ## Questions 

  For any questions, Please reach out at: 

  * GitHub: http://github.com/savitamanchanda
  * Email: manchandasavita3@gmail.com

  ## Links to the Deployed Application 

  * The URL of the deployed application - https://damp-taiga-91454.herokuapp.com/

  * The URL of the GitHub repository - https://github.com/savitamanchanda/PWA_TextEditor

  ![](./images/Screenshot%202023-04-03%20at%204.59.33%20PM.png)
  ![](./images/Screenshot%202023-04-03%20at%205.00.06%20PM.png)
  ![](./images/Screenshot%202023-04-03%20at%205.00.12%20PM.png)
  ![](./images/Screenshot%202023-04-03%20at%205.00.51%20PM.png)
