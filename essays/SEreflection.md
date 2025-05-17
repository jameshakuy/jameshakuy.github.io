
---
layout: essay
type: essay
title: "Reflecting on Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2025-05-16
published: true
labels:
  - design patterns
  - software engineering principles
  - agile project development
---


Throughout this semester, we had the priviledge to learn Software Engineering principles alongside tools to practice these principles. We had WODs and take home WODs to solidify our understanding of these tools and our final project allowed us to practice S.E. principles. Such principles includes Agile Project Development, Configuration Management, Design Patterns, and more! As much as I would love to talk about how my team and I followed these standards to complete our project, I will first define these terms to get you on pace.

# What is Agile Project Development?
Agile Project Development is a methodology that focuses on collaboration, iterative development, and flexibility in response to change. To achieve these traits, projects are broken down into small manageable chunks in a continuous manner, improving using feedback. You can see this as an abstract class where there are many practices that derives from it. A specific approach we learned and practiced in class is called Issue Driven Project Management. While it follows core Agile principles, this approach focuses on small issues/tasks that are assigned to invidivual members which are assigned and resolved independently which ensures accountability and progress tracking.

# What is Design Patterns?
Design patterns are reusable solutions to common software design problems. They provide a structured approach to designing software that enhances code maintainability, scalability, and extensibility. Design patterns for software projects like MVC (Model, View, Controller) offers a structure (blueprint/schema) on how to approach projects. There are also design patterns in code such as components in React where code are encapsulated and are able to be reused across the whole project.

# What is Configuration Management?
Configuration management is the pracitce of managing software versions, configuration, and dependencies. It is important for all team members to work on the same version so code written are compatible. Note that not all code are compatible with different versions! For example, a python code written in 3.9 may not be compatible with say 3.6. Another example is the use of Git to manage code versions. If one team member is working on an old version and implements their changes, it may not work with the current version everyone else is working on.

# What is Coding Standards?
Coding standards are a set of guidelines developers follow to ensure that code is readable, maintainable, and consistent. These standards include naming conventions, indentation, commenting practices, and function design principles. However, there is not one set and stones standard. Coding standards can differ from institutions, coding languages, organizations, companies, etc. It's important that you follow the standards enforced at your workplace.

Phew! Now that all definitions are made clear, I can finally share how we used these methodologies to complete our project in ease! To begin with, our coding standards were mainly enforced by a linter—which automatically flagged styling and naming issues—so we never had to debate whitespace or comment rules in pull requests. We also commented our code thoughtfully, adding “why” explanations next to non-obvious logic to help teammates (and future selves) understand our decisions. Another tool we used is Git, the version control system at the heart of our configuration management practices: every feature branch, every bugfix, and every merge was tracked in commit history, ensuring that anyone could roll back or reproduce any state of the codebase. We also used npm to pin and install dependencies, making sure everyone ran the exact same library versions without manual coordination.

Now, throughout the duration of this project, we applied these principles in concert:

- Issue-Driven Agile
We treated each small task—whether “design login form,” “implement API endpoint,” or “write unit tests for cart logic” as its own issue in our sprint board. Assigning, estimating, and closing issues every few days kept us focused on incremental progress, and weekly stand-up updates helped us spot and resolve blockers before they stalled the whole team.

- Configuration Management in Practice
By committing our code to Git and using npm lockfiles, we avoided the dreaded “it works on my machine” problem. Whenever someone pulled the latest changes, they knew exactly which Node modules to install, and that their local environment matched production. This discipline would translate directly to any other domain—be it data science experiments (tracking package versions for reproducible models) or embedded software (managing firmware revisions and toolchain settings).

- Design Patterns for Clean Architecture
Although we built a web application, we organized our logic in an MVC-style structure separating data models, view components, and controller-like services and encapsulated UI pieces as reusable React components. This separation of concerns made our codebase easier to navigate, test, and extend. The same patterns could just as easily guide the architecture of a desktop app or a backend microservice, illustrating how these blueprints transcend any one technology stack.


# Conclusion
By combining issue-driven Agile, strict configuration management, and well-chosen design patterns, we delivered our project smoothly while learning skills that apply far beyond web development. These foundational practices will serve me equally well in mobile apps, machine learning pipelines, robotics software, or any other complex system I tackle next.
