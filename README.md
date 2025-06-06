[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18914939&assignment_repo_type=AssignmentRepo)
# SE_Day1
Software Engineering Day1 Assignment

#Part 1: Introduction to Software Engineering

Explain what software engineering is and discuss its importance in the technology industry.

Software Engineering is the backbone of modern day technology, which ensures that software is not just functional but also secure, scalable, and sustainable. Without it, we’d have buggy apps, vulnerable systems, and slower innovation.It is the systematic application of engineering principles to write instructions(codes) for computers,build apps, games, and websites that make life easier


Identify and describe at least three key milestones in the evolution of software engineering.

1. Mastering Complexity – The Rise of Object-Oriented Programming (OOP) (1970s–1980s):As software grew more complex, OOP helped by organizing code into reusable "objects" with data and behavior. This made software easier to build, understand, and maintain.
2. Mastering Process – The Capability Maturity Model (CMM) (1980s–1990s):To make software development more predictable and efficient, CMM introduced a step-by-step model to improve processes. It helped companies move from chaotic coding to well-organized development.
3. Mastering Complexity & Process – DevOps and Continuous Delivery (2010s–Present):DevOps combines development and IT operations, using automation to speed up coding, testing, and deployment. This makes software more reliable and faster to deliver.


List and briefly explain the phases of the Software Development Life Cycle
Software Development Life  Cycle
1.Planning & Requirement Analysis – Define what to build and why. Gather stakeholder needs, feasibility studies are conducted to ensure product meets demand , and create an SRS document. 
2.System Design – Decide how to build it. Plan architecture, choose the tech stack, and create design documents (UML, flowcharts).This is also the stage for prototyping
3.Implementation (Coding) – Write code following standards (SOLID principles, using version control (Git). 
4.Testing – Ensure quality through:
Unit Test: This tests individual methods and functions of each components
Integration test: This test verifies the compatibility of various components or modules 
Performance testing:These are formal tests that verifies if a system meets and satisfies business requirements
5.Deployment – Release the product using CI/CD pipelines, containerization (Docker), or firmware flashing.
6.Maintenance & Evolution – Fix bugs, feature enhancement,adding new features and plan for obsolescence. 


Compare and contrast the Waterfall and Agile methodologies. Provide examples of scenarios where each would be appropriate.
Waterfall methodology: Linear, phase-gated process (Requirements → Design → Implementation → Testing → Maintenance)
For water fall methodology,it has a rigid structure,reviews only come at the end of the cycle and testing is done at the end of the development process
It is recommended to use Water fall methodology  when:
✓ Requirements are stable and well-defined
✓ Projects have fixed budgets/timelines (e.g., government contracts)
✓ Hardware-software integration is required 



Agile: Iterative, cyclical process (Plan → Develop → Test → Review → Repeat)
Agile methodology makes use of an adaptive approach,continuous iterations, and has high flexibility
It is recommended to use Agile methodology when:
✓ Requirements are expected to evolve over time
✓ Rapid prototyping is valuable
✓ Customer collaboration is feasible


Describe the roles and responsibilities of a Software Developer, a Quality Assurance Engineer, and a Project Manager in a software engineering team.
The folowing are the reponsibilities of a Software developer,a Quality Assurance Engineer, and a Project Manager in a software engineering team.
1. Software Developer:
**Core Role:** Design, build, and maintain software systems.  

Responsibilities:  
- Write clean, efficient code following best practices  
- Develop new features and fix bugs  
- Collaborate with QA to resolve defects    
- Optimize performance and scalability  
- Maintain documentation (code comments, technical specs)  

2. Quality Assurance (QA) Engineer: 
Core Role: Ensure software reliability and user satisfaction.  

Responsibilities:
- Design test plans and test cases  
- Execute manual and automated tests  
- Report and track bugs (using tools like JIRA)  
- Perform regression testing  
- Validate security and performance  
- Ensures that products meet with compliance requirements.  


3. Project Manager (PM)
Core Role: Deliver projects on time and within budget.  

Responsibilities:  
- Define project scope and timelines  
- Allocate tasks to team members  
- Track progress (using Agile/Waterfall methods)  
- Manage risks and resolve blockers  
- Communicate with stakeholders  
- Ensure team collaboration (stand-ups, retrospectives)  
- Balance quality, speed, and resources


Discuss the importance of Integrated Development Environments (IDEs) and Version Control Systems (VCS) in the software development process. Give examples of each.
. Integrated Development Environments (IDEs) 
Purpose: Streamline coding, debugging, and testing in a unified interface.  

Key Benefits of working with an IDE
✔ Code Efficiency – Syntax highlighting, autocompletion, and templates speed up development.  
✔ Debugging Tools – Built-in debuggers help identify errors quickly.  
✔ Project Management– Organize files, dependencies, and build configurations.  
✔ Integration – Supports plugins for version control, testing, and deployment.  
Example of IDE is PyCharm** – Optimized for Python (AI/ML, Django).  


2. Version Control Systems (VCS)  
Purpose: Track code changes, enable collaboration, and prevent data loss.  

Key Benefits  of workimg with a VCS  
✔ Collaboration – Multiple developers can work on the same codebase (e.g., via branching).  
✔ History & Rollback – Revert to previous versions if bugs arise.  
✔ CI/CD Integration – Automate testing/deployment (e.g., GitHub Actions).  

An example of VCS is Git (with GitHub/GitLab) – Industry standard for open-source and commercial projects.  
IDEs and VCS are foundational to modern software engineering, ensuring efficiency, collaboration, and reliabilitty, whether in web apps, AI systems, or embedded mechatronics projects.  


What are some common challenges faced by software engineers? Provide strategies to overcome these challenges.
Software engineers face numerous hurdles during development. Below are key challenges with actionable strategies to overcome them:
1. Changing Requirements:Clients/stakeholders frequently update specs mid-project, causing scope creep.
Solutions:
Adopt Agile – Break projects into sprints with flexible planning.
Prioritize MVP (Minimum Viable Product) – Focus on core features first.
Leverage Debuggers – IDE tools (VS Code, PyCharm) or command-line (GDB).
2. Debugging Complex Issues
Solutions:
Write Unit Tests (e.g., pytest, JUnit) to isolate components.
Leverage Debuggers – IDE tools (VS Code, PyCharm) or command-line (GDB).
3. Keeping Up with Technology: Rapidly evolving frameworks/languages (e.g., AI, cloud).
Solutions:
Focus on Fundamentals – Algorithms > trendy tools.
Join Communities – Stack Overflow, GitHub open-source projects.

5. Tight Deadlines: Unrealistic timelines leading to rushed, buggy code.
Automate Repetitive Tasks – CI/CD pipelines (GitHub Actions, Jenkins).
Estimate Tasks Wisely – Use Fibonacci sequencing for effort scoring.
Communicate Early – Flag delays to managers before crises arises


Explain the different types of testing (unit, integration, system, and acceptance) and their importance in software quality assurance.
1. Unit Testing:Tests individual components (functions, classes) in isolation.
2. Integration Testing:Checks interaction between modules (APIs, databases, microservices).
3. System Testing:Evaluates the entire system against requirements.
4. Acceptance Testing: Confirms/verifies that  the system meets business/user requirements.


#Part 2: Introduction to AI and Prompt Engineering


Define prompt engineering and discuss its importance in interacting with AI models.
Prompt engineering is the art and science of crafting effective inputs (prompts) to guide AI models—especially Large Language Models (LLMs) like ChatGPT, Gemini, or DeepSeek—toward generating desired outputs. It involves:
Structuring queries for clarity and context.
Using techniques (few-shot learning, chain-of-thought).
Optimizing for accuracy, creativity, or task specificity.

 Prompt engineering is like teaching someone how to ask the right questions—it bridges human intent and AI capability. As AI grows more pervasive, this skill becomes as vital as programming literacy.it is important when interacting with AI because of the following:
1.Adapts AI to Domain-Specific Tasks: This is importantso that it gives resonsws tailored to that particular field of interest.
2. It keads to efficiency: Prompt Engineering saves time by reducing back-and-forth iterations with the AI.
3. It also reduces vague and unclear answers giving room for concise and clear-cut answers appropriate for each situation.


Provide an example of a vague prompt and then improve it by making it clear, specific, and concise. Explain why the improved prompt is more effective.
Vague vs. Specific Prompts 

Vague Example (Coding): 
"How do I fix my code?"  
→ AI uselessly asks:"What code? What error?"  

Clear Example:"This Python code gives 'IndexError: list out of range' on line 5. How do I safely access the last item in an empty list?" 
→ AI gives exact solution: `if my_list: last_item = my_list[-1]`

Why This Works:  
1. No Mind-Reading Needed – The AI knows *exactly* what you want.  
2. Time management: – Gets to the point in seconds.  
3. No Confusion – Clear = useful answers every time.  

