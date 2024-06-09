[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15240566&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

Software engineering is the systematic application of engineering principles techniques and methods to the design, development, testing, and maintenance of software systems. Its aim is to produce high-quality software products that meet the needs of users, are delivered on time and within budget, and are maintainable and scalable in the long term.

What is software engineering, and how does it differ from traditional programming?
Software engineering involves with design, development, testing and maintenance of software applications.

Differences between software engineering and traditional development:
Traditional programming often focuses solely on writing code to achieve a specific functionality or solve a particular problem. Software engineering, on the other hand, encompasses a broader range of activities beyond just coding, such as requirements analysis, design, testing, and maintenance.

Software engineering follows a systematic and structured approach to software development, typically involving defined phases or stages. Traditional programming may lack this structured process, with developers often diving directly into coding without a comprehensive plan.

Software engineering places a strong emphasis on producing high-quality software products that are reliable, scalable, maintainable, and secure. This involves adhering to best practices, using design patterns, writing clean and well-documented code, and conducting thorough testing. Traditional programming may prioritize quick solutions over long-term quality.

Teamwork and Collaboration: Software engineering often involves collaboration among team members with diverse skills and expertise, including developers, designers, testers, project managers, and stakeholders. Traditional programming may be more individual-focused, with developers working alone on small projects.

Software engineering considers the entire software lifecycle, from initial concept to retirement, and focuses on creating sustainable software solutions that can evolve and adapt to changing requirements over time. Traditional programming may be more focused on solving immediate problems without considering long-term implications.


Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Requirements analysis - The requirements of the software system are gathered from the users and other sources.
Planning - The project leads to defining the project's purpose and its desired result.
Design and prototype - The design of the system ie the system structure, components, interfaces, and data models.
Software development - This is the phase where the actual code is written based on the design specifications using programming languages and development tools.
Testing - The software is tested to ensure that it meets the specified requirements and quality standards.
Deployment - The software is deployed to the production environment for use by end-users. This may involve installation, configuration, and migration of data.
Maintenance - This phase involves ongoing support and updates to the software. This includes fixing bugs, addressing user feedback, adding new features, and making enhancements to the system.
References: Distant job - https://distantjob.com/blog/software-development-life-cycle-stages-and-models/#:~:text=A%20full%20SDLC%20has%207,omitted%2C%20split%2C%20or%20combined.
Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Agile model: It strongly emphasizes developer-client communication. The team agrees on an MVP (Minimum Viable Product) with essential features and tries to reach that in as few iterations as possible. After every development iteration, the customer can see the results and let the team know if they are satisfied. Therefore, work is done in regularly iterated cycles that are identified as sprints—projects under the Agile model usually last from two to four weeks.

Waterfall model: It was the original SDLC process. It divides the project into discreet phases with tasks and objectives. In this model, the team must execute of every stage completely, meaning that the output of one phase is the input of the next phase. If one phase is not completed, it’s impossible to move forward to the next one. Another characteristic of the Waterfall model is that it’s strictly documented and has predefined features expected to be developed in every phase.

Key differences:
Approach: Waterfall follows a sequential approach, while Agile is iterative and incremental.
Flexibility: Waterfall is less flexible and adaptable to changes, while Agile is easy to change.
Documentation: Waterfall emphasizes detailed documentation, while Agile values working software over comprehensive documentation.
Customer Involvement: Agile involves customers and stakeholders throughout the development process, while Waterfall typically has less customer involvement until the later stages.
Risk Management: Waterfall attempts to mitigate risks early in the process, while Agile manages risks through incremental development and continuous feedback.

Agile model is preferred for projects with evolving or unclear requirements, where flexibility, collaboration, and frequent feedback are crucial.
Waterfall model is preferred for well-defined projects with stable requirements, where predictability and detailed documentation are essential.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirements Engineering is the process of identifying, eliciting, analyzing, specifying, validating, and managing the needs and expectations of stakeholders for a software system.
Steps:
1) Feasibility Study - involves the following feasibility studies:
i. Technical Feasibility: The current resources both hardware software along required technology are analyzed/assessed to develop the project. This technical feasibility study reports whether there are correct required resources and technologies that will be used for project development. Along with this, the feasibility study also analyzes the technical skills and capabilities of the technical team, whether existing technology can be used or not, whether maintenance and up-gradation are easy or not for the chosen technology.
ii. Operational Feasibility: The degree of providing service to requirements is analyzed along with how easy the product will be to operate and maintain after deployment.
iii. Economic Feasibility study cost and benefit of the project are analyzed.
2) Requirements elicitation - It is the process of gathering information about the needs and expectations of stakeholders for a software system. It is related to the various ways used to gain knowledge about the project domain and requirements. The various sources of domain knowledge include customers, business manuals, the existing software of the same type, standards, and other stakeholders of the project. The techniques used for requirements elicitation include interviews, brainstorming, task analysis, Delphi technique, prototyping, etc.
3) Requirements specification - It is the process of documenting the requirements identified in the analysis step in a clear, consistent, and unambiguous manner. This activity is used to produce formal software requirement models.
4) Requirements for verification and validation - Verification: It refers to the set of tasks that ensures that the software correctly implements a specific function. 
Validation: It refers to a different set of tasks that ensures that the software that has been built is traceable to customer requirements.
5) Requirements management - It is the process of analyzing, documenting, tracking, prioritizing, and agreeing on the requirement and controlling the communication with relevant stakeholders. It involves the process of managing the requirements throughout the software development life cycle, including tracking and controlling changes, and ensuring that the requirements are still valid and relevant.

Importance of Requirements Engingeering:
Alignment with Stakeholder Needs
Reduced Development Costs and Risks
Improved Communication and Collaboration among stakeholders, developers, testers, and other project team members.
Enhanced Quality and User Satisfaction.
Requirements serve as the foundation for system design, development, testing, and deployment.
 References: https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/
 ChatGPT Open AI

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity in software design refers to the practice of breaking down a software system into smaller, self-contained units or modules, each responsible for a specific aspect or functionality of the system. These modules are designed to be independent, cohesive, and loosely coupled, meaning they can be developed, tested, and maintained separately from one another. 
Modularity allows changes to be made to one module without affecting others. This isolation reduces the risk of unintended side effects and makes it easier to debug and maintain the software system. It encourages reuse of existing modules in different parts of the system or in other projects. It also improves maintainability by localizing changes to specific modules. Modular systems are easier to test because each module can be tested independently.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Unit testing involves testing individual units or components of the software in isolation. These units are typically functions, methods, or classes.
Integration testing verifies that individual units/modules work together as expected when combined to form larger components or subsystems.
System testing evaluates the entire software system as a whole, ensuring that it meets the specified requirements and functions correctly in the intended environment.
Acceptance testing evaluates the software's compliance with business requirements and assesses its suitability for deployment.
Importance of testing:
Bug detection and fixing.
Quality assurance.
Identifying and mitigating risks.
User needs satsfaction.
Provides feedback for improvement.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Version Control Systems (VCS) are tools that track changes to source code, documents, or any other set of files over time, allowing multiple developers to collaborate on a project simultaneously, managing various versions of the files and facilitating tasks such as branching, merging, and tracking changes. 
Version control systems are essential tools for software development teams, enabling efficient collaboration, tracking changes, managing project history, and ensuring the integrity and reliability of project files.
Examples of version control systems: Git, Microsoft Team Foundation Server (Azure DevOps Server), Helix Core.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Project managers in software organize software projects and can assign tasks to software engineering teams according to the specifications of a task. Software project managers use their leadership skills, technical knowledge and experience to direct their teams and ensure software meets client requirements.
Some of the challenges faced in software project management include:
Misalignment between goals and business objectives.
Communication.
Lack of accountability.
Resource allocation.
Project management software.
Poor planning and unrealistic deadlines.

Reference: https://www.koombea.com/blog/project-manager-challenges/
https://www.indeed.com/career-advice/finding-a-job/project-manager-in-software#:~:text=Software%20project%20managers%20serve%20as,to%20help%20complete%20the%20project.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Software Maintenance refers to the process of modifying and updating a software system after it has been delivered to the customer.
Several Types of Software Maintenance
Corrective Maintenance: This involves fixing errors and bugs in the software system.
Patching: It is an emergency fix implemented mainly due to pressure from management. Patching is done for corrective maintenance but it gives rise to unforeseen future errors due to lack of proper impact analysis.
Adaptive Maintenance: This involves modifying the software system to adapt it to changes in the environment, such as changes in hardware or software, government policies, and business rules.
Perfective Maintenance: This involves improving functionality, performance, and reliability, and restructuring the software system to improve changeability.
Preventive Maintenance: This involves taking measures to prevent future problems, such as optimization, updating documentation, reviewing and testing the system, and implementing preventive measures such as backups.
Software Maintenance must be performed in order to: 
Correct faults.
Improve the design.
Implement enhancements.
Interface with other systems.
Accommodate programs so that different hardware, software, system features, and telecommunications facilities can be used.
Migrate legacy software.
Retire software.
Requirement of user changes.

References: https://www.geeksforgeeks.org/software-engineering-software-maintenance/

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Ethical issues:
Unethical data collection
Algorithmic bias
Weak security
Wrong Priorities
What they can do to adhere to ethical standards:
Be honest
Be accountable
Be proactive
Be a responsible citizen

Reference: https://fullscale.io/blog/ethical-issues-in-software-development/

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
