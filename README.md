<h1 align="center"> Engineering Principles</h1>

<p align="center"><img alt="epilot" src="./epilot-logo.svg" width="200"></p>

The following is a list of core principles [epilot](https://epilot.cloud/) engineers use to make decisions in their daily work building our software product.

<!-- toc -->

- [Freedom and responsibility](#freedom-and-responsibility)
- [Ownership: You build it, you run it](#ownership-you-build-it-you-run-it)
- [Solutions over problems](#solutions-over-problems)
- [API First: We design software with APIs](#api-first-we-design-software-with-apis)
- [Rent over build: We rent the necessary and focus on building the important](#rent-over-build-we-rent-the-necessary-and-focus-on-building-the-important)
- [Proof-of-concepts: Show, don’t tell](#proof-of-concepts-show-dont-tell)
- [Progress over perfection](#progress-over-perfection)

<!-- tocstop -->

## Freedom and Responsibility

We hire smart people who we can trust.

We operate by principles and expect our teams to cultivate a strategic mindset.

Teams and individuals are able to choose their own tools and go outside of what has been previously used in order to keep delivering product value. 

Teams are experts in their domains and own their decisions and the consequences of their decisions.

Experts provide support for decisions but do not act as gatekeepers.

### Why?

- **Speed**: Independency means speed, because teams can make their own decisions and don’t have to wait for centralized organs to approve everything they do.
- **Ownership**: Independency means ownership, because teams have to live with their decisions
- **Motivation**: Autonomy motivates, because teams are expected to find solutions for their challenges.

## Ownership: You build it, you run it

We subscribe to this core principle of the DevOps movement.

There is no dedicated Ops team who you can pass on the responsibility to take your code and make sure it runs reliably and scales to customers' needs.

Each team owns their deployment issues, performance bugs, capacity planning, monitoring, technical support; operating the pieces of software they build.

We expect teams to automate testing, deployment and monitoring of their features to minimise the need for manual operational tasks.

### Why?

- **Operational Efficiency** - A high degree of automation, monitoring and utilising managed infrastructure to build reliable software frees up the time of engineers to focus on development instead of operations. We don’t need to hire dedicated Ops engineers to keep things stable.
- **Higher Quality** - Bringing engineers closer to the day-to-day operation of our business establishes a direct feedback loop with our users and allows for faster iteration and ultimately higher quality software design.
- **Accountability** - Being responsible for operations for the code we write is an incentive to do things better. Nobody wants to wake up during the night to fix a memory leak in production.

## Solutions over Problems

“Problem-solving leaders have one thing in common: a faith that there’s always a better way.” – Gerald M. Weinberg

We expect all our engineers to be leaders on this one, when faced with a problem or when identifying a possible problem, all our engineers are incentivized to apply a proactive approach towards helping find solutions over raising problems for someone else to fix. The guideline below lists a set of steps that can be applied to any problem:
- Inception, identify the stakeholders, the multiple points of view, and mitigate any communication issues, be transparent about your doubts
- Negotiation, identify the scope of the problem, some solutions may have pitfalls, but it's important to understand the use cases that they address first
- Elaboration, with the foundation in place, analyze possible solutions or alternative solutions for an already proposed solution
- Negotiation is the cooperation phase, you should now engage with other team members and reach for feedback about the possible solutions you found to a problem or an incomplete solution
- Specification, finally after coming up with an agreement on a solution, modify an existing RFC (Request for Comments) or produce a new one
- Validation, share your RFC and gather enough feedback to produce a PoC (Proof of Concept). We incentive the should don't tell culture.
- Requirement Management, once you have all the above done, you have all the data you need to organize work into actionable backlog items.

### Why?

- **Collaboration**: Engineers should collaborate towards finding solutions. Everyone can present problems, we are the last line of defence against problems, we are the solution makers, and we should behave as such.
- **Productivity**: We are all much more productive when discussing over concrete data, like an alternative solution or a concrete solution for a concrete problem. Raising a problem just for the sake of raising a problem, does not provide that much value.

## API First: We design software with APIs

Before we write a single line of code, we design the APIs of a service in a way that any other team, whether internal to epilot or external, can use the APIs interface with our service without prior knowledge.

We encourage the usage of common, machine readable standards such as OpenAPI, GraphQL or type definitions as design tools.

### Why?

- **Collaboration**: Using APIs to design software helps collaboration across engineers
- **Decoupling**: Teams can get decoupled and work more autonomously
- **Productivity**: Teams work with a contract in mind and are able to work in parallel
- **Transparency**: Commitment and agreement on what is expected from an engineering standpoint

## Rent over build: We rent the necessary and focus on building the important

First, we look at the business value of solving a problem to determine how much impact solving a problem will generate. This will help us to judge what is a necessity or basic expectation where we simply have to tick the box for our customers and what really sets our product apart from the rest, i.e. the unique that a customer will not get anywhere else.

Keeping the necessary vs. the important in mind, we focus on building the important unique features that provide business value and rent everything else off-the-shelf.

This notion applies to all aspects of our software delivery:

- The infrastructure (AWS, serverless, etc.)
- Libraries, frameworks and tools (React tables, design library, testing, etc.)
- Plays and practices (standards, conventions, APIs/Swagger, etc.)

### Why?

- **Shoulders of giants**: Build smarter and faster by taking what other’s have built before us and assembling those things together
- **Focus**: Rely on expert solutions and tooling to free up our engineers to focus on the unique problems that provide the most value for our customers
- **Cost Efficiency**: Reduce costs (operating, maintenance, development, etc.) by renting

## Proof-of-concepts: Show, don’t tell

Often the best way to move things forward is to stop discussing and start building.

Building a concrete POC, an incomplete and intentionally corner-cutting version of a proposed feature helps move the design forward and discover problems with the design early on.

A proof-of-concept should include the critical parts of the system to discover and hopefully prove the end-to-end feasibility of the proposed design.

Proof-of-concepts should be small enough to build with very low effort and be completely disposable. It should be expected that any work done and code written to build a POC will likely be discarded.

The purpose of a POC is to prove the feasibility of a design and get a feel for what the end result might look like with as low upfront effort as possible.

### Why?

- **Fewer meetings**: Trying to rally everyone in the company behind an idea or a new feature can easily result in an endless cycle of meetings and abstract arguments.
- **Things happen**: Even with thorough design work and great planning, things will change after you start building.
- **Code wins arguments**: Proof-of-concepts are a great, concrete tool to convey an idea and avoid wasting time on abstract discussion. They can be used to get feedback early and also help catch obvious issues with the design.



## Progress over perfection

A startup’s lifeblood is innovation and speed of delivery. Being innovative but slow is a risk because other software companies can easily copy our ideas and our alleged lead can quickly evaporate (e.g. Instagram vs. Snapchat).

- To grow we need to constantly strive to deliver customer value as fast as possible.
- We need to carefully separate the important from the unimportant.
- We have to avoid over engineering a solution and constantly challenge what we do.

Neither does it mean we compromise on quality, nor does it mean we aim to build the perfect solution that needs to last for the next 10 years. We accept that the pace of change in software, business and engineering is accelerating and embrace rapid cycle.

### Why?

- **Quick iteration**: Technology is an accelerator for innovation and ultimately solves problems for customers. So the longer a solution for a real problem is perfected and does not get into the hands of our customers, the longer we miss to innovate and drive real customer value.
- **Big Picture**: It’s easy to overengineer something and solve problems that might not exists or might not be a real problem at the moment (optimize for the unknown future)
