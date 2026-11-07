# MockMate – AI Interview Platform

MockMate is an AI-powered interview platform that enables candidates to experience personalized, real-time technical interviews based on their skills, technology stack, and preferences. It combines conversational AI, voice-based interaction, and intelligent interview management to create a more realistic interview preparation experience.

## Features

- **AI-Powered Interviewer:** Conducts interactive technical interviews using an AI-driven voice assistant.
- **Personalized Interviews:** Generates interview experiences based on the candidate's technology stack, skills, and preferences.
- **Pre-Interview Customization:** Allows candidates to communicate with the AI interviewer before starting an interview to configure their interview experience.
- **Real-Time Voice Interaction:** Enables natural voice-based conversations between candidates and the AI interviewer using Vapi.
- **Live Speech-to-Text:** Generates subtitles by converting the candidate's spoken responses into text.
- **Conversational Edge-Case Handling:** Handles prolonged pauses, response delays, and unexpected interaction scenarios to maintain a smooth conversation.
- **Interview Management:** Provides interview listings, dashboards, interview details, and feedback reports.
- **AI-Generated Feedback:** Evaluates interview responses and generates performance scores and feedback for candidates.

## Architecture

The application follows a modular architecture that separates authentication, interview experience, interview services, external integrations, and shared UI components.

![MockMate Architecture](./architecture.png)

### Architecture Components

- **Identity & Sessions:** Handles user authentication and session management through Firebase Authentication.
- **Interview Experience:** Manages interview listings, dashboards, interview details, feedback reports, and the voice interview agent.
- **Interview Services:** Handles interview generation, interviewer configuration, interview execution, and feedback generation.
- **External Integrations:** Connects Firebase services, Vapi voice infrastructure, Google AI services, and Firestore.
- **Shared Presentation:** Provides reusable interview cards, technology icons, form components, and UI primitives.

## Tech Stack

**Frontend**
- Next.js
- React.js
- TypeScript
- Tailwind CSS

**AI & Voice Integration**
- Vapi AI – Real-time voice assistant and conversational interaction
- Google AI SDK – AI model integration
- AI SDK – AI-powered generation workflows

**Backend & Database**
- Firebase Authentication
- Firebase Admin SDK
- Cloud Firestore

**Libraries & Utilities**
- React Hook Form
- Zod
- Radix UI
- Lucide React
- Day.js
- Sonner

## Core Objective

MockMate aims to make technical interview preparation more interactive, personalized, and realistic by replacing static question-based practice with an adaptive, AI-driven voice interview experience.