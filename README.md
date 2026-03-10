# Englishour

**Englishour** is an English language learning platform built with **React.js** for the frontend and **Node.js** for the backend. The project was developed as part of the **Software Development Sessional course during the 6th semester**.  

🎥 **YouTube Demo:** [Watch the demo here](https://youtu.be/122Pwv6Ht6I)





The platform consists of two main components:

- **Admin (Moderator) Module**
- **Learner Module**

---

# Admin (Moderator) Module Features

## Topic and Level Management

Admins or moderators can create learning **topics** and organize them into different **difficulty levels**.

## Content Management

Moderators can add **exercises and tutorial notes** under each level either:

- **Manually**
- **By uploading files**

Exercises uploaded by one moderator must be **reviewed and approved by other moderators** before publication. A **notification system** informs moderators about pending approvals.

## Content Review and Approval

Moderators can **preview and review newly added content**. Once a piece of content receives a required number of approvals from other moderators, it becomes **published on the platform**.

## Statistics Dashboard

Admins can view multiple platform statistics:

### Exercise Statistics

- Percentage of students who attempted an exercise
- Success rate
- Ability to adjust difficulty levels based on performance

### Topic Statistics

- Number of exercises in each topic
- Attempt rate per topic
- Success rate for each topic

### Platform Statistics

- Exercises added by moderators
- Moderator ratings
- Number of students joined
- Student activity levels
- Success rates across different difficulty levels

## Recent Activity

Displays recently added content by moderators and their **approval status** (pending or approved).

---

# Learner Module Features

## Exercise Completion

Students can complete **exercises and tests** from different topics and tasks uploaded by moderators. Results are shown immediately after completing an exercise.

## Tutorials and Notes

Each task includes learning materials such as **tutorials and notes** to support the exercises.

## Notification System

Students receive notifications whenever **new topics or exercises** are added to the platform.

## Moderator Rating

Students can see which **moderator uploaded content** and provide **ratings** for moderators.

## Recent Activity

Students can view a log of their activity, including:

- Exercise completion
- Level progression
- Learning history








# Installation

1. Create a .env file in the root folder.
Add the following:
  POSTGRES_URI=<<Your database uri>>
  sample: POSTGRES_URI=postgres://user:pass@example.com:5432/dbname
 
 2. run "npm install"
 3. run "npm run dev"
