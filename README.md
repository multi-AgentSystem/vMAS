# vMAS
A versatile multi-agent system (vMAS) using the Scrum framework, Python, Langchain, and GitHub for task management.

# Intro: 
So I have a pretty crazy idea, that I carry around with me for some weeks, and I am trying to build it myself. But it is not working - no software engineering skills and no plan on software development.
I would love to get some feedback here, and would appreciate if anyone wants to pitch in.

# TL;DR:
A versatile multi-agent system (vMAS) using the Scrum framework, Python, Langchain, and GitHub for task management. 
- Agents will communicate via RabbitMQ and Apache Thrift. 
- The system will be available on GitHub Marketplace, with configurations done within GitHub. 
- The backend will be powered by Python and FastAPI, with agents having access to tools like GitHub, OpenAPI, terminal, and a file management system. 
- Agents will have different types of memory bases and roles aligned with the Scrum framework.

# Project Plan
1.  Building such a versatile multi-agent system (vMAS) that aligns with the AGPL License and uses Scrum as the primary project management framework involves several stages.
2.  Scrum Framework: As your foundational methodology, Scrum provides a robust iterative framework that would allow agents to work in sprints, with reviews and retrospectives for consistent evolution and improvement.
3.  Python and Langchain: Python, a versatile and easy-to-learn language, serves as the backbone of your agents' codebase. Langchain, on the other hand, will be used to implement the agents, tapping into its potential to design artificial languages.
4.  GitHub and pyGitHub: Your agents will use GitHub for task management and versioning. Through the Python library, pyGitHub, your agents can interact directly with GitHub API, manipulating repositories, creating issues, and managing pull requests programmatically.
5.  Task Management: GitHub's Issues, Pull Requests, and Project Boards will be central to your tasks and sprint management. These tools will align your project flow with Scrum methodologies such as sprint planning, daily standups, and retrospectives.
6.  Inter-Agent Communication: RabbitMQ, a message-broker software, along with Apache Thrift, a software framework for scalable cross-language services development, will enable efficient and effective communication among agents. This will ensure a seamless feedback loop back into GitHub.
7.  GitHub Marketplace: By packaging your application as a GitHub App and listing it on the GitHub marketplace, it becomes accessible for other users to incorporate into their own repositories.
8.  Configuration: You'll develop a user interface within GitHub for agent configuration, with intuitive elements like dropdown menus for selection and a main frame for drag-and-drop operations.
9.  Backend: Python, coupled with FastAPI, a high-performance web framework, will drive your backend development. FastAPI's efficiency and Python's simplicity will provide a solid foundation for your backend.
10.  Agent Tools: Agents will have access to tools like GitHub, openapi for API specifications, terminal for command-line operations, code interpreters for executing scripts, and a file management system. This will empower the agents to perform their tasks efficiently.
11.  Memory Bases: Agents will have collective long-term, private long-term, and short-term memory bases. These different memory types could influence how an agent responds to various stimuli or tasks, allowing a tailored approach based on past interactions.
12.  Agent Roles: Following the Scrum framework, agents will take on roles like product owner, scrum master, and members of the development team. The choice of roles, whether manual or through templates, will dictate the agent's responsibilities and interactions within the system.
13.  Agent Configuration: Each agent can be configured based on the provider (such as OpenAI's model or local Language Models via GPU/CPU), its persona, its traits, and the tools it uses. The configuration data will be stored in a NoSQL database like FerretDB for easy retrieval and modification.


These steps provide a comprehensive blueprint for your vMAS, ensuring a robust, interactive, and versatile system aligned with Scrum principles.

## Example workflow for the multi-agent-system:
![PlantUML-Time-series_Multi-agent-setup](https://github.com/multi-AgentSystem/vMAS/assets/134055815/4d099aae-9efb-4cb5-83f6-f7672137956f)

## Example for the themes and the specific roles with attributes
![Rollen-Multi-agent-system](https://github.com/multi-AgentSystem/vMAS/assets/134055815/7d5a334d-9440-42bf-9c37-67d9e40326d0)
