<img src="banner.png"/>

## Backend Engineer - Coding challenge

This test is a part of our hiring process at Tailwarden for the Backend Engineer position. It should take you between 1 and 3 hours depending on your experience.

**Feel free to apply! Drop us a line with your LinkedIn/GitHub/Twitter and link of your code repository at [mohamed@tailwarden.com](mailto:mohamed@tailwarden.com)**

At Tailwarden, we use mainly Golang but you are free to use any modern language/framework you wish. Here are some technologies we are more familiar with: JavaScript, Python, Java, Ruby.

> Treat this project as if you/we would continue working on this after your assignment: maintainability, scalability, and readability are super important.

## Goal

For this assignment, you are supposed:
- Build a server that connects to an AWS account and exposes the following API endpoints:
  - Endpoint to list all AWS Lambda functions created in the AWS account across regions.
  - Endpoint to search for Lambda functions using the following query params:
    1. `runtime`: filter functions with a given runtime environment - [Read more about Lambda runtimes](https://docs.aws.amazon.com/lambda/latest/dg/lambda-runtimes.html)
    2. `tags`: filter functions with a given tag value or tag key - [Read more about tags on Lambda](https://docs.aws.amazon.com/lambda/latest/dg/configuration-tags.html).
    3. `region`: filter functions running in a given AWS region - [Read more about list of AWS regions where AWS Lambda is supported](https://docs.aws.amazon.com/general/latest/gr/lambda-service.html)
- Write a CI/CD pipeline (CircleCI, GitHub Actions, etc) to test, build and deloy the API.

When you’re done, host it somewhere (e.g. on AWS Lambda, Amazon EC2/EKS, Heroku, Google AppEngine, etc.)

### Submission

Create a new repo into your favorite git platform (GitHub, Gitlab, etc) with a README file containing list of instructions to run the project.

After you've finished, you can share the repository URL with us.

### Review

After you delivered the completed assignment to us, we will review it as soon as we can, generally within 48 hours. **We pay special attention to:**

- [ ] Coding skills.
- [ ] Code organization (modularity, dependencies between modules, naming, etc)
- [ ] Overall code quality (edge cases, usage of tools, performance, best practices)

### Good luck,
