A large-scale benchmark called ScenEval, consisting of 12,864 tasks for testing LLMs on their capability at generating Java programs from natural language description of coding tasks, was constructed by extracting sources automatically from professional problem-solving forum Stack Overflow and online training website W3Resource Tutorial on Java programming, and manually from textbooks of Java programming. The former forms a sample of real-world coding problems asked by professional developers while the latter forms a sample of textbook questions that are presented well by expert and authoritative authors. There are also a number of novelties in the design of the benchmark, which include the use of metadata to describe the scenarios of the coding tasks in the benchmark, and the inclusion of reference solutions of the coding tasks.

In ScenEval, each test case is a coding task accompanied by metadata represented as a JSON value, with its structure illustrated in figures below:

Task ID: A unique identifier assigned to each coding task.

Title: The title of the coding task.

Source: A list of sources where the task is found; multiple sources are listed if the task appears in more than one.

Topics: A list of topics that the coding task addresses.

Programming Language: The programming language in which the solution is to be implemented.

Version: The version number of the task, enabling tracking of dataset evolution.

Description: A detailed description of the coding task, which may include plain
text, a code snippet (e.g., a function signature or skeleton), or a fully qualified file
name for image data.

Reference Solutions: A collection of reference solutions for the task.
![fig43](https://github.com/user-attachments/assets/9dbe9891-e992-47c6-b561-8183aa1e7eff)
![fig44](https://github.com/user-attachments/assets/391d0a67-7d0e-4803-ad6c-963d4893f03a)
![fig_3](https://github.com/user-attachments/assets/5b4c13f6-8a27-4e6b-9de5-2e06d2d6ab29)
![fig_5](https://github.com/user-attachments/assets/af887814-199c-4cb7-8553-5a2d9154587b)
![fig_6](https://github.com/user-attachments/assets/d911a416-2f5b-4dbb-811d-4b35e2ee2aa5)

