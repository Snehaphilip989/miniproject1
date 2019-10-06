## How the usage of Git, Docker, Automated Testing, and Continuous Integration can improve the productivity and competitiveness of a company ?
Software is a key competitive differentiator for companies across industries. The faster companies can get new enhancements and functionality to market, the wider their competitive edge.To achieve such development teams adopt continuous integration to speed up and automate the software delivery lifecycle. CI, a DevOps process that is integral to continuous delivery. Continuously integrating code improves processes in a way that benefits both IT teams and their business counterparts.

CI continuously processes, tests, and uploads changes or additions made to a code base. The code is saved in a source control management system that is accessible to all developers for testing and reference. Any developer working on the application has access to the most current code. Each integration is verified by an automated build (including test) to detect integration errors as quickly as possible. Many teams find that this approach leads to significantly reduced integration problems and allows a team to develop cohesive software more rapidly.Three major impacts it has done to improve the productivity and competitiveness for the companies are reducing the errors and manual tasks, identified and resolved integration challenges early and shorten the delivery life-cycle.

## Following are the elements for the continuous Integration/Continuous delivery pipeline structure: 

Source Stage: Pipeline run is triggered by a source code repository. A change in code triggers a notification to the CI/CD tool, which runs the corresponding pipeline.

Build Stage: The source code and its dependencies to build a runnable instance of our product that we can potentially ship to our end users. Regardless of the language, cloud-native software is typically deployed with Docker, in which case this stage of the CI/CD pipeline builds the Docker containers.

Test Stage: We run automated tests to validate the correctness of our code and the behavior of our product.The test stage acts as a safety net that prevents easily reproducible bugs from reaching the end users.Depending on the size and complexity of the project, this phase can last from seconds to hours. Many large-scale projects run tests in multiple stages, starting with smoke tests that perform quick sanity checks to end-to-end integration tests that test the entire system from the user’s point of view.

## Aspects of using Git, Docker, Automated Testing, and Continuous Integration that provides companies a competitive edge :

### 1. Reliable, High Performance 
The continuous updates and test automation in CI helps ensure reliable, high-quality releases that have fewer errors and bugs that could reduce their effectiveness. For end users, that translates to enhancements that they can put to use more quickly to drive business growth.

### 2. Reduced Costs from Fewer Outages
CI reduces manual tasks and errors, which also reduces the risk of outages or downtime after release. For end users, that provides a higher level of service and increases productivity, especially when CI is extended to CD, where deployments occur automatically across test environments and into production. More importantly, it drastically reduces costs as businesses won’t have to spend time and resources resolving outages.

## SOURCE: 

### [ci/cd] https://dzone.com/articles/benefits-of-continuous-integration-for-businesses
### [ci/cd] https://semaphoreci.com/blog/cicd-pipeline
### [GIT] https://www.freecodecamp.org/news/what-is-git-and-how-to-use-it-c341b049ae61/
### [DOCKER] https://medium.com/uptime-99/the-benefits-of-using-docker-for-development-and-operations-2c5256ad89bc
