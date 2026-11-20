# 🧠 Quiz App

A multiple-choice quiz web app with 4 topics: Web Dev, Programming, Sri Lanka and General Knowledge.

**Live demo:** https://amaya514.github.io/quiz-app/

## Features
- 4 topics with 6 questions each
- Questions and answers are shuffled every time
- 15-second timer for each question
- Shows the right answer after you pick
- Progress bar, final score and a message
- Remembers your best score for each topic (saved in the browser)

## Built with
HTML, CSS and plain JavaScript. No libraries.

## Add your own questions
Open `index.html` and add to the `QUIZZES` object:

```js
"My Topic": { icon: "⭐", questions: [
  { q: "Question?", a: ["Option 1", "Option 2", "Option 3", "Option 4"], c: 0 }, // c = index of the right answer
]},
```

## Run it locally
Download the repo and open `index.html` in any browser.
