# webpack-practice02

This is a practice project in order to get used to setting up webpack in anticipation of learning React. The issue for the problem encountered in webpack-practice01 was found in stack over-flow at: https://stackoverflow.com/questions/35810172/webpack-is-not-recognized-as-a-internal-or-external-command-operable-program-or

The solution used on that page was: As an alternative, if you have Webpack installed locally, you can explicitly specify where Command Prompt should look to find it, like so:

node_modules\.bin\webpack

(This does assume that you're inside the directory with your package.json and that you've already run npm install webpack).
