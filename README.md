# Smart India Hackathon Workshop
# Date:29/03/2025
## Register Number:212224230295
## Name:Vasanth P
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
```
The system will be a web-based simulation software that replicates a real-world interview scenario. It will use AI-based question generation, response evaluation, and scoring mechanisms to ensure an unbiased, structured assessment process. The system will include:

A dynamic question bank tailored to candidate expertise.

AI-driven scoring mechanisms for response evaluation.

A virtual boardroom interface with structured interview flow.

Data analytics for performance evaluation.
```

## Proposed Solution / Architecture Diagram
```
![image](https://github.com/user-attachments/assets/022a1918-3821-4e18-9b36-81c4af7ae89e)



The system consists of the following major components:

1.User Interface (UI)

Web-based interface for candidates and selectors.

Virtual boardroom environment with real-time interaction.

2.Backend System

Question Generation Module: AI-based system to generate relevant questions based on applicant expertise.

Evaluation Engine: NLP-based response evaluation system to grade answers.

Scoring & Ranking Module: Computes relevance scores and ranks candidates.

3.Database

Stores candidate profiles, interview history, and performance metrics.

4.AI & NLP Engine

Machine learning algorithms to analyze responses.

Sentiment analysis for evaluating confidence and clarity.

5.Security & Access Control

Role-based access for interviewers and candidates.

Data encryption for secure candidate information.

```
## Use Cases
```
![image](https://github.com/user-attachments/assets/85776faa-61a7-4617-ba79-ad5d1d76f15e)

1.Candidate Registration

Candidates sign up and provide details about their expertise and background.

2.Interview Panel Setup

Experts create an interview session and define candidate requirements.

3.Question Generation & Evaluation

System generates relevant questions based on the candidate’s domain.

The AI engine evaluates responses for correctness and relevance.

4.Real-time Interviewing

Candidates interact with a virtual panel.

Experts can manually pose additional questions.

5.Scoring & Report Generation

The system generates a detailed candidate evaluation report.

Scores are calculated based on response quality and domain knowledge.
```

## Technology Stack
```
Frontend
React.js / Angular.js (for a dynamic and responsive UI).

Bootstrap / TailwindCSS (for UI styling).

Backend
Node.js with Express.js / Django (for API development).

Database
PostgreSQL / MongoDB (to store candidate profiles, interview data).

AI & NLP
Python with TensorFlow / OpenAI API (for response evaluation).

Natural Language Processing (NLTK, spaCy) for scoring relevance.

Real-time Communication
WebRTC / Socket.io (for live interviews).

Authentication & Security
OAuth 2.0 / JWT (for secure login).

AES Encryption (for data security).

```

## Dependencies
```
Dependencies
Cloud services for hosting (AWS / Azure / GCP).

AI/ML models for NLP-based response evaluation.

Database management tools (PostgreSQL / MongoDB).

WebRTC for real-time interviews.

```

