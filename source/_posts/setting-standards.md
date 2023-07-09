---
title: Setting standards to be more confident in your production services
date: 2023-04-19 22:04:00
tags:
  - sdlc
  - standards

categories:
  - thoughts
---

## Intro

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

## Setting clear acceptance criteria

<p>In addition to the prerequisites for pull requests, defining clear acceptance criteria is vital for ensuring the
quality and functionality of your production services. Acceptance criteria outline the specific conditions
that must be met for a feature or code change to be considered complete and ready for deployment.
Here's why setting clear acceptance criteria is beneficial:</p>

1. <p><b>Alignment with stakeholders:</b> Acceptance criteria serve as a communication tool between developers, project managers, and other stakeholders.
    By defining clear criteria, everyone involved has a shared understanding of what is expected from the code changes.
    This helps avoid misunderstandings and ensures that the final product meets the desired requirements.</p>
2. <p><b>Quality assurance:</b> Acceptance criteria act as a benchmark for quality assurance.
    They outline the expected behaviors and functionality of the code changes, making it easier to create comprehensive
    test cases and conduct thorough testing. Well-defined acceptance criteria ensure that all aspects of
    the feature or code change are thoroughly examined and validated.</p>
3. <p><b>Reduced ambiguity:</b> Clear acceptance criteria eliminate ambiguity and subjective interpretations.
    This allows developers to have a clear understanding of what needs to be implemented, reducing the risk of misalignment or wasted effort.
    It also enables testers to verify the functionality precisely, providing more accurate feedback on whether the acceptance criteria have been met.</p>
4. <p><b>Efficient development process:</b> With well-defined acceptance criteria,
    developers can focus on meeting specific objectives and requirements. By understanding the expected outcomes,
    they can streamline their development process, optimize their code, and avoid unnecessary iterations or rework.
    This leads to more efficient development cycles and faster delivery of features.</p>
5. <p><b>Customer satisfaction:</b> Ultimately, setting clear acceptance criteria contributes to customer satisfaction.
    When code changes meet the acceptance criteria, it indicates that the product aligns with the customers' expectations and needs.
    This helps build trust and confidence in the reliability of your production services, leading to higher customer satisfaction levels.</p>

<p>By establishing and adhering to clear acceptance criteria, you can ensure that the development team delivers high-quality
code changes that align with the project's objectives. It also provides a framework for evaluating the success of the implemented features,
enhancing the overall performance and reliability of your production services.</p>

## Communication

<p>Having clear and effective communication plays a vital role in ensuring the success of production services.
Whether it's discussing proposed changes or announcing existing changes going live.
Having a good communication strategy defined truly reflects the confidence in the production services.</p>

1. <p><b>Alignment and collaboration:</b> Clear communication allows teams to align their efforts and collaborate effectively.
    When proposing changes, developers can communicate their ideas, rationale, and potential impact to stakeholders, gathering valuable feedback and insights.
    This alignment ensures that everyone is on the same page regarding the changes being implemented and facilitates smoother collaboration across teams.</p>
2. <p><b>Transparency and visibility:</b> Communicating proposed and existing changes promotes transparency and provides visibility into the development process.
    By sharing information about upcoming features or code changes, you keep all stakeholders informed about the progress and expected timeline.
    This transparency helps manage expectations and reduces the likelihood of surprises or misunderstandings during deployments.</p>
3. <p><b>Risk mitigation:</b> Effective communication about proposed changes enables early identification and mitigation of potential risks.
    By involving relevant stakeholders in the discussion, you can gather diverse perspectives, uncover possible challenges, and address them proactively.
    This helps minimize the chances of disruptions or negative impacts on the production environment.</p>
4. <p><b>Coordination of dependencies:</b> In complex systems, different components or services may have dependencies on one another.
    Communicating about proposed changes and existing changes going live allows teams to coordinate and manage these dependencies effectively.
    This ensures that changes are implemented in the correct order, minimizing compatibility issues or unintended consequences.</p>
5. <p><b>Customer awareness and support:</b> Transparent communication about changes going live helps customers stay informed and prepared.
    By providing timely notifications, release notes, or changelogs, you empower customers to understand how the changes may affect their experience or workflows.
    This proactive approach builds trust, reduces support requests, and enables customers to adapt smoothly to the evolving production services.</p>

<p>Clear communication throughout the development and deployment process fosters collaboration, reduces risks,
and enhances customer satisfaction. By establishing effective channels for communication and sharing information
about proposed changes and existing changes going live, you can create a culture of transparency and accountability within your organization.
This culture, in turn, contributes to the overall confidence in your production services.</p>