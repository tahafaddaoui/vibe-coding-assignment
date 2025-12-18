# Experience Documentation: Using a Vibe Coding Tool

---

## Tool Selection Justification

I chose Replit Agent as my vibe coding tool because it provides an integrated environment where application generation, execution, and testing occur in a single platform. Unlike traditional IDE-based assistants, Replit Agent allows developers to describe an application in natural language and receive a fully structured, runnable project almost instantly. This made it especially suitable for a course assignment that emphasizes functionality, completeness, and ease of demonstration.

Another reason for choosing Replit Agent was its accessibility and beginner-friendly workflow. The tool handles project scaffolding, file organization, and environment configuration automatically, which reduces setup complexity. For a Todo List application that requires persistence and interactivity, Replit Agent offered an efficient way to focus on logic and user experience rather than tooling overhead.

---

## Development Process

The development process began by prompting Replit Agent with a high-level description of the application requirements, including task creation, editing, deletion, and persistence using local storage. The agent generated the initial HTML, CSS, and JavaScript files, providing a complete baseline implementation. This initial output was functional but basic in terms of styling and interaction design.

I then iteratively refined the application through follow-up prompts. For example, I requested inline task editing, visual indicators for completed tasks, and improved code readability. Each prompt resulted in targeted changes across multiple files, demonstrating the agent’s awareness of the full project context. This iterative process significantly reduced the amount of manual coding required.

In total, it took approximately four to five iterations to reach a stable and fully functional version of the application. After each iteration, I tested the app in the browser, reviewed the generated code, and requested adjustments where necessary. The feedback loop between prompting, reviewing, and testing was fast and efficient compared to traditional development workflows.

---

## Challenges and Solutions

One of the main challenges encountered was maintaining code clarity and structure. While Replit Agent produced working code quickly, some functions were initially longer than necessary or lacked clear naming conventions. To address this, I manually refactored parts of the JavaScript file and requested the agent to simplify specific logic blocks.

Another challenge involved ensuring reliable data persistence. Although the agent implemented localStorage correctly, edge cases such as empty input handling and task ID management required additional attention. I manually added validation checks and improved error handling to make the application more robust.

The AI tool was helpful in identifying logical patterns and generating boilerplate code, but it was not always optimal in terms of best practices. This required human judgment to review, correct, and improve the final implementation. This experience highlighted the importance of developer oversight when using vibe coding tools.

---

## Reflection

One of the most surprising aspects of vibe coding was how effectively the tool could translate abstract requirements into a working application. Instead of focusing on individual lines of code, the development process felt more like directing a collaborator. This shifted my role from writing code to reviewing, guiding, and refining it.

Vibe coding significantly changed my development workflow by reducing setup time and repetitive tasks. It allowed me to experiment more freely and iterate faster, especially during the early stages of development. However, it also emphasized the need for strong foundational knowledge to evaluate and improve AI-generated code.

I would use this tool for future projects, particularly for prototyping, learning new frameworks, or building minimum viable products. As this technology evolves, it is likely to have a major impact on software development by increasing productivity and lowering entry barriers. However, it will also require developers to focus more on system design, code review, and ethical responsibility rather than manual implementation alone.
