# Project Plan: StudyPilot

## 1. Find a direction
Real need: Most students procrastinate on large assignments because they feel overwhelmed and don't know where to start. My own experience of staying up late to finish big projects inspired me to create a tool that breaks down big tasks into small, manageable daily steps.

## 2. Research
Key resources and reusable materials:
- Existing tools like Todoist and Notion for task management.
- AI APIs (e.g., OpenAI) for task breakdown.
- Front-end frameworks for building the simple interface (e.g., basic HTML/JS or React).
Links:
- [ai-task-manager](https://github.com/MAbdullaha07/ai-task-manager): A full-stack example of using GPT API to break down and assign tasks. Useful for backend logic reference.
- [ai-project-planner](https://github.com/ayauho/ai-project-planner): Shows how to decompose projects into tasks and visualize them. Good reference for future UI.
- [study-pilot-ai](https://github.com/ZZZ234234234/study-pilot-ai): A local-first AI study assistant that generates study plans. Relevant to our core "study plan" feature.
- [StudyPilot (Queena34)](https://github.com/Queena34/StudyPilot): Generates daily checkable tasks based on weak points and exam dates. Directly mirrors our goal of breaking down big assignments.
- [OpenAI Function Calling Docs](https://platform.openai.com/docs/guides/function-calling): The official documentation for structured output. We can use this to generate a task list from a user's input.
Keep key links here and explain what you learned and can use.

## 3. Narrow down
Problem: Students don't need another complex project management tool; they need a simple way to turn "Write a paper" into "1. Find 3 sources, 2. Write an outline".
Specific situation: A student has a 2-week deadline for a history essay. They open StudyPilot, type in the essay topic, and the AI generates a 10-step daily checklist. The scope is narrowed down to just: input text -> AI output steps -> check off steps.

## 4. Propose a solution
Why it solves the problem: It reduces cognitive load. It doesn't just list tasks, it tells the student exactly what to do next, eliminating the decision paralysis.
Value compared to existing approaches: Traditional tools require the student to manually plan everything. StudyPilot uses AI to automatically generate the plan. Assumption: We assume students are willing to spend 30 seconds typing their assignment to get an instant plan.

## 5. Define a minimal workflow
What stays in the first version: A simple text input box, a button to submit, and a hardcoded list of steps (or a very basic AI API call) that appears on the screen.
What can wait: User accounts, database storage, progress bars, and sharing features.
Simplest complete workflow: User types "Math Homework" -> presses Enter -> sees a list of 3 simple steps.

## 6. Build it
To be added

## 7. Feedback and iteration
To be added
