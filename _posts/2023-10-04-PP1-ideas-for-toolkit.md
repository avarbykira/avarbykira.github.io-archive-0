---
title: Ideas for PP1 Toolkit
date: 2023-10-04 15:12:00 +1000
categories: 
tags: 
---

## 1. Interactive Visualization Tool: ImplicaTree

### Description

The ImplicaTree visualizes the cascading effects of a technical decision in a tree-like structure. 

Starting with the decision at the trunk, branches represent primary outcomes, and twigs represent secondary or tertiary outcomes.

![[example-of-m-ary-tree.png]]

### Features

[[Drawing 2023-10-04 13.29.44.excalidraw]]

- **Decision Node:** Start by inputting the core technical decision or solution. In this graph, it is node A.
- **Predictive Analysis:** Using historical data and predictive algorithms, the tool suggests potential direct (primary) outcomes. These are your main branches.
- **Expandable Nodes:** Clicking on any primary outcome (branch) will expand it to reveal secondary and even tertiary consequences, forming the twigs.
- **User Input:** Users can manually add or adjust branches based on their expertise, predictions, or specific concerns.
- **Color Coding:** Outcomes are color-coded: green for positive, red for negative, and yellow for neutral or uncertain. This gives an immediate visual sense of the potential benefits or problems.
- **Annotations:** Each branch/twig can be annotated with notes, relevant articles, or research.

### Benefits

- gives engineers a visual, holistic view of potential implications.
- can clearly see cascading effects
- can more responsibly anticipate and address potential challenges.

## 2. Board Game: Ethical Navigators

### Description

In "Ethical Navigators," players collaboratively address tech scenarios using a deck of cards. 

Each round introduces:

- a tech situation (Topic Card)
- its challenges (Dilemma Card)
- and a unique perspective (Stakeholder Card). 

Players propose solutions, allocate "Solution Tokens" to emphasize their decisions, and then vote on the best approach, considering both the dilemmas and the stakeholder's interests. After several rounds, the player with the most points, earned from peer votes, emerges as the "Chief Ethical Navigator."

### Components

#### Topic Cards

These set the stage with a realistic tech situation.

1. **Smart City Integration** _Description:_ Your team is responsible for implementing a new IoT-based traffic management system in a bustling city, aiming to reduce congestion and optimize traffic flow.
2. **AI-powered Healthcare Tool** _Description:_ You're developing a diagnostic AI tool that predicts potential health risks based on a patient's genetics, lifestyle, and medical history.
3. **Personalized Learning Software** _Description:_ Your company plans to launch an educational software that personalizes curriculum for each student, using real-time data analytics to adapt content.

#### Dilemma Cards

Present 2-3 challenges or complications related to the topic.

For Smart City Integration: 

1. **Data Privacy Concerns** _Description:_ The traffic management system requires collecting real-time location data from vehicles and personal devices. How will you ensure privacy?
2. **Potential Job Loss** _Description:_ The system's efficiency might render several traffic management jobs obsolete. How will this employment shift be addressed?
3. **Infrastructure Costs** _Description:_ Upgrading the city to accommodate the new system will be costly and might require rerouting traffic for months, causing disruptions.

For AI-powered Healthcare Tool: 

1. **Bias in Prediction** _Description:_ Early tests indicate the tool might be less accurate for minority ethnic groups. How do you address this bias?
2. **Patient Anxiety** _Description:_ The tool might predict health risks that are not immediately actionable, potentially causing undue stress for patients.
3. **Data Security** _Description:_ Storing sensitive health data presents a target for cyberattacks. How will you ensure the security of this data?

For Personalized Learning Software:

1. **Learning Gaps** _Description:_ The adaptive nature might cause some students to miss out on foundational knowledge. How can you ensure a comprehensive education?
2. **Over-reliance on Tech** _Description:_ Teachers express concern that they'll become too reliant on the software, losing the human touch in education.
3. **Data Collection Ethics** _Description:_ The software requires monitoring student behaviours and responses closely. How will you address concerns about surveillance and data use?

#### Stakeholder Cards

Introduce a non-traditional stakeholder, offering a fresh perspective on the situation.

1. **Local Small Business Owner** _Perspective:_ Concerned about how tech implementations, especially in urban settings, might affect foot traffic, customer behaviour, or even their business's relevance.
2. **Elderly Patient without Tech Savvy** _Perspective:_ Has limited experience with technology and is wary of AI predictions, preferring human touch in healthcare. Concerns about understanding and using the tool.
3. **Parent of a Student with Learning Disabilities** _Perspective:_ Worried that the software might not cater adequately to special needs or might label their child based on pace, affecting self-esteem.

### Setup

- Shuffle each set of cards separately and place them face down.
- Each player starts with a set number of "Solution Tokens" (which represent potential solutions or actions).

### Gameplay

1. **Drawing the Scene**:
    - Draw one "Topic Card" to establish the tech situation for the round.
    - Draw a corresponding "Dilemma Card" to highlight the challenges.
    - Finally, draw a "Stakeholder Card" to introduce a unique perspective into the mix.

2. **Discussion Phase**:
    - Players discuss the scenario, considering the challenges presented by the dilemma and the interests of the introduced stakeholder.
    - Players can reference real-world cases, ethical principles, and potential long-term consequences during their discussions.

3. **Solution Proposal**:
    - Each player thinks of a potential solution to the challenge, using their "Solution Tokens" to give weight to certain actions or decisions. They can allocate multiple tokens to emphasize a solution's importance.
    - Players then present their proposed solutions to the group, justifying their decisions and token allocations.

4. **Voting & Feedback**:
    - Players vote on the best solution, excluding their own.
    - The solution with the most votes is considered the group's decision for the round.
    - Feedback is discussed: Why did players choose one solution over another? How did the stakeholder's perspective influence decisions?

5. **Scoring**:
    - Players earn points based on the number of votes their solution received.
    - Bonus points are awarded for solutions that address the stakeholder's interests most effectively.

6. **Game End**:
    - After a predetermined number of rounds or when the card decks are exhausted, the player with the most points is deemed the "Chief Ethical Navigator."

### Benefits

1. **Diverse Viewpoints:** The game introduces non-traditional stakeholders, ensuring players recognize and value diverse viewpoints, fostering empathy and a broader understanding of tech implications.
2. **Real-World Application**: Through realistic tech situations and dilemmas, players are equipped with the tools to confront actual challenges in their professional work, bridging the gap between theory and practice.
3. **Collaborative Decision-Making**: Engineers and scientists often work in teams. The game promotes collaborative ethical decision-making, honing skills in negotiation, perspective-taking, and collective problem-solving.