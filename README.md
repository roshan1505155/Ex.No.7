# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Objectives:
1. To understand the concept of prompt engineering in AI tools.
2. To build a personal productivity assistant capable of managing daily tasks and schedules.
3. To simulate natural language interactions with AI.
4. To explore how prompt complexity affects output quality.
5. To foster creativity and problem-solving using LLMs in real-life tasks.

# Introduction

In the era of Artificial Intelligence, Large Language Models (LLMs) such as ChatGPT have revolutionized the way humans interact with machines.
These models understand and generate human-like text, making them capable of performing tasks like writing, scheduling, organizing, planning, and answering queries through simple conversational prompts.

A prompt-based application uses these models to perform functions that traditionally require complex programming. The key lies in designing effective prompts that guide the model to respond accurately and meaningfully.

This experiment demonstrates how a personal productivity assistant can be built using prompts — evolving from basic commands to advanced adaptive interactions.

# Aim:
To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 
ChatGPT (GPT-5 or equivalent LLM)
Python / Flask (optional – for interface)
Command-line or Chat interface (for testing)
Google Sheets / Notion / Drive (for task tracking, optional)

# Explanation: 
Prompt-based systems rely on the clarity and specificity of instructions given to the AI.
If the prompt is vague, the model gives generic results. But with detailed, contextual prompts, it produces organized, actionable, and intelligent responses.
This lab shows how ChatGPT can act as:
A Daily Task Manager
A Smart Scheduler
A Wellness Advisor
A Personal Assistant that adapts to user behavior
We progressively improve prompts to achieve better control and richer outputs.

Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.

# Prompt Design and Outputs

Prompt 1 – Basic Prompt
Prompt:
“Create a to-do list for me with three tasks for today.”
Output:
Here’s your to-do list for today:
Complete your project documentation.
Review your lecture notes for tomorrow’s class.
Call your mom in the evening.

# Prompt 2 – Intermediate Prompt

Prompt:
“Design a daily task manager that helps me add, remove, and prioritize tasks. Also, remind me of pending tasks at the end of the day.”
Output:
Daily Task Manager Features:
Add Task: You can say, “Add task: Finish AI Lab Record by 5 PM.”
Remove Task: “Remove completed task: Finish AI Lab Record.”
Set Priority: Mark tasks as High, Medium, or Low.
End-of-Day Summary: Automatically shows pending tasks at 9 PM.

Prompt 3 – Advanced Prompt

Prompt:
“Design a personal productivity assistant that can manage daily tasks, schedule reminders, suggest wellness tips, and adapt to my preferences.”
Output:
Personal Productivity Assistant Features
1. Task Management:
Add, delete, and view tasks using natural language.
Example: “Remind me to call my friend at 6 PM.”
The assistant organizes them by priority and date.
2. Smart Scheduler:
Schedule events automatically based on free time.
Detects overlapping appointments and suggests alternatives.
Example: “You already have a meeting at 6 PM. Shall I reschedule the call to 7 PM?”
3. Wellness Advisor:
Suggests health tips based on user activity and time of day.
Example: “You’ve been studying for 2 hours. Take a 10-minute walk.”
4. Adaptive Memory:
Learns from user habits (e.g., prefers evening reminders).

Example: “You usually study at 7 PM. Shall I set today’s study reminder?”
Sample Simulation:
User: Add task: Finish project at 4 PM (High Priority).
Assistant: Task added successfully! “Finish project at 4 PM” marked as High Priority.
User: Show pending tasks.
Assistant: You have 2 pending tasks:
1. Finish project – High Priority
2. Revise Python concepts – Medium Priority

# Step-by-Step Procedure

Identify Needs:
Define what the assistant must handle (tasks, wellness, reminders).

Build Prompts:
Start from simple (“Add a reminder”) to complex (“Design a productivity system with adaptive learning”).

Interact and Test:
Use ChatGPT chat or command line to simulate user interactions.

Refine Prompts:
Rephrase until the assistant gives structured, relevant, and adaptive responses.

Evaluate Outputs:
Compare results for each prompt and observe improvement with better context.



# Observation:
The model starts showing structure, categories, and reminders. Interaction is now more dynamic.
Simple and direct. The model generates tasks but lacks time management or prioritization.

# EXPECTED OUTPUT: 
| Feature         | Description                        | Example Output                                                    |
| --------------- | ---------------------------------- | ----------------------------------------------------------------- |
| Task Manager    | Adds and tracks user tasks         | “Added: Finish report at 5 PM.”                                   |
| Smart Scheduler | Manages time and detects conflicts | “You have free time at 3 PM. Would you like to add a break?”      |
| Wellness Tips   | Generates daily health suggestions | “Take deep breaths for 1 minute to relax.”                        |
| Adaptive Memory | Learns and customizes              | “You prefer morning study sessions — shall I remind you at 9 AM?” |

# Output (Example Response by LLM):
<img width="1023" height="352" alt="Screenshot 2025-10-09 090958" src="https://github.com/user-attachments/assets/f34a7814-0bb3-4f2b-a350-4b9a35bad1d6" />

# Sample Interaction Summary

User: “Add ‘Complete assignment’ at 5 PM.”
Assistant: “Added task: ‘Complete assignment’ at 5 PM.”

User: “Show pending tasks.”
Assistant: “Pending: Complete assignment, Study AI, Take walk.”

User: “Give a wellness tip.”
Assistant: “Stretch your legs for a minute and drink water.”

User: “What’s my evening plan?”
Assistant: “At 5 PM – Complete assignment, 7 PM – Study AI, 8 PM – Walk.”

# Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.



# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
