# FixFlow AI

FixFlow AI is a platform designed to help agencies and freelancers convert client project briefs into professional proposals, while matching skilled talent with the right project opportunities.

This repository is publicly available to offer developers who are planning open-source or project contributions an insight into what FixFlow AI is and how they can contribute.

If you are interested in contributing, you must first send an email to **ai.fixflow.helpdesk@gmail.com**. In your email, please clearly describe:
- Why you want to contribute to FixFlow AI.
- How you plan to contribute (the specific areas, features, or fixes you want to work on).

Based on your proposal, the project maintainers will coordinate with you on how to proceed.

## What is FixFlow AI?

FixFlow AI is a workspace that takes raw client project briefs and automatically turns them into structured proposals. Instead of spending hours or days analyzing requirements, writing documents, and estimating costs, users can generate a complete proposal draft quickly, refine it, and share it directly with clients.

### Our Main Motive

The core purpose of FixFlow AI is to bridge the gap between freelancers and clients. The platform helps freelancers find projects that match their specific skills and experience. At the same time, it ensures clients have access to qualified freelancers who possess the exact knowledge and capabilities required for the job, allowing freelancers to submit competitive and accurate bids.

## The Problem It Solves

Creating proposals for new projects is a time-consuming and expensive process for service providers. A typical proposal workflow requires:
- Carefully reading long and often unstructured client briefs.
- Manually identifying key features, timelines, and risks.
- Estimating the effort and cost for each part of the project.
- Writing, formatting, and proofreading multi-page documents.

This manual process can take anywhere from several hours to a few days. During this time, clients may lose interest or choose a competitor who responds faster. FixFlow AI solves this by automating the initial analysis and drafting stages, reducing the turnaround time to minutes so you can send proposals faster and win more business.

## Targeted Customers

FixFlow AI is built for:
- Professional Services Agencies: Development shops, design studios, and marketing agencies handling mid-to-large-scale projects.
- Freelancers and Independent Contractors: Consultants and developers who need to quickly pitch and win new clients without overhead.
- Project and Account Managers: Teams inside agencies who need a standardized tool to prepare proposals and keep client communications organized.

## Key Features

- Skill-Based Matching: Connects freelancers to clients based on matching skillsets and project needs.
- Brief Uploads: Paste project text or upload document briefs to start.
- Proposal Generation: Generate draft details including features, estimated timelines, effort distributions, and risk mitigations.
- Revisions and Refinement: Edit sections, ask for changes, and keep track of different versions.
- Client Share Portal: Share a secure web link with clients where they can review the proposal and leave feedback.
- Team Workspace: Collaborate with your team members on proposals, manage comments, and see who is actively editing.

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm (version 9 or higher)
- MongoDB database (local or MongoDB Atlas)

### Setup

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Suvam-paul145/FixFlowAI.git
   cd FixFlowAI
   ```

2. Install the frontend dependencies:
   ```bash
   npm install
   ```

3. Install the backend dependencies:
   ```bash
   cd backend
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the root directory and the `backend` directory based on the configuration requirements.
   - Configure your database connection strings and necessary service keys.

5. Run the development environment:
   - Start the backend API:
     ```bash
     cd backend
     npm run dev
     ```
   - Start the frontend application:
     ```bash
     cd ..
     npm run dev
     ```

## License

This project is licensed under the MIT License. See the LICENSE file for details.