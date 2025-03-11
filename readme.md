<a name="readme-top"></a>



<div align="center">
  
  <img src="./src/img/form.png" alt="logo" width="50" height="50" />
  <br/>

  <h3><b>Form Transport</b></h3>

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)


<!-- PROJECT DESCRIPTION -->

# 📖 [Form test ] <a name="about-project"></a>

  **[Linters]**  The "Formulario Linters" is a simple and interactive web page that demonstrates the effective use of HTML, CSS, and JavaScript to build user-friendly forms. This project gathers basic user information such as name, email, age, and other preferences, showcasing a clean layout and responsive design.

It emphasizes best practices in form design, validation, and styling, ensuring a seamless and intuitive user experience. Below is how you could present a brief descriptive introduction for your project based on its functionality.
 

### Tech Stack <a name="tech-stack"></a>

<li> HTML </li>
<li> CSS </li>
<li> Javascript </li>
<li> Webpack </li>
<li> Express </li>
<li> Babel </li>
<li> Git </li>
<li> Github actions </li>
<li> Bash Script </li>
<!-- Features -->

### Key Features <a name="key-features"></a>

- **[HTML & CSS Best practices]**
- **[Responsive Design]**
- **[USER LIKES]**
- **[USER COMMENTS]**
- **[USER RESERVATIONS]**
- **[Webpack Bundling ]**
- **[Express Server to handle routing]**
- **[Bash Script to automate deployment]**


### Series List:
Formulario Linters is a simple web page that collects basic user information through an interactive form. It allows users to input data like their name, email, age, and preferences.

Users can select options from dropdown menus, check boxes, and leave comments. This project is a straightforward yet effective example of creating responsive and functional web forms.

### Likes:
 Users can express their preferences and indicate their favorite series by utilizing the "Like" feature. This functionality is achieved through REST methods, enabling users to interact with the app and curate their personal collection of liked shows. By utilizing async/await and Promises, the app ensures smooth and responsive liking functionality.

### Comments Popup: 
The app allows users to input data, such as name, email, and age, while selecting preferences through dropdown menus and checkboxes. JavaScript handles validatio

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->

### 🚀 Live Demo <a name="live-demo"></a>

> 

- [Live Demo Link](	
forwebpack-eydvcqacbxe9bjer.brazilsouth-01.azurewebsites.net
)



<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites
To run this project  you need the following tools:
- [VS Code ]
- [Git and GitHub ]
- [Nodejs ]
- [Express ]
- [Bash Script ]
- [openssl to generate self signed certificates ]
- [Webpack Installation ]
- [CI CD Netlify Bot  Instalation]
- [Nodejs ]



### Setup

Clone this repository to your desired folder:
```sh
 cd FOR5MULARIO-LINTERS
 git clone 
git@github.com
:https://github.com/Julay-alb/formlintersJS.git
```


### Install

Install this project with:

Lighthouse run
```sh
    npm install -g @lhci/cli@0.7.x
```
Webhint:
```sh
     npm install --save-dev hint@7.x
```
Stylelint:
```sh
     npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```

Eslint
```sh
     npm install --save-dev eslint@7.x eslint-config-airbnb-base@14.x eslint-plugin-import@2.x babel-eslint@10.x
```
Webpack
```sh
     npm init -y
     npm install webpack webpack-cli --save-dev
```

Webpack Css loader
```sh
     npm install --save-dev style-loader css-loader
```
Webpack html loader
```sh
     npm install --save-dev html-loader
```

Webpack html plugin
```sh
     npm install --save-dev html-webpack-plugin
```

Webpack dev server
```sh
     npm install --save-dev webpack-dev-server
```
Babel Dependency loader
```sh
     npm install --save-dev babel-loader
```
Minify CSS: To reduce the size of your CSS file by removing unnecessary characters such as whitespace and comments. 
```sh
     npm install --save-dev css-minimizer-webpack-plugin
```
Split Js : If your JS file is large, splitting it into smaller modular files can help improve the loading time. 
```sh
     npm install --save-dev terser-webpack-plugin
```

Split CSS: If your CSS file is large, splitting it into smaller modular files can help improve the loading time. 
```sh
     npm install mini-css-extract-plugin --save-dev
```
Babel core
```sh
     npm install --save-dev @babel/core @babel/preset-env
```
Express and body-parser
```sh
     npm install --save express body-parser
```

Concurrent, the npm package for running multiple commands in parallel
```sh
     npm install --save-dev concurrently
```


### Usage

To run locally run the following command:
## Development mode
```sh
    npm run build-dev
    npm run devserver-reload    
```
## Production mode
```sh
    npm run build-prod
    npm run server-prod
```


### Run tests

To run tests, run the following command:


To test the Stylelint linter:
```sh
    npx stylelint "**/*.{css,scss}"
```
To test the Webhint:
```sh
    npx hint .
```
To test the ESLint linter:
```sh
    npx eslint .
```


### Deployment

### Cloud Production deployment:
In root folder run the following command:
```sh
    bash 
deployment.sh
 -u username -i ipaddress -d Namefolder -e environment
```
The arguments are:
- -u username
- -i ipaddress
- -d Namefolder
- -e environment (prod or dev) respectively

With the last script, the app will be deployed to any cloud provider you want to use,  you only need the IP address and the right permission to access it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

JULIAN ALBARRACIN


👤 **Author1**

- GitHub: [@Julay-alb](
https://github.com/Julay-alb
)
- LinkedIn: [LinkedIn](
www.linkedin.com/in/julián-albarracin-bb7952183
)




<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>


- [ ] **[Personalized Recommendations]**
- [ ] **[Advanced Search Filters]**
- [ ] **[Notifications and Reminders]**


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](
https://github.com/Julay-alb/formlintersJS.git
).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

> Write a message to encourage readers to support your project

If you like this project please give  one start.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank  God for giving me the strength to carry out this project.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ (optional) -->



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](
LICENSE.md
) licensed.



<p align="right">(<a href="#readme-top">back to top</a>)</p> 