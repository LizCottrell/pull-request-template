# Pull Request Template
Use this template to make your life much easier on Github and Bitbucket. You can copy and paste this into your pull request comments or use an extension such as [Chrome Pull Request Templates](https://github.com/tcrammond/chrome-pullrequest-templates) to automatically apply your template

A PR template helps speed up the pull request flow for you by providing the reviewer a lot of extra information and saving yourself from having to remember what to include in the template. 

## Example Template 

#### What is this PR for?

This solves the issue of certain form fields not correctly validation

#### Where should the reviewer start?

1. Pull in the code and run `npm install`
1. Then run `npm run build` and finally `npm start`
1. Open your browser to http://localhost:8080

#### What should the reviewer look at?

1. Enter an email into the email field but leave out the @ symbol
1. Enter a phone number into the phone field but use a letter instead of a number (1-800-222-22r2)
1. Try to submit the form
1. Validating should now work correctly. 

#### How should this be manually tested?

1. Using the steps above should be enough for testing.

#### What are the relevant tickets?

TKT-180

#### Screenshots (if appropriate)
![Screenshot of the issue](https://upload.wikimedia.org/wikipedia/commons/5/57/Bootstrap-3.1.1-screenshot-jumbotron-example.png)

#### What gif best describes this PR or how it makes you feel?
![Makin bacon pancakes](https://media.giphy.com/media/Jr1dbQy33utOg/giphy.gif)

#### Additional comments:

Thanks for pointing out this bug, it was a tricky one but I was able to sort it out.

#### Definition of Done:
- [ ] Passes Automated Testing
- [ ] Passes Linting
- [ ] Documentation is up to date with any new changes
- [ ] Meets Project/Company/Personal coding standards

### Summary of Commits:
