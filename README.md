<div>Learn CSS fundamentals through fun and challenging quizzes! :smiley:</div>

<hr />

### :rocket: How to run the app locally

In order to use this app locally, the package manager _yarn_ needs to be installed

If you don't have it installed yet, head over to:

:point_right: [https://yarnpkg.com/en/docs/install](https://yarnpkg.com/en/docs/install)

and install the latest yarn version for your system.

#### 1. Clone the repo

:horse_racing: Run this command to clone the repo, it shall install the app locally and change to its directory automatically:

`git clone https://github.com/fameweka/css-quiz.git fameweka-css-quizzes && cd $_`

#### 2. Install dependencies

First, before you can use the app, you have to run this command to install all the dependencies:

`yarn install`

#### 3. Start and view the app :eyes:

After you've installed all the dependencies, run this command to start the app:

`yarn start` :horse_racing:

Then, in your browser, open http://localhost:8000/ to view it! :tada: :tada:

### :construction: Contributing

I invite you to contribute to this repository! You can do so by opening an issue, or by directly contributing questions.

To directly contribute a quiz question, do the following:

1. Fork the repository :fork_and_knife:
2. In terminal run `yarn install`
3. For creating new question run `yarn new-question %your_question_name%`
   (Note `%your_question_name%` should be lowercased with words separated with dash `-`)
4. Open file `index.md` in directory `content/questions/%your_question_name%` and fill all fields.

If you have any questions, let me know!

### :clipboard: About the app

The app was bootstrapped using the `gatsby-starter-blog` template and then massaging it into a format conducive to quizzing.

### css-quiz

Up to the challenge? Take the quiz? Enjoyed the quiz? Contribute to the questions

### Deployment

Run below command to deploy to gh-pages.

```bash
npm run deploy
```
