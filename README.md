# Part1-Information-Sheet-for-Students
Artifact 1 - This is a one page sheet that would provide a motivating scenario /  conceptual explanation  / a simple example of source code control

**Student Information Sheet: Implementing Source Code Control with Git**

---

### Learning Goals:
By the end of this lesson, you will be able to:
1. Explain the concept of source code control and its importance in software development.
2. Understand and implement basic git commands such as init, clone, add, commit, push, and pull.
3. Create and manage repositories on GitHub, including handling branches and merges.

### Success Criteria:
- Successfully initialize a git repository and clone an existing repository.
- Perform basic git operations like adding files, committing changes, and pushing to a remote repository.
- Demonstrate the ability to branch and merge code effectively without errors.

---

## Motivating Scenario: Safekeeping Your Digital Masterpieces

Imagine you are an artist crafting a large-scale digital art piece. Each brush stroke is a piece of your code; every change forms part of a bigger picture. Just as an artist needs to save and archive every stage of their artwork for safety and reference, coders need a robust system to manage and safeguard their code. This is where Git, a distributed version control system, comes into play. It helps you keep track of every modification, experiment safely with new ideas (branches), and combine (merge) those ideas back into your main project.

## Conceptual Explanation: What is Source Code Control?

Source code control, also known as version control, is the management of changes to documents, programs, and other information stored as computer files. It allows multiple users to work on the same codebase without overwriting each other's work, tracks history, and helps resolve conflicts by merging changes from different contributors.

**Git** is a free and open-source distributed version control system designed to handle projects with speed and efficiency. It is vital for today’s developers as it supports non-linear workflows, provides robust branching and merging capabilities, and includes cryptographic authentication of history changes.

## Example in a Real-World Scenario:

**Scenario**: A team of student developers is working to build a new feature for their school's schedule management application. They need a system to manage their code as they test new functionalities without affecting the working state of the application.

**Git Implementation**:
- **Initialize and Clone Repositories**: The team leader creates a new repository on GitHub and shares the repository link with team members. Each member clones this repository to their local machines using `git clone`.
- **Basic Operations**: Team members work on their tasks. As they edit files, they use `git add` to stage files they've modified and `git commit` to save their changes locally. When ready, they `yse `git push` to send modifications back to the GitHub server.
- **Branching and Merging**: For new features, developers create separate branches using `git branch` and switch between them using `git checkout`. Once a feature is completed and tested, it is merged back into the main branch using `git merge`, ensuring the core application remains stable and new features are integrated smoothly.

By adhering to this workflow, the team can efficiently manage their code changes and integrate contributions from multiple developers without conflicts, thereby maintaining the integrity and continuity of their application.

---

**Conclusion**:

Mastering Git not only helps you manage and protect your code but also facilitates team collaboration and project transparency. As highlighted in the source, "You Do, We Do, I Do: A Strategy for Productive Struggle," starting with hands-on practice (You do), moving to collaborative application (We do), and finally receiving guided instruction (I do), can greatly enhance your understanding and proficiency in using Git. It's a vital skill for any aspiring software engineer, ensuring you're well-prepared to manage professional development projects in the future. Embrace the power of source code control—with Git, your code’s history and collaborative potential are just a few commands away.

Sources:
Sarah McKibben (2017). [A Flight Plan for Coding in PreK and Beyond.](https://www.ascd.org/el/articles/a-flight-plan-for-coding-in-prek-and-beyond)
(2020). [Design class allows students to choose their own learning adventure.] (https://www.iste.org/explore/iste-standards-action/design-class-allows-students-choose-their-own-learning-adventure)
(2018). [Embed computational thinking into PBL.] (https://www.iste.org/explore/Computational-Thinking/Embed-computational-thinking-into-PBL)
(2019). [CT Competencies: Embrace integration across the curriculum.] (https://www.iste.org/explore/empowered-learner/ct-competencies-embrace-integration-across-curriculum)
Katie J. Waddell (2018). [You Do, We Do, I Do: A Strategy for Productive Struggle.] (https://www.ascd.org/el/articles/you-do-we-do-i-do-a-strategy-for-productive-struggle)
