# QA Engineer Test

Hello, and thank you for your interest in joining our team. We've outlined a few little exercises below to help assess your skillset.

## Getting Setup

To get started you'll need a few things setup if you haven't already:

- Node v7 or higher installed
  - **Note:** We'd prefer you work in Node.js but are open to other languages that play nicely with modern web-tech

## Functional + Visual Testing

### Instructions
To test your functional testing skills we'd like you to create a test to crawl each truck build in our Shop by Build section (https://builds.realtruck.com/) and ensure the following:
- That each build loads successfully
  - For example, you'd check that https://builds.realtruck.com/build/gray-f-150-on-pro-comp-lift returns with a status code 200 and that certain elements on the page are present such as the *mobile_breadcrums* class being present in the DOM, and so on for each and every build
- Whether or not the rendering of a build has changed from the last time the test was run
  - For example by using differential screenshot analysis

### What we're looking for
- Clean, logical, maintainable code
- We prefer you use differential screenshot analysis, how you implement it is up to you
- Some combination of [PhantomJS 2](https://github.com/ariya/phantomjs) or [SlimerJS](https://github.com/laurentj/slimerjs) and [Resemble.js](http://huddle.github.io/Resemble.js/), but we're open to any other more innovative / creative way of accomplishing the above

## Unit Testing

### Instructions
To test your experience with unit testing we'd like you to setup and configure a series of unit tests to check the script / code you created for the Functional + Visual Testing portion.

### What we're looking for
- Common sense unit tests that leverage a widely used unit testing framework of your choice (something like [Mocha](https://mochajs.org/) would be ideal)
- You can test as little or as much of your code as you like, we're looking to see what you choose to test and how so we want you to use your best judgement imagining this is a real-world scenario
