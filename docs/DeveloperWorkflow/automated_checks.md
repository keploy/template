# DeveloperWorkflow:

Automated Checks for pull requests
==================================

In order to maintain the code quality and coverage of our repositories,
keploy deploys a series of tools. These tools include our
Continuous Integration Setup that runs a complete test suite, Automated
Code quality checks as well as Coverage tracking tools.

This section focuses on how these automated tests are set up and how they can
be configured on our GitHub repositories. Currently only the
following checks are available in our `keploy`
repository.

Continuous Integration
----------------------

Keploy uses `GitHub Actions`_ for Continuous Integration. GitHub
Actions creates an environment based on the Operating System of your
choice and runs our test suite. This Continuous
Integration script is triggered by every pull request and only passes
when all the tests run successfully. 

<p align="center">
    <a href="https://github.com/keploy/template"><img src="https://github.com/Ayush7614/template/blob/main/docs/images/all%20checks.png" />
        </a>
</p>

-  GitHub pull request Checks

-  In the case where tests fail, we can debug the problem from going
   through the console output as displayed here.

<p align="center">
    <a href="https://github.com/keploy/template"><img src="check fails.png" />
        </a>
</p>
