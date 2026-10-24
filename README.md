CULTUREPULSE AI

Cultural Intelligence for the Real World

CULTUREPULSE AI is an AI-powered cultural intelligence platform that helps teams turn cultural affinity insights into more relevant audience strategies, brand comparisons, and campaign concepts.

Live Demo: https://culturepulse-ai-agen-3522.bolt.host
GitHub Repository: https://github.com/hasan735392814-pixel/culturepulse-ai

The Problem

Traditional audience research often relies on broad demographics and assumptions. These approaches can miss the cultural interests, affinities, and connections that influence what audiences discover, enjoy, and engage with.

Our Solution

CULTUREPULSE AI provides an interactive workspace for exploring cultural intelligence and translating insights into actionable ideas.

Key Features

- Cultural Analysis: Explore cultural affinity insights for audience and brand research.
- Entity Search: Discover relevant entities across supported cultural categories.
- Side-by-Side Comparisons: Compare entities to identify useful similarities and differences.
- Campaign Studio: Turn research insights into campaign concepts and creative directions.
- Saved Reports: Keep track of research and revisit previous analyses.
- AI-Assisted Interpretation: Present findings with contextual explanations to support decision-making.

Powered by Qloo

The platform integrates with the Qloo API to retrieve cultural intelligence insights. Qloo-derived data supports the analysis and comparison experience, while the application translates those insights into a more accessible workflow.

API credentials are handled server-side and should never be exposed in client-side code or committed to the repository.

Technology Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Supabase Edge Functions
- Qloo API

Architecture

The frontend provides the research interface and analysis workflows. Supabase Edge Functions act as the server-side integration layer for Qloo API requests, helping keep sensitive API credentials out of the browser.

Getting Started

Prerequisites

- Node.js and npm
- A Supabase project
- A valid Qloo API key

Installation

npm install

Create a local environment configuration based on ".env.example", and configure the required public application settings for your Supabase project.

Configure the Qloo API key as a server-side secret for the appropriate Supabase Edge Functions. Never place private API keys in frontend environment variables or commit them to Git.

Run Locally

npm run dev

Production Build

npm run build

Deploy the frontend using a compatible static hosting provider and deploy the Supabase Edge Functions to your configured Supabase project.

Refer to the project configuration and function code for the exact environment variables and deployment requirements.

Responsible Use

Cultural affinity insights are intended to support research and creative decision-making. They should not be treated as definitive statements about individuals or used as substitutes for direct audience research and validation.

Hackathon Project

CULTUREPULSE AI was developed as a project for the Qloo Agentic Hackathon, exploring how cultural intelligence can help people make better-informed creative and audience decisions.

License

This project is released under the MIT License. See the "LICENSE" file for details.
