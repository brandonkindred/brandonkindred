# Brandon Kindred

I'm a professional nerd. That's the short version.

The longer version: I'm unashamedly curious and aggressively interested in how things work. I poke at things, I take them apart, and along the way I tend to spot problems and build something to fix them. Sometimes that something turns into a real tool people use. Sometimes it's an interesting demonstration of nothing in particular. Both are fine — that's how the learning happens.

If you scroll through my repos you'll find a mix of curiosity, failed ventures, and the occasional useful tool. **No promises on the functionality of anything specifically.** I'm here to be curious and learn out loud.

A note on what's happening here right now: I shut Qanairy down years ago, but I never stopped using pieces of it. For a long time those pieces lived as janky personal setups — held together with whatever shortcut got me to the answer. Newish parenthood has a way of making "I'll fix it later" feel expensive, so I've been pulling the parts I rely on out into their own clean services. A few of those are below.

## A few favorites

**[Khala — Agentic AI Teams](https://github.com/brandonkindred/Khala-Agentic-AI-Teams)**
My open R&D environment for learning the ins and outs of AI agents and agentic teams, built on the AWS Strands Agents SDK. Twenty named functional teams — strategy lab, nutritionist, sales, agent registry — coordinated through a planning and orchestration layer. Increasingly the place I spin up new agentic teams and run exploratory experiments.

**[Deepthought](https://github.com/brandonkindred/Deepthought)**
A graph-based reasoning engine that stores model weights as edges inside a Neo4j knowledge graph instead of dense parameter matrices. Learning is localized — only the edges connected to the tokens in a training example get updated, via Q-learning — which keeps the whole thing CPU-only and the reasoning paths inspectable. Named for the Douglas Adams computer; the bet is that systems that *reason* and explain themselves beat systems that only compute. Its lineage traces back to the RL core I built for Qanairy.

**[browser-service](https://github.com/brandonkindred/browser-service)**
Hands out a real, dedicated browser instance over the network and keeps it alive for the session — open → interact → close, sticky on a session id, with a real-time socket and an HTTP fallback. Selenium 4 for desktop, Appium 8 for mobile. This is the clean spin-off of the Selenium browser farm that used to live inside Look-see and eat the GKE bill; instead of an embedded WebDriver in every consumer, it's a service that hands you a browser.

**[Unified-Data-Processing](https://github.com/brandonkindred/Unified-Data-Processing)**
A Java 17 library that gives Kafka, Amazon MSK, Pulsar, Google Cloud Pub/Sub, and AWS Kinesis the same publisher/consumer interface — write the producer/consumer code once, swap brokers by swapping the wiring. On top of that sit `DataBridge` (fans heterogeneous sources into a unified Kafka backbone) and `DataRelay` (fans the backbone back out to any of the supported brokers), both at-least-once with provenance stamped on every message. It's the "stop writing the same ingestion shim for the fourth time" library.

**[Look-see](https://github.com/brandonkindred/Look-see)** — 2020–2024
An automated web accessibility audit platform that automates over 80% of WCAG requirements. Sole founder, sole engineer. MassChallenge 2021 cohort. The fun engineering bit was retiring two GKE clusters (a duplicated-monolith scale-out and the Selenium browser farm that ate the bill) and rebuilding on Cloud Run + Pub/Sub + Neo4j — operational cost went from ~$13K/mo to ~$640/mo. The browser-farm half of that work is what eventually became browser-service.

## Things I've written

**[Using Semantic Versioning to Simplify Release Management](https://aws.amazon.com/blogs/devops/using-semantic-versioning-to-simplify-release-management/)** — AWS DevOps & Developer Productivity Blog
A release-management pattern for teams shipping fast without breaking downstream consumers.

**[Creating Your First CI/CD Pipeline Using GitHub Actions](https://brandonkindred.medium.com/creating-your-first-ci-cd-pipeline-using-github-actions-81c668008582)**
A practical, runnable walkthrough. 3,900+ reads and still compounding.

**[Mastering Concurrency with the Dining Philosopher Problem](https://brandonkindred.medium.com/mastering-concurrency-with-the-dining-philosopher-problem-8445920f7863)**
CS fundamentals treated as fundamentals, not trivia.

**[Navigating a Maze with the A\* Algorithm in Python](https://brandonkindred.medium.com/navigating-a-maze-with-the-a-algorithm-in-python-94846529ceb8)**
Pathfinding from first principles.

More at [brandonkindred.medium.com](https://brandonkindred.medium.com).

## Conversations

**[Product for Product Management — EP 40: Startups, Look-See](https://www.spreaker.com/episode/ep-40-startups-look-see-with-brandon-kindred--48806607)** (Feb 2022) — with Matt Green & Moshe Mikanovsky. Founder story, accessibility audit product, what product managers should know about the lane.

**[Radio Entrepreneurs — Brandon Kindred, Qanairy, Inc.](https://radioentrepreneurs.com/2019/02/27/brandon-kindred-qanairy-inc/)** (Feb 2019) — with Nathan Gobes. Using AI to automate UI test generation and maintenance. [YouTube cut](https://www.youtube.com/watch?v=guJsWsWzNo0).

**[Underserved — EP 029: Domo Arigato, Mr. Roboto](https://www.tapesearch.com/episode/ep-029-domo-arigato-mr-roboto/3xKvDRKH6dBHpL7AV39hjh)** (Nov 2020) — with Andrew Gelina. Path into programming, FIRST Robotics, AI/ML for software testing, founder lessons.

## What I reach for

I've shipped production code in Perl, Kotlin, Python, Java, TypeScript/JavaScript, Scala, SQL, and Cypher. AWS (Lambda, API Gateway, EventBridge, Step Functions, ECS, DynamoDB), Terraform, CDK, Neo4j, Kafka. Problems over stacks — I pick up whatever the problem requires.

---

If you're looking for my **professional work** — clients, employers, the serious résumé version — that lives on [LinkedIn](https://www.linkedin.com/in/brandon-kindred/). This page is the curiosity side.
