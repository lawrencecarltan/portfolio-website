+++
date = '2024-04-26T18:22:42+11:00'
draft = false
title = 'Bridging the Context Gap Between Teams Through Site Reliability Engineering'
thumbnail= "images/sre-context-gaps.webp"
+++

With the rise of more composable architectures such as microservices in modern software, application components are becoming smaller and more independent than ever before. Unsurprisingly, this shift aligns with the growing need for scalable, flexible, and agile solutions to meet the increasing complexity of today’s fast-paced digital landscape.

An inadvertent drawback however, is that as services become more composable, organizational teams have naturally reflected this structure as well. In a way, this is simply [Conway’s Law](https://www.atlassian.com/blog/teamwork/what-is-conways-law-acmi) in action.

As such, gaps that start to form not only between teams but within the multiple roles within it are often overlooked. This disconnect, often referred to as “context gap”, arises from the different priorities, tools and even language between different teams and roles within teams.

Site Reliability Engineering (SRE) emerges as a powerful methodology to bridge this gap, fostering collaboration which ultimately enhances system reliability and quality. This article further delves into the reasons for context gaps, how it impacts organizations and how SRE principles can be an effective mitigation against these challenges.

## Understanding Context Gaps and Its Impact
The first type of context gap is one that exists between teams owning different microservices that compose an application. The challenge is that most often, teams simply end up looking after their own microservice with no further context as to how they play a part in the bigger picture.

The second type of context gap is more challenging as it is one that exists between the different roles within a team. Categorically speaking, there are 3 main roles in software delivery teams — Product Management, Product Development and Product Operations.

Context gaps within these roles exist simply because of the nature of what each role prioritizes:

- **Product Management** wants to introduce new features that customers ask for
- **Product Development** wants to develop the new features defined by Product Management and deliver it as quickly as possible
- **Product Operations** wants to keep availability of the application and hence naturally wants to keep changes to a minimum (especially if changes have historically caused outages)

These distinct priorities result in misalignment, conflicts which subsequently lead to a product that is **not delivered with agility, not reliable, and not relied on by its customers.** Unmistakably, this means that each of the goals of each role mentioned above are not sufficiently met.

The reality is, operational stability and reliability is every role’s job zero. If an application is operationally unavailable:

- The new features that Product Management pushes for won’t be available
- The features delivered quickly by Developers won’t be used
- Operations will be working day and night

## Bridging the Gap with Site Reliability Engineering

Site Reliability Engineering offers a holistic approach to address not only the challenges posed by context gaps but the reasons they exist in the first place. It emphasizes the collaboration between Product Management, Development, and Operations Teams by establishing shared goals and tooling to amplify system reliability, scalability, and performance. Here’s how SRE principles help bridge context gaps:

- **Shared Objectives:** SRE encourages Dev and Ops teams to align around common objectives, such as service uptime, latency targets, and error rates. By establishing Service Level Objectives (SLOs) and Service Level Indicators (SLIs), teams gain a shared understanding of system behaviour and performance expectations.
- **Automation and Tooling:** Automation plays a pivotal role in SRE practices, enabling teams to streamline repetitive tasks, reduce manual errors, and enhance operational efficiency. By investing in robust monitoring, deployment, and incident response tooling, organizations empower both Dev and Ops teams to collaborate effectively while maintaining system reliability.
- **Blameless Culture:** SRE promotes a blameless culture where failures are treated as learning opportunities rather than occasions for assigning blame. By fostering an environment of psychological safety, teams are more inclined to share knowledge, collaborate on solutions, and proactively address issues without fear of repercussion.
- **Continuous Improvement:** SRE embraces the principles of continuous improvement and iteration. Through practices like blameless postmortems and retrospectives, teams reflect on past incidents, identify areas for improvement, and iteratively enhance system resilience and reliability.
- **Cross-Functional Collaboration:** SRE encourages cross-functional collaboration through practices like shared on-call rotations and incident response exercises. By breaking down silos and fostering empathy between Dev and Ops teams, organizations can leverage diverse perspectives to tackle complex challenges more effectively.

Context gaps between development and operations teams present significant challenges for organizations striving to deliver reliable services. However, by embracing key SRE principles, we can start bridging these gaps by fostering collaboration, enhancing system reliability and ultimately deliver greater value to users. By prioritizing shared objectives, engineering mindset, blameless culture, continuous improvement, and cross-functional collaboration, organizations can embark on a journey towards a more reliable and resilient digital future.
