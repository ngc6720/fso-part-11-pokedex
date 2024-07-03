# exercise 1

Let's assume the imaginary application is written in Python. In the case of using a CI pipeline, we would probably want to integrate linting, testing and building steps.
For the linting step, tools like Pylint or Ruff can help us check code formating and style. When it comes to testing we can use unittest or pytest for unit and integration tests. For end-to-end testing we can use the Playwright framework which also supports Python.
When we want to build the app, tools like Flask exist to help create the files needed for the built form of the application
To set up the CI, we can use Bitbucket, GitLab, Bamboo or Azure as alternatives to Jenkins and GitHub Actions.
As it is a small development team and the stack imagined is basic, it may be enough to use a cloud-based environment since we do not need very specific and custom features.
