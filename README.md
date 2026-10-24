# AI-Based Smart Study Planner for Students

## Description
A responsive browser-based study planning prototype that helps students organize subjects, topics, deadlines, and estimated study durations. It suggests a study order using priority, difficulty, and deadline information, tracks completion, displays productivity statistics, and includes a Pomodoro focus timer. Tasks are saved in browser local storage.

## How to run
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Add a task with a subject, topic, target date, duration, priority, and difficulty.
4. Review the suggested plan and mark tasks complete as you finish them.
5. Use the 25-minute focus timer.

## Features
- Add and delete study tasks
- Priority and difficulty-based suggested order
- Completion dashboard and planned study-hour total
- Pomodoro timer
- Responsive layout
- Local storage persistence

## Technology
HTML5, CSS3, JavaScript, localStorage.

## Scope note
The schedule suggestion uses rule-based logic. It does not connect to an external AI service or claim to be a trained AI model. Possible extensions include calendar integration, notifications, user accounts, and an AI API.

## Testing checklist
Add a task; confirm it appears in the task list and suggested plan; mark it complete and verify dashboard updates; delete a task; refresh to verify persistence; test timer start, pause, and reset.
