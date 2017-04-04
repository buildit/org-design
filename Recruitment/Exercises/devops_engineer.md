# DevOps Engineer - Technical Test
We think infrastructure is best represented as code, and provisioning of resources should be automated as much as possible.

Your task is to create a CI build pipeline that deploys a web application to a load-balanced
environment. You are free to complete the test in a local environment (using tools like Vagrant and
Docker) or use any CI service, provisioning tool and cloud environment you feel comfortable with.

For this test, you will need to deploy our [example application](https://github.com/buildit/devops-test-webapp).

* Your CI job(s) should:
  * Run the tests included with the application.
  * Deploy to a target environment when the job is successful.
* The target environment should consist of:
  * A load-balancer accessible via HTTP on port 80.
  * Two application servers ([example application](https://github.com/buildit/devops-test-webapp)) accessible via HTTP on port 3000.
* The load-balancer should use a round-robin strategy.
* The application server should return the response "Hi there! I'm being served from {hostname}!".

## Context
We are testing your ability to implement modern automated infrastructure, as well as general knowledge of system administration. In your solution you should emphasize readability, maintainability and DevOps methodologies.

## Submit your solution
Create a public Github repository and push your solution in it. Commit often - we would rather see a history of trial and error than a single monolithic push. When you're finished, send us the URL to the repository.

