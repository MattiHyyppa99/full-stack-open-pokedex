# Exercise 11.1

- The application is an API which is built with Python. Linting the codebase can be done with Pylint. Pylint can detect both errors and it enforces a coding standard. Testing could be done with pytest, for example. Python is an interpreted language so there is no need for a build step. However, if we used some additional technologies, such as Docker, there would need to be a build step for creating the Docker image of the application.
- CircleCI and Travis CI. If the codebase were stored on GitLab, we could also use GitLab's CI tools.
- Because linting, testing and building are very common CI steps, a cloud-based environment would work just fine. Especially if the company is small, a cloud-based environment would be a good starting point.
