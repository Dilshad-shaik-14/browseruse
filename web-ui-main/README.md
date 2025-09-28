<<<<<<< HEAD
=======
Problem Statement – Web Navigator AI Agent

Title:
BrowserUse

Description:
Finding information on the web is often repetitive and time-consuming. Users need to perform searches, open multiple websites, extract information, or complete tasks like form filling manually.

Problem:
Manual web navigation for tasks like research, data collection, or monitoring websites takes significant time and effort, especially for repetitive or multi-step processes.

Proposed Solution:
Develop a Web Navigator AI Agent that can autonomously perform web tasks based on natural language instructions. The agent can:

Search for information on the web

Open multiple websites

Extract or summarize relevant content

Simulate user interactions like clicking links or filling forms

Goal:
Create a minimal prototype where a user inputs a task (in plain English), and the AI agent demonstrates step-by-step autonomous navigation or simulation of web tasks.

Impact:

Saves time for repetitive online tasks

Helps researchers, students, and professionals quickly gather information

Provides a foundation for intelligent autonomous agents that can interact with the web
Frontend

React 19: The user interface is built using React 19, a popular JavaScript library for building user interfaces.

Next.js 15 (App Router): Next.js 15 is used for server-side rendering and routing, enhancing the performance and scalability of the application.

TypeScript 2: TypeScript 2 provides static typing, improving code quality and maintainability.

Tailwind CSS v4: Tailwind CSS v4 is employed for utility-first CSS styling, allowing for rapid and responsive design.

Radix UI Primitives: Radix UI Primitives offer low-level UI components that are accessible and customizable.

Backend

Python: The backend is developed in Python, leveraging its simplicity and readability.

Playwright: Playwright is used for browser automation, enabling the AI agent to interact with web pages programmatically.

uvicorn: uvicorn serves as the ASGI server for running the application, providing high-performance asynchronous capabilities.

AI Integration

OpenAI GPT-3.5: The application integrates with OpenAI's GPT-3.5 model to process natural language instructions and generate responses.

LangChain: LangChain is utilized to manage and chain together multiple language model calls, facilitating complex workflows.

Contribution of team making this big project

1. Frontend Developer

Responsibilities:

Build and style the UI for the agent

Implement input boxes for user instructions

Display agent responses and navigation steps

Integrate frontend with backend API
Technologies: React, Next.js, TypeScript, Tailwind CSS, Radix UI
Deliverables: Fully functional, responsive UI

2. Backend Developer

Responsibilities:

Build the backend API to process instructions

Handle routing, data processing, and communication with AI model

Manage sessions and agent state

Implement logging of actions if needed
Technologies: Python, FastAPI/Flask, uvicorn
Deliverables: Stable API endpoints connected to frontend

3. AI / Language Model Integration

Responsibilities:

Connect to OpenAI GPT-3.5 or Hugging Face model

Parse natural language instructions and generate actionable steps

Implement LangChain or workflow chaining for multi-step tasks

Test AI responses and improve prompt design
Technologies: Python, OpenAI API, LangChain
Deliverables: Functional AI agent capable of generating task steps

4. Browser Automation / Scraping Engineer

Responsibilities:

Implement browser automation with Playwright or Puppeteer

Simulate navigation, clicks, and scraping web content

Ensure agent actions are accurate and reproducible

Handle edge cases like login pages or dynamic content
Technologies: Playwright, Puppeteer, Python
Deliverables: Reliable web automation layer integrated with AI

5. Designer / Presentation (PPT & Demo)

Responsibilities:

Design project logo, UI mockups, or color themes

Prepare the hackathon presentation slides

Create demo flow diagrams or screenshots for submission

Ensure the project looks polished for judges

Tools: Canva
>>>>>>> 6d8019359d2c1dddde360bec5ac62c588f542645
