# Brandon Kindred

Systems engineer working on graph-native ML and neuro-symbolic systems since 2016. Currently Cloud Application Architect at AWS Professional Services.

Three-time founder. Built a graph-native ML system from 2016 to 2020 whose core architectural bets (knowledge graphs as first-class weights, retrieval over graph structure) have since become mainstream under labels like GraphRAG and knowledge-graph agents. I care about the problems under the hype cycle: distributed systems, graph ML, CS fundamentals. I write and ship to prove it.

For background, roles, and professional references: [linkedin.com/in/brandon-kindred](https://www.linkedin.com/in/brandon-kindred/).

## Selected Work

**[Khala — Agentic AI Teams](https://github.com/brandonkindred/Khala-Agentic-AI-Teams)**
Personal R&D environment, open-sourced, where I learn the ins and outs of AI agents and agentic teams. Built on the AWS Strands Agents SDK. Twenty named functional teams (strategy lab, nutritionist, sales, agent registry, and more) coordinated through a planning and orchestration layer. Increasingly a system for spinning up new agentic teams and running exploratory experiments like Deepthought, a recursive agent. Look-see is the first external pilot built on top of it.

**[Look-see](https://github.com/brandonkindred/Look-see)** — 2020–2024
Automated web accessibility audit platform that automates over 80% of WCAG requirements. Sole founder, sole engineer. MassChallenge 2021 cohort. Reduced operational cost from ~$13K/mo to ~$640/mo by retiring two GKE clusters (one running a duplicated-monolith scale-out pattern, one hosting a Selenium browser farm that dominated the bill) in favor of a decomposed service on Google Cloud Run + Pub/Sub, Neo4j on Compute Engine, and a Cloud Run hosted Selenium Docker image still published on my GitHub.

**HypeDrive** — *originally BuzzBands*, 2015–2016
Geofenced mobile promotions platform. Sole engineer on a shipped iOS + Android app (Angular compiled to native via PhoneGap) and a Ruby on Rails + PostgreSQL backend. Product shipped, never reached paying customers. Kept the codebase and the lesson: a working product doesn't rescue a distribution gap.
Repos: [BuzzBands](https://github.com/brandonkindred/BuzzBands) · [buzzbands_mobile](https://github.com/brandonkindred/buzzbands_mobile) · [buzzbands_client](https://github.com/brandonkindred/buzzbands_client)

**Qanairy** — 2016–2019
Automated web user interface testing service that used reinforcement learning and and Graph ML to map web applications and generate tests autonomously. Failed to identify distribution channel for growth. The RL core is now in the Deepthought repo. *Best in Class: Transfer Learning*, AI DevWorld San Jose, 2019.

## Selected Writing

**[Using Semantic Versioning to Simplify Release Management](https://aws.amazon.com/blogs/devops/using-semantic-versioning-to-simplify-release-management/)** — AWS DevOps & Developer Productivity Blog
Release-management pattern for teams shipping fast without breaking downstream consumers.

**[Creating Your First CI/CD Pipeline Using GitHub Actions](https://brandonkindred.medium.com/creating-your-first-ci-cd-pipeline-using-github-actions-81c668008582)**
Practical, runnable walkthrough. 3,900+ reads and still compounding.

**[Mastering Concurrency with the Dining Philosopher Problem](https://brandonkindred.medium.com/mastering-concurrency-with-the-dining-philosopher-problem-8445920f7863)**
CS fundamentals treated as fundamentals, not trivia.

**[Navigating a Maze with the A\* Algorithm in Python](https://brandonkindred.medium.com/navigating-a-maze-with-the-a-algorithm-in-python-94846529ceb8)**
Pathfinding from first principles.

More at [brandonkindred.medium.com](https://brandonkindred.medium.com).

## Talks & Appearances

**[Product for Product Management — EP 40: Startups, Look-See](https://www.spreaker.com/episode/ep-40-startups-look-see-with-brandon-kindred--48806607)** (Feb 2022)
With hosts Matt Green & Moshe Mikanovsky. Founder story, accessibility audit product, what product managers should know about the lane.

**[Radio Entrepreneurs — Brandon Kindred, Qanairy, Inc.](https://radioentrepreneurs.com/2019/02/27/brandon-kindred-qanairy-inc/)** (Feb 2019)
With Nathan Gobes. Founder interview on Qanairy, using AI to automate generation and maintenance of UI tests. [YouTube cut](https://www.youtube.com/watch?v=guJsWsWzNo0).

**[Underserved — EP 029: Domo Arigato, Mr. Roboto](https://www.tapesearch.com/episode/ep-029-domo-arigato-mr-roboto/3xKvDRKH6dBHpL7AV39hjh)** (Nov 2020)
With host Andrew Gelina. Engineer-focused conversation: path into programming, FIRST Robotics competitions, AI/ML for software testing, founder lessons.

## What I build in

Production code shipped in Perl, Kotlin, Python, Java, TypeScript/JavaScript, Scala, SQL, and Cypher. AWS (Lambda, API Gateway, EventBridge, Step Functions, ECS, DynamoDB), Terraform, CDK, Neo4j, Kafka.

Problems over stacks. I pick up whatever the problem requires.
