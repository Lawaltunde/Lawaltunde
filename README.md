# Hammed Lawal

Java backend engineer. I build Spring Boot services and REST APIs that stay fast and correct under real use: background processing for slow work, transactional workflows in PostgreSQL that keep payments and stock consistent, and AI features with fallbacks, cost limits and tests behind them. I secure APIs with Spring Security, cover my work with JUnit, Mockito and Testcontainers, and ship it with Docker and CI/CD to AWS. I share Java backend lessons on LinkedIn as StillYourLawal.

## Featured projects

**[ScoreNorth](https://scorenorth.org)** · [how it's built](https://github.com/Lawaltunde/scorenorth-showcase)
A CELPIP practice platform with 500+ active users. AI grades speaking and writing answers.
To keep costs under control it has a budget guard, a per-student cap and a fallback scorer, and models can be swapped through config without code changes.

**[AI Booking Agent](https://github.com/Lawaltunde/hotel-reservation-agent-team5)**
Finds the cheapest suitable hotel in any Canadian city and phones the front desk to confirm price and availability. Built by a three-person team in seven hours at the TechTO Fast & Frugal Hackathon, placing top 4 of 20.
The model (GPT-5.4 mini) only extracts structured details. Price ranking is plain Java, parallel calls are capped, and Google Places field masks keep API costs low.

**[MedSimple](https://github.com/Lawaltunde/med_simple)**
A patient intake and triage app: patients report symptoms as text, voice or photo, and clinics see cases ordered by urgency rather than booking time. Presented at hackathons.
Each clinic integration and AI feature sits behind an adapter with a rule-based fallback chosen at runtime, and the audit log is append-only, enforced by a PostgreSQL trigger.

## Awards

- Sofvie Analytics Award
- Cambrian Award of Excellence
- AWS Autonomous DeepRacer 2025 Winner

## Stack

Java, Spring Boot, Spring AI, PostgreSQL, Docker, React, AWS (EC2, S3), Kafka

## Links

[Portfolio](https://portfolly.io/lawalhammed) · [LinkedIn](https://www.linkedin.com/in/hammed-lawal-tunde)
