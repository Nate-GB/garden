---
title: "Extreme Programming"
tags:
- sapling
- project
---

## What is it?
- An [Agile Approach](notes/Agile%20Approach.md) for software development
- Heavy emphasis on software engineering practices
- XP takes good software development practices to extreme levels and codifies them
- Puts a customer on the development team
- Aims to create a higher quality of life for the developer and better software for the customer

## 5 values
- Communication
- Simplicity
- Feedback
- Respect
- Courage

## Roles
- Customer
	- Decides which features are needed eventually and which are needed next
	- Teams can select one of more customer proxies if the "customer" is a large user-base
- Tracker
	- Captures metrics, measures progress, and looks for improvement opportunities
	- Usually part-time role for a team member
- Coach
	- Mentors team members on how to use XP practices. Usually somebody outside the team who has experience in XP

## Common Practices
- Pair Programming
	- Two software engineers work side by side to create code at once
	- Typically one person writes the code, while the other watches and provides feedback
- Ten-minute build
	- It should take ten minutes or less to build, test, and deploy the entire system
	- If it takes longer, devs are less likely to run tests
- Continuous Integration
	- Merge local code onto the main repo regularly, at least a few times a day
	- Reduces conflicts and allows automatic builds and tests to run
- Test-first programming
	- traditional software development writes and passes tests after development, but XP does it before
	- Also called "Test Driven Development"
	- Writes tests and then writes the code to pass the tests
- Incremental Design
	- XP adopts incremental design, like all other [Agile Approaches](notes/Agile%20Approach.md)
	- Small, infrequent improvements are more valuable than delayed releases
- Sit together
	- Teams work in a shared, open space
- Whole Team
	- Everybody needed for a project is on the team
- On-site Customer
	- XP includes the customer on the team
- Energized Work
	- 40 hour workweeks, max
	- No back to back overtime
- Stories
	- An effective format for communicating requirements
	- User's needs are written in a short, descriptive format that conveys what the user wants and how it would help them
- Weekly Cycle
	- Similar to a sprint cadence
	- Each week the team selects stories and plans work for the week
- Quarterly Cycle
	- A planning and reflection event
	- Team inspects and adapts their processes
	- Identify major themes for the project and create stories to deliver upon them
- Slack
	- Slack must be built into the team's weekly plan by including option tasks that the team can reschedule if they don't have time to complete them

## Strengths and Weaknesses
- Strengths
	 - Highly efficient
	- Builds the most essential increments first
	- Does not waste time on low-priority features
	- Continuous integration, automation, and a high rate of adaptability
	- Teams come together quickly
	- Less project failure because customer is a team member
- Weaknesses
	- Limited to software development
	- Can result in lackluster design
	- Rapid pace can cause high stress on devs
	- Minimal documentation can hinder new team members' understanding
	- Relies on face-to-face interaction between team members and customers