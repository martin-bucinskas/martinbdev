---
title: Setting standards to be more confident in your production services
date: 2023-04-19 22:04:00
tags:
  - sdlc
  - standards

categories:
  - thoughts
---

# Intro

<p>In today's fast-paced and dynamic world, the importance of setting standards for production services cannot be overstated.
Without proper processes and standards in place, it can be challenging to maintain the quality and reliability of your services.
However, by implementing a structured software development life cycle (SDLC), defining playbooks, alerts, and standards,
you can greatly enhance your confidence in your production services.</p>

<p>This blog will explore the benefits of establishing these standards and provide insights into how you can develop them for your organization.
So, whether you're an experienced software developer or just starting, read on to discover
how setting standards can help you create a more dependable and robust production environment.</p>

## Pull Requests

<p>The easiest place to start is to start with the pull requests.</p>

<p>Defining prerequisites for pull requests (PRs) is a crucial aspect of setting standards for production services.
Here are some prerequisites that should be considered before a PR is raised:</p>

  - **Code review:** <p>Before submitting a PR, the code should be reviewed by at least one team member. This ensures that the code adheres to the team's standards and that any potential issues are identified and addressed before the code is merged.</p>

  - **Automated testing:** <p>The code should be tested using automated testing tools. This helps to catch any regressions that may have been introduced and ensures that the code behaves as expected.</p>

  - **Documentation:** <p>The PR should include documentation that explains the purpose of the code changes, any potential impacts, and how to use the new functionality.</p>

  - **Compliance:** <p>The code changes should adhere to any compliance requirements that are in place, such as security or regulatory standards.</p>

  - **Continuous Integration/Continuous Deployment (CI/CD) pipeline:** <p>The PR should be part of a CI/CD pipeline that automatically builds, tests, and deploys the code changes. This ensures that the changes are automatically integrated into the production environment without any manual intervention.</p>

<p>By defining these prerequisites for PRs, you can ensure that any code changes that are introduced to the production
environment are of high quality and adhere to the team's standards.
It also helps to reduce the risk of introducing errors or issues that could impact the stability and
reliability of the production environment.</p>