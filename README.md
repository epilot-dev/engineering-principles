<h1 align="center"> Engineering Principles</h1>

<p align="center"><img alt="epilot" src="./epilot-logo.png" width="200"></p>

The following is a list of core principles [epilot](https://epilot.cloud/) product engineers ([What is a product engineer?](https://productengineer.org)) use to make decisions in their daily work.

<!-- toc -->

- [Freedom and Responsibility](#freedom-and-responsibility)
- [Continuous Delivery](#continuous-delivery)
- [Ownership: You build it, you run it](#ownership-you-build-it-you-run-it)
- [Complete the Mission](#complete-the-mission)
- [Show, don't tell: Deliver working software early and frequently.](#show-dont-tell-deliver-working-software-early-and-frequently)
- [Every Week is Quality Week](#every-week-is-quality-week)
- [Solutions over Problems](#solutions-over-problems)
- [API First: We design software with APIs](#api-first-we-design-software-with-apis)
- [Rent over build: We rent the necessary and focus on building the important](#rent-over-build-we-rent-the-necessary-and-focus-on-building-the-important)
- [Progress over perfection](#progress-over-perfection)
- [Delete before optimizing](#delete-before-optimizing)
- [Feasibility before vision](#feasibility-before-vision)
- [Named requirements](#named-requirements)

<!-- tocstop -->

## Freedom and Responsibility

We hire smart people who we can trust.

We operate by principles and expect every individual to cultivate a strategic mindset.

Engineers should possess a Hacker mentality to make their own decisions with their tools and methods even going outside of our established "stack" when warranted.

Teams are experts in their domains and own their decisions and the consequences of their decisions.

Experts provide support for decisions but do not act as gatekeepers.

### Why?

- **Speed**: Independency means speed, because teams can make their own decisions and don't have to wait for centralized organs to approve everything they do.
- **Ownership**: Independency means ownership, because teams have to live with their decisions
- **Motivation**: Autonomy motivates, because teams are expected to find solutions for their challenges.

## Continuous Delivery

We organize and develop our software as small decoupled services, with named engineers owning the maintenance and development of each service. These services are then integrated and deployed through a unified continuous delivery (CD) pipeline, incorporating automated end-to-end tests verifying functionality in the context of realistic use cases and data.

### Why?

- **Reliability** Our customers expect all features to work seamlessly together at all times. Testing end-to-end with realistic use cases helps prevent most regressions.
- **Speed** Continuous delivery with automated testing allows us to ship with confidence and deliver features our customers want, faster.
- **Modular architecture** Keeping services small and decoupled helps keep our software easier to reason about and maintain while allowing diversity in tech choices.

## Complete the Mission

Execution matters more than the details. If you don't deliver, nothing else counts.

If something is your responsibility, it gets done. There's no credit for effort alone, no excuses for setbacks, and no rewards for stopping short. This principle is about relentless focus on the outcome—setting a clear mission and ensuring it is achieved.

- We take **full responsibility** for what we own and see it through to the end.
- We **solve problems, not just highlight them**. Delays and obstacles don't excuse failure.
- We don't celebrate "almost done". **Real impact comes from delivery, not effort.**

Every initiative must have a single named owner. If no one owns it, it doesn't exist. If the owner can't execute, the initiative dies or gets a new owner — it doesn't get passed around as someone else's problem. Ownership is not delegable. You finish what you start, or you kill it honestly.

When faced with challenges, we find a way forward, take responsibility, and make it happen. Delivering results is what matters, whether in engineering, operations, product, or leadership.

### Why?

- **Ownership drives impact**: If no one owns a problem, it doesn't get solved. Taking ownership means stepping up and ensuring real progress happens.
- **Accountability creates trust**: Teams that take responsibility—both for successes and failures—are the ones people rely on.
- **Delivery is the only measure of execution**: Ideas, discussions, and partial work mean nothing if they don't translate into **real results**.
- **Zombie initiatives destroy morale**: Initiatives without clear ownership, concrete progress, or a path to completion drain energy from teams and erode trust. Kill them early.

## Ownership: You build it, you run it

We subscribe to this core principle of the DevOps movement.

There is no dedicated Ops team who you can pass on the responsibility to take your code and make sure it runs reliably and scales to customers' needs.

Each team owns their deployment issues, performance bugs, capacity planning, monitoring, technical support; operating the pieces of software they build.

We expect teams to automate testing, deployment and monitoring of their features to minimise the need for manual operational tasks.

### Why?

- **Operational Efficiency** - A high degree of automation, monitoring and utilising managed infrastructure to build reliable software frees up the time of engineers to focus on development instead of operations. We don't need to hire dedicated Ops engineers to keep things stable.
- **Higher Quality** - Bringing engineers closer to the day-to-day operation of our business establishes a direct feedback loop with our users and allows for faster iteration and ultimately higher quality software design.
- **Accountability** - Being responsible for operations for the code we write is an incentive to do things better. Nobody wants to wake up during the night to fix a memory leak in production.

## Show, don't tell: Deliver working software early and frequently.

We believe in the basic Agile principle of "Release early and release often". This approach helps us manage risk and make better decisions by creating fast feedback loops between ourselves and our users.

Value is what we want. Working software delivers value. Delivering working software early gives us value sooner.

While prototypes and proof-of-concepts can be great tools early on, we should always maintain shippable code. Avoid creating technical debt. Don't depend on polish happening later.

### Why?

- **Code wins arguments**: Debating abstract ideas leads to endless meetings. A working piece of software is always better than architecture diagrams and RFCs.
- **Move fast**: Putting feedback loops in place early on helps us make more informed decisions collaboratively and commit to deliverables that create tangible progress.
- **Risk management**: Even with great design and careful planning, unplanned work is guaranteed to appear once you're in the process of building. So better start early.

## Every Week is Quality Week

Our teams appear cult-like when it comes to quality. We believe the code we produce is always our best work and represents our level of professional competence. No excuses.

It's our job to prevent the accumulation of technical debt and maintain the productivity and happiness of our fellow engineers. We refuse any request to lower our quality standards for the sake of cutting corners.

We do not rely on others, especially our customers, to test our software. [We are our own best testing team](https://github.com/anttiviljami/romero-programming-principles#principle-5-dont-rely-on-testers) and should never allow anyone else to experience bugs or see our software crash.

### Why?

- **Professional pride**: For our own wellbeing as software engineers, it's extremely important to take pride in the quality of the code we write.
- **Technical debt**: Sacrificing quality in the short term accumulates debt that can paralyze our ability to move fast later. We should never do anything that knowingly decreases our long-term productivity.
- **Strong teams**: Quality as a non-negotiable, foundational value builds a sense of eliteness in our teams and binds us together as engineers behind a common cause.

## Solutions over Problems

"Problem-solving leaders have one thing in common: a faith that there's always a better way." – Gerald M. Weinberg

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

This also applies to product features. Before building a capability, ask: do our customers already have a tool for this? If yes, integrate — don't compete. We build what's uniquely ours. We integrate everything else. The fastest way to deliver value is often connecting to something that already works rather than rebuilding it from scratch.

This notion applies to all aspects of our software delivery:

- The infrastructure (AWS, serverless, etc.)
- Libraries, frameworks and tools (React tables, design library, testing, etc.)
- Plays and practices (standards, conventions, APIs/Swagger, etc.)
- Product capabilities (integrate with existing customer tools rather than replacing them)

### Why?

- **Shoulders of giants**: Build smarter and faster by taking what other's have built before us and assembling those things together
- **Focus**: Rely on expert solutions and tooling to free up our engineers to focus on the unique problems that provide the most value for our customers
- **Cost Efficiency**: Reduce costs (operating, maintenance, development, etc.) by renting
- **Market reality**: Our customers already use tools for common needs. Competing with established solutions wastes engineering time. Integrating with them creates value immediately.

## Progress over perfection

A startup's lifeblood is innovation and speed of delivery. We accept that the pace of change in software, business and engineering is accelerating and embrace rapid cycle times.

Being slow is a risk because it opens the door for other software companies to take our ideas and overtake us with speed, evaporating our alleged lead (e.g. Instagram vs. Snapchat).

- To grow we need to constantly strive to deliver customer value as fast as possible.
- We need to carefully separate the important from the unimportant.
- We have to avoid over engineering a solution and constantly challenge what we do.

In situations where we lack definitive answers based on real world data, we err on the side of speed and iteration over endless discussion and planning.

This doesn't mean we compromise on quality, and especially not security. Quality engineering allows us to maintain speed in the long term, while a restless focus on security ensures the continuity of our business.

### Why?

- **Quick iteration**: Technology is an accelerator for innovation and ultimately solves problems for customers. So the longer a solution for a real problem is perfected and does not get into the hands of our customers, the longer we miss to innovate and drive real customer value.
- **Big Picture**: It's easy to overengineer something and solve problems that might not exists or might not be a real problem at the moment (optimize for the unknown future)

## Delete before optimizing

Before improving a process, feature, or workflow, first ask: should this exist at all?

The best code is no code. The best process is no process. The best meeting is no meeting. We actively prune scope, remove unused features, and kill initiatives that lack a concrete customer need.

If you're not regularly deleting things — code, processes, meetings, scope — you're accumulating drag. Addition is easy. Subtraction requires judgment.

### Why?

- **Simplicity compounds**: Every line of code, every process, every recurring meeting carries maintenance cost. Removing what doesn't earn its keep frees capacity for what matters.
- **Courage over comfort**: It's easier to add than to remove. Removing requires admitting something wasn't needed or didn't work. We value that honesty.
- **Speed**: The fastest way to finish something is to realize it doesn't need to be done. Scope reduction is the most underused tool in engineering.

## Feasibility before vision

No design or product vision gets roadmap priority without an engineering feasibility check.

Vision without implementation reality is fiction. We validate before we iterate. Engineers are involved from the start — not brought in after the design is "done" to figure out how to make it work.

A North Star is useful for direction, but useless without a grounded path to get there. If a vision has been redesigned multiple times without shipping, it's not a vision — it's a hallucination.

### Why?

- **Grounded execution**: The gap between "what we want" and "what we can build" is where initiatives go to die. Closing that gap early saves everyone's time.
- **Engineer involvement**: Engineers closest to the system know what's possible, what's cheap, and what's expensive. Excluding them from early decisions produces designs that don't survive contact with reality.
- **Accountability**: When engineering signs off on feasibility upfront, there's shared ownership of the outcome. When engineering inherits an infeasible plan, there's only blame.

## Named requirements

Every requirement must trace back to a named person and a concrete customer scenario.

"We need this" is not a requirement. "Customer X needs Y to do Z" is. Anonymous requirements produce vaporware. If nobody can attach a real name and a real use case to a request, it doesn't make the cut.

This applies to features, integrations, process changes, and tooling decisions. If it can't be grounded in a specific, named need, it's speculation — and speculation doesn't ship.

### Why?

- **Accountability**: A named requirement has an owner. An anonymous one has none. Ownership drives follow-through.
- **Focus**: Grounding work in real customer scenarios prevents building for imaginary use cases or demo-driven development.
- **Prioritization**: When everything is "needed," nothing is prioritized. Named requirements with concrete scenarios make trade-offs visible and honest.
- **Trust**: Customers trust us when we solve their actual problems. They lose trust when we build features nobody asked for while their real needs go unmet.
