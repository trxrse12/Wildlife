0. Agenda
1. Introduction: goals and their prios on whiteboard; also the ground rules (don't by shy to suggest tuture discussions, etc.);
2. Discovery:
- Is your business using the cloud?
- Is the data lake you’re considering building a new solution or a migration?
- Will you use non-relational data?
- How much data do you need to store?
- Will you have streaming data?
- Will you use dashboards and/or ad-hoc queries?
- Will you use batch and/or interactive queries?
- How fast do the reports need to run? Are there service level agreements (SLAs) in place with specific requirements?
- Will you use this data in predictive analytics or machine learning?
- Do you need to master the data?
- Are there any security limitations with storing data in the cloud (for example, defined in your customer contracts)?
- Does this solution require 24/7 client access?
- What is the skill level of the end users?
- How many concurrent users will be accessing the solution at peak times? How many on average?
- What is your budget?
- What is your planned timeline?
- Is the source data cloud-born and/or on-prem born?
- How much data needs to be imported into the solution every day?
- What are your current pain points or obstacles with regard to:
- Do you want to use third-party and/or open source tools?
- Are you okay with using products that are in public or private preview?
- What are your security requirements? Do you need data sovereignty?
- Is data movement a challenge?
- How much self-service BI would you like?

3. The design process:
a. The problem domain >>> use cases, user stories, event storming, etc.
Result: Actors (requirements/users/additional context) and Actions
b. Architectural (non-functional) attributes >>> availability/reliability/performance/scalability/elasticity/security/concurrency
Result: map them onto your archit components

Use Actor/Action approach

3. Following up:
- Summary document
- Physical architecture
- Action items
- Parking-lot items and follow-ups
- Survey

4. Deliverables:
a. Overview
b. The cases
c. The strategy
d. The Arcitecture
e. Sequence Diagrams
f. Architectural Design Records (ADRs)