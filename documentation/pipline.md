## Pipeline


CircleCI is a continuous integration tool. It allows for rapid deployment of code to production.

1- wrote my own code, commit and push it to git repo.

2- CircleCI will be triggered and will execute commands in .circleci/config.yml file
  - CircleCI pulls new changes
  - CircleCI setup the environment (node - aws - eb - browser extension)


3- CirCleCI will build, test and deploy to amazon beanstalk.
- CircleCI installs dependencies
- CircleCI vaildates if browser extenstion is installed
- CircleCI runs the unit testing
- CircleCI build both 2 projects api and front end
- CircleCI deploys the 2 projects


