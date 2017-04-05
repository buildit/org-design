# DevOps Engineer - Technical Test
We think infrastructure is best represented as code, and provisioning of resources should be automated as much as possible.

Your task is to create a clustered web environment. You are free to complete the test using:

* A local development environment, using tools like Vagrant and Docker.
* A cloud environment, using any provider and provisioning tools you feel comfortable with.

The target environment should consist of:

* A load-balancer accessible via HTTP on port 80.
* Two application servers accessible via HTTP on port 3000 - please use our provided [example application](https://github.com/buildit/devops-test-webapp).
* The load-balancer should use a round-robin strategy.
* The application server should return the response "Hi there! I'm being served from {hostname}!".

## Context
We are testing your ability to implement modern automated infrastructure, as well as general knowledge of system administration. In your solution you should emphasize readability, maintainability and DevOps methodologies.

## Bonus Point
Automate a build and delivery pipeline using the [example application](https://github.com/buildit/devops-test-webapp)

## Submit your solution
Create a public Github repository and push your solution in it. Commit often - we would rather see a history of trial and error than a single monolithic push. When you're finished, send us the URL to the repository.

