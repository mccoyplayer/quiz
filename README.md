<h1 align=center>Quiz Web App</h1>

<p align="center"> 
   <img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT License" /> 
   <a aria-label="last commit" href="https://github.com/adebola-io/quiz-app/commits/main"> 
      <img alt="" src="https://img.shields.io/github/last-commit/adebola-io/quiz-app.svg"> 
   </a>
   <a href="https://GitHub.com/adebola-io/quiz-app"><img src="https://img.shields.io/badge/contributors-7-ee8449"/></a>
   <a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PR(s)-welcome-brightgreen.svg?style=flat-square" alt="Make a pull request."></a>
 </p>

This is the repository for Group 3 of the CSC 420 Software Engineering project.

## Design 🖌

The design for this project is hosted on Figma [here](https://www.figma.com/file/AUoDWCLv80ZajCBgePszki/CSC-420---Project?type=design&node-id=0%3A1&mode=design&t=dHfWTuMj0kdoQkOx-1).

## Development 🖥

### Front-end 

The front-end is (to be) written using React and Tailwind. Node and NPM/Yarn must be installed to preview it. To run the frontend locally, cd into the `frontend/` folder and run

```shell
npm install
```

followed by

```shell
npm run dev
```

to start the local dev server.


### Back-end

A simple development back-end is present in the `/backend/mock/` folder. To run it, cd into the folder and run:

```
npm install
```

and then

```shell
npm start
```

to start the Node.js server.

To see the code for the main back-end, visit [here](https://github.com/Matec12/quiz-app-backend).


## Documentation 📜

Relevant documentation files can be viewed in the [`docs`](https://github.com/adebola-io/quiz-app/tree/main/docs) folder. 


## Deployment 🚀

All pushes to the `production` branch are automatically deployed on Vercel [here](http://csc420quiz.vercel.app).
