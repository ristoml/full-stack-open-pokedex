Hypothetical situation where a team of six people are working on a project written in Java.

Linting the code: 
A popular and trusted linter for Java-language is Checkstyle. With Checkstyle the developers can define multiple rules which can either raise notifications, warning or errors. The rules may apply to naming conventions, number of function parameters, line lenghts and naming conventions, to name a few. By applying linting rules to the code you make it easier to read and understand (=coherent), making the development more efficient.

Testing the code:
JUnit is the most popular and well-known Java unit testing framework. It is widely used int test-driven development projects. Automated tests written with JUnit help to ensure the project remains bugfree and allow developers to focus on new features instead of manually testing every implemented new feature.

Building:
Maven by Apache is build automation tool popularly used in Java projects. Maven takes care of the proper method of building the project and also its dependencies. By using a tool like Maven to build your project and take care of its dependencies, you reduce the risk of "works on my machine" problem arising and yet again allow the team to focus on implementing new code and features instead of troubleshooting issues with existing code.

Jenkins and GitHub Actions alternatives:
CircleCI, Azure Pipelines, GitLab CI, Buildkite, Travis CI, Airflow...

Making the decision between self-hosted or cloud-based CI environment for the project:
In the case of conventional Java-project i.e. backend for a online store a cloud-based environment would most probably speed up the setting up of the CI. Other benefits are not having to worry about getting the hardware and setting up a local self-hosted server or having to deal with a situation where the hardware of your local server fails and you are left without working CI environment.
There might be some special cases where using a self-hosted environment could come beneficial, for it allows you to freely customize the computational power and resources among other things.

