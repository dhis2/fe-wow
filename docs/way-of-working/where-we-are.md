---
title: Where we are now?
sidebar_position: 5
---

## Where we are now

### high-level view

In Platform Frontend, we are a team of ~6 developers responsible for over 20 apps and libraries.

The main lifecycle is the major release cycle. This used to be six months (two major releases per year), but it changed to one yearly release. Other than the major release, we have regular patches for the versions we support (last 3 versions).

We get high-level requirements from **the roadmap** that translate into projects that are delivered during the lifecycle. The roadmap responsibility falls mainly with the functional design team, tech team leads, We also maintain existing projects, and libraries that are used through the DHIS2 ecosystem internally and externally.

### From dev's perspective

Most of our projects tend to become a one-man project ("man", since we're also very lacking in diversity). This is mainly due to lack of resources, but often due to people's preference and the type of projects where having more than one person wouldn't necessary make things quicker.

The main lifecycle while developing remains the major release. We've had attempts to break these long periods into shorter spans. We tried formal methods like sprints, but also informal methods like aligning with product demos and reviews.

This causes issues with estimation (it's harder to estimate big projects) and visibility (it's hard to know what state projects are in). But it also works - we _generally_ deliver on our release commitments but with a cost.

The cost to quality is in the shape of:

- Lack of tests: we often end up sacrificing tests in order to deliver on these commitments
- Lack of knowledge sharing: people working on silos tend to become experts with certain apps or parts of the system, while others don't.
- Technical debt: taking shorcuts leads to technical debt that we don't get to tackle.

**Process-wise**, we use Jira for tickets. We have an ongoing board that is kanban-ish. We tried some sort of sprints but that didn't work mainly because work kept being in big chunks that span multiple sprints.

### cross-functional collaboration

**UX**: UX (aka Joe) tend to be involved in larger projects. They communicate wireframes and specs that guide our development work.

**Testing**: From a dev's perspective, testers tend to get involved towards the end of the release cycle. Developers do testing for the PRs when they are ready, along the code review. 

**Functional design**: There is no direct interaction with functional design between devs and functional design team typically. But they tend to collaborate closely with the tech leads, and product managers, and their input is the main driver for the roadmap

**Security**: Devs, in frontend, also don't tend to have direct contact with the security team, but we often get tickets that are security-focused.

### Type of work

### Greenfield projects
**Big** like new Data Entry app, and Maintenance app - these should have more than a developer involved.

Or **mid-size** like the new Login App, the FE components for multi-calendar support, the PWA support in app-platform.

### Brownfield projects

Maintenance of existing apps. These vary in their age, and hence, the tech stack used and its quality.

### Platform development

We maintain a large set of tools and libraries that are part of the app-platform, the UI library for example.

About 15% of our time (a completely made up guesstimation, for now) goes into maintaining these tools, improving them, and handling new situations that arise that need 

### BAU - Business as Usual

Bugs and issues related to the previous releases.
