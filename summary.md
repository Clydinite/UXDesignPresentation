# Project Summary: Tainan Park Activity Platform

This document provides a comprehensive summary of the User Experience Design project focused on creating a digital platform for Tainan Park. It covers the entire design process, from initial research to prototyping and verification.

## 1. Project Overview & Goal

The project, titled "TainanPark Activity Platform (台南公園輕社交平台)," is a school project exploring how a digital platform can facilitate low-pressure, comfortable, and authentic social interactions for teenagers. The platform is centered around Tainan Park and allows teens to discover or host small, "vibe-based" activities like sunset walks, casual photography, or quiet meetups. The core design philosophy is to help shy or slow-to-warm-up users take their first step into social spaces at their own pace.

*   **Source**: `data/intro.md`

---

## 2. Phase 1: Design Discovery & Research

This phase focused on understanding the users and defining the core problem, starting with broad observation before jumping to solutions.

*   **Source**: `data/research_process.pdf`

### 2.1. Initial Research & Site Selection

The team conducted a preliminary study of three potential sites in Tainan: Da-Dong Night Market, Yin-tong Community, and Tainan Park.

*   **Decision**: Tainan Park was selected.
*   **Rationale**: The park is a "non-purposed" open space with a diverse demographic and low environmental pressure. It presented a unique challenge: the "digital island" phenomenon, where people are physically present but psychologically isolated in their digital worlds. This provided a rich ground for a UX-focused behavioral study.
*   **Source**: `data/research.md`

### 2.2. Field Study & User Observation

In-depth field observations were conducted at Tainan Park, documenting the behaviors of 12 distinct user groups/individuals. These ranged from children playing and elderly individuals playing cards to students waiting for the bus. These observations captured nuanced stories and interactions within the park environment.

*   **Source**: `data/field_study.csv`

### 2.3. Empathy Mapping

To understand the psychology behind the observed behaviors, an **Empathy Map** was created. This helped synthesize the field observations (what users `Say`, `Do`, `Think`, and `Feel`). It revealed that even when users are quietly on their phones, they are in a complex transitional state, experiencing a mix of waiting, fatigue, and mild anxiety, rather than simply killing time.

*   **Source**: `data/research_process.pdf`

### 2.4. Data Analysis: User Behavior Clustering

The qualitative observations were quantified across 9 behavioral and psychological dimensions (e.g., `Negative vs Positive Emotion`, `Alone vs Group`, `Distracted vs Focused`). Using the DBSCAN clustering algorithm, four distinct user groups and two outliers were identified:

*   **Group A (Cluster 0)**: **High-Frequency Movers** (e.g., joggers, kids on bikes).
*   **Group B (Cluster 1)**: **Closed Social Groups** (e.g., couples, friends).
*   **Group C (Cluster 2)**: **Stationary Observers** (e.g., parents watching kids).
*   **Group D (Cluster 3)**: **Territorial Occupants** (e.g., elderly regulars).
*   **Outliers**: Anxious bus-waiter and a child playing without tech.

This analysis revealed a **"Social Void"**: a gap where certain users are psychologically isolated despite being in a public space, leading to the core design concept of a "Social Intensity Slider".

*   **Source**: `data/user_behavior_dimension_analysis.ipynb`, `data/user_behavior_dimension_analysis_summary.md`

---

## 3. Phase 2: Problem Convergence & Persona Definition

This phase synthesized the research into a concrete user definition and problem statement.

### 3.1. User Persona: 楊子萱 (Yang Zixuan)

The research culminated in the creation of a detailed user persona.

*   **Who**: Yang Zixuan, a 16-year-old high school student who is shy, slow-to-warm-up, and an observer.
*   **Core Problem**: She feels like an outsider in her school's solidified social circles and desires to make connections, but finds typical social events (large, loud, competitive) to be high-pressure and overwhelming.
*   **Needs**: She needs a way to find safe, low-stakes social opportunities that allow for natural, non-awkward interaction and a gradual warming-up period.
*   **Source**: `data/user_persona.md`

### 3.2. Stakeholder Analysis

A stakeholder map was created with Zixuan at the center to visualize the forces acting upon her. It revealed that her problem is not just a lack of friends, but a complex web of influences including academic pressure (cram school), digital distraction (social media algorithms), and environmental anxiety (feeling watched by strangers in the park).

*   **Source**: `data/stakeholder_map.md`

### 3.3. Defining the Core Problem

The problem was further broken down using two key frameworks:

*   **Jobs-To-Be-Done (JTBD)**: Identified key "jobs" the user would "hire" the platform for, such as "Seek low-pressure participation," "Break out of existing social circles," and "Preview the atmosphere of an event to build confidence."
*   **How Might We (HMW)**: Framed the design challenges into actionable questions, like "How might we... provide a sense of privacy for users in a public space?" and "How might we... let users reserve a specific, semi-private space without direct social interaction?"

*   **Source**: `data/jobs_to_be_done.md`, `data/how_might_we.csv`

---

## 4. Phase 3: Solution Exploration & Prototyping

This phase focused on designing and building a solution based on the research.

### 4.1. Detailed User Story & Storyboarding

A detailed, visual user story was created to map out every step of Yang Zixuan's journey, from motivation to resolution.

1.  **The Problem**: The story begins with Zixuan in her room, feeling isolated as she sees her old friends enjoying their new high school lives on social media. She wants to make new friends but feels the social circles at her new school are already solidified and intimidating.
2.  **Failed Attempt**: She considers joining a school club but is overwhelmed by the posters on the bulletin board. The lack of information about the members and atmosphere makes her anxious about choosing the wrong one, so she gives up.
3.  **Discovery**: After school, she spots a small, unobtrusive poster for the "Tainan Park Social Platform." Intrigued by the promise of low-pressure events, she scans the QR code.
4.  **First Interaction**: The app's welcome screen leads her to the "Explore Activities" page. She is initially overwhelmed by the options.
5.  **Filtering**: She notices the detailed filters and first looks at a high-interaction "team challenge" event, but the description makes it clear it's for outgoing people, which makes her feel it's not for her. She then uses the "Social Intensity" and "Group Size" sliders to narrow the options to quiet, small-group activities.
6.  **Finding the Right Fit**: The filters lead her to a "Sunset Walk + Phone Photography" event. The description is welcoming to beginners, and she feels reassured.
7.  **Joining**: Before joining, she is prompted to create a simple profile. After filling it out, she successfully joins the event.
8.  **Post-Registration**: She can see the event in her "My Activities" tab, which gives her a sense of confirmation and reduces her anxiety.
9.  **Pre-Event Anxiety & Reassurance**: On the day of the event, she feels anxious and hesitates. However, she receives a notification from the app with a reassuring message from the host and other participants, which gives her the final push to go.
10. **The Event**: She is warmly welcomed at the meeting spot. During the walk, the shared activity of taking photos provides a natural topic of conversation, allowing her to connect with others without pressure.
11. **The Outcome**: The story concludes with her at a picnic with her new friends, looking at the photos they took. She feels a sense of belonging, having finally found a group where she can be herself.

This detailed storyboard illustrates exactly how the platform's features (filters, detailed descriptions, profile creation, notifications) work together to guide a shy user through the entire process of making new friends.

*   **Source**: `data/user_story.pdf`, `data/design_scenario.md`

### 4.2. MVP Prototype (The Website)

A functional prototype of the platform was developed as a web application. Key features include:

*   **Activities Page**: The core discovery feature, allowing users to filter events by keyword, **social intensity**, group size, date, and interest tags.
*   **Host Page**: A form for users to create and submit their own activities.
*   **Profile Page**: A detailed user profile that goes beyond basic info to include personality sliders (e.g., "Observational vs. Proactive," "Slow-paced vs. Fast-paced"), "Ask me about" tags, and privacy settings for personal information.
*   **My Activities Page**: A dashboard for users to manage the events they have joined or are hosting. It includes a multi-step verification status tracker for hosted events (`Pending` -> `Reviewing` -> `Verified`).
*   **Friends Page**: A simple CRM for managing connections made on the platform, including private notes and a chat function.
*   **Safety Page**: Provides a park safety map, emergency contact info, and "escape scripts" for users who feel uncomfortable and want to leave an event politely.
*   **Notifications Page**: Centralizes all updates, including new participants, comments, and activity reminders.

*   **Source**: Files under `data/website/`

---

## 5. Phase 4: Testing & Iteration

The final phase involved testing the design concepts and identifying areas for improvement.

### 5.1. Persona Verification (Role-playing)

A series of interviews were conducted where participants responded from the perspective of the Yang Zixuan persona. The feedback validated several core design assumptions:

*   **Aversion to Heat**: Participants confirmed they would not attend an outdoor event in Tainan during the day without A/C, validating the focus on evening/sunset activities.
*   **Fear of Initiating**: Participants expressed anxiety about hosting events, validating the need for features like "start only when enough people join."
*   **Value of Low-Stakes Activities**: The idea of activities where the fun is in the task itself (e.g., photography), rather than forced socialization, was highly resonant.
*   **Source**: `data/persona_verification.md`

### 5.2. Modification Report

Based on the verification process, a report was compiled with proposals for the next iteration of the platform (v2.0). Key recommendations include:

*   **Enhanced Trust & Safety**: Implement a student identity verification system.
*   **Richer Profiles**: Add more personal and interest-based fields to help users find matches.
*   **Improved Hosting Features**: Allow hosts to set a *minimum* number of participants for an event to proceed.
*   **Better Onboarding & Guidance**: Create explicit guides for new users on how to participate and for new hosts on how to lead an activity. Add emergency contact numbers directly to event pages.

*   **Source**: `data/modification_report_based_on_verification.md`
