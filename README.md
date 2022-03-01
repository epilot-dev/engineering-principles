<h1 align="center"> Engineering Principles</h1>

<p align="center"><img alt="epilot" src="./epilot-logo.svg" width="200"></p>

The following is a list of core principles [epilot](https://epilot.cloud/) engineers use to make decisions in their daily work building our software product.

<!-- toc -->

- [Freedom and Responsibility](#freedom-and-responsibility)
- [Ownership: You build it, you run it](#ownership-you-build-it-you-run-it)
- [Show, don’t tell: Deliver working software early and frequently.](#show-dont-tell-deliver-working-software-early-and-frequently)
- [Cult of Quality](#cult-of-quality)
- [Solutions over Problems](#solutions-over-problems)
- [API First: We design software with APIs](#api-first-we-design-software-with-apis)
- [Rent over build: We rent the necessary and focus on building the important](#rent-over-build-we-rent-the-necessary-and-focus-on-building-the-important)
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

## Show, don’t tell: Deliver working software early and frequently.

We believe in the basic Agile principle of "Release early and release often". This approach helps us manage risk and make better decisions by creating fast feedback loops between ourselves and our users.

While prototypes and proof-of-concepts can be great tools early on, we should always maintain shippable code. Avoid creating technical debt. Don't depend on polish happening later. 

Gather feedback where uncertainty exists. We are our own best testing team and as software professionals we shouldn't let our users remind us what quality software looks like. Don't ship and apologise for incomplete or broken features. Ship [minimum lovable products](https://productschool.com/blog/product-management-2/minimum-lovable-product/) instead.

### Why?

- **Code wins arguments**: Debating abstract ideas leads to endless meetings. A working piece of software is always better than architecture diagrams and RFCs.
- **Move fast**: Putting feedback loops in place early on helps us make more informed decisions collaboratively and commit to deliverables that create tangible progress.
- **Risk management**: Even with great design and careful planning, unplanned work is guaranteed to appear once you're in the process of building. So better start early. 

## Cult of Quality

We are making a [cult of quality](https://www.alchemists.io/articles/peopleware/#_make_a_cult_of_quality). The code we produce is always our best work and the most important representation of our level of professional competence.

It's our job to prevent the accumulation of technical debt and maintain the productivity and happiness of our fellow engineers. We refuse any request to lower our quality standards for the sake of cutting corners.

We do not rely on others, especially our customers, to test our software. [We are our own best testing team](https://github.com/anttiviljami/romero-programming-principles#principle-5-dont-rely-on-testers) and should never allow anyone else to experience bugs or see the our software crash. 

### Why?

- **Professional pride**: For our own wellbeing as software engineers, it's extremely important to take pride in the quality of the code we write.
- **Technical debt**: Sacrificing quality in the short term accumulates debt that can and will paralyze our ability to move fast later. We should never do anything that knowingly decreases our long-term productivity.
- **Strong teams**: Quality as a non-negotiable, foundational value builds a sense of eliteness in our teams and binds us together as engineers behind a common cause.

## Solutions over Problems

“Problem-solving leaders have one thing in common: a faith that there’s always a better way.” – Gerald M. Weinberg

We expect all our engineers to be leaders on this one, when faced with a problem or when identifying a possible problem, engineers should apply a proactive approach towards finding solutions over raising problems for someone else to fix.

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



## Progress over perfection

A startup’s lifeblood is innovation and speed of delivery. Being innovative but slow is a risk because other software companies can easily copy our ideas and our alleged lead can quickly evaporate (e.g. Instagram vs. Snapchat).

- To grow we need to constantly strive to deliver customer value as fast as possible.
- We need to carefully separate the important from the unimportant.
- We have to avoid over engineering a solution and constantly challenge what we do.

Neither does it mean we compromise on quality, nor does it mean we aim to build the perfect solution that needs to last for the next 10 years. We accept that the pace of change in software, business and engineering is accelerating and embrace rapid cycle.

### Why?

- **Quick iteration**: Technology is an accelerator for innovation and ultimately solves problems for customers. So the longer a solution for a real problem is perfected and does not get into the hands of our customers, the longer we miss to innovate and drive real customer value.
- **Big Picture**: It’s easy to overengineer something and solve problems that might not exists or might not be a real problem at the moment (optimize for the unknown future)
