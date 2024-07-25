# Part1-Information-Sheet-for-Students
Artifact 1 - This is a one page sheet that would provide a motivating scenario /  conceptual explanation  / a simple example of source code control

**Student Information Sheet: Implementing Source Code Control with Git**

---
![XKCD GitHub Comic]([http://url/to/img.png](https://imgs.xkcd.com/comics/git.png))
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
- **Basic Operations**: Team members work on their tasks. As they edit files, they use `git add` to stage files they've modified and `git commit` to save their changes locally. When ready, they use `git push` to send modifications back to the GitHub server.
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

### Student Programming Exercises/Assignment: GitHub Scavenger Hunt

---

#### Objective:
To reinforce understanding of Source Code Control (SCC) principles, focusing on using Git and GitHub effectively. This assignment will help students extend their knowledge by practically navigating a version control system, managing changes, and collaborating using GitHub. The activities are designed as a scavenger hunt within the framework of the GitHub repository provided (https://github.com/code-dot-org/csa-se-lesson1).

#### Exercises Outline:
Students will work through a series of tasks that require them to clone, modify, rollback, branch, merge, and manage pull requests within a GitHub repository.

**Exercise 1: Clone and Initial Setup**
- Goal: Understand the process of cloning a repository and setting up a local workspace.
- Task: Clone the provided repository to your local machine using `git clone`.
- Expected Output: Students should have a local copy of the repository.

**Exercise 2: Branch Creation and Modification**
- Goal: Learn how to create branches and make modifications in a controlled way.
- Task: Create a new branch named `feature-yourname`, then add a new file named `yourname.txt` that contains some information about yourself.
- Expected Output: A new branch with a new file properly committed.

**Exercise 3: Commit Changes**
- Goal: Grasp commit principles in git for tracking changes.
- Task: Make changes to `README.md` in your new branch by adding a line of text at the bottom describing what you've learned so far about SCC. Commit these changes.
- Expected Output: Changes are committed with an appropriate commit message.

**Exercise 4: Pushing and Pull Requests**
- Goal: Understand how to push changes to the remote repository and initiate pull requests.
- Task: Push your branch to GitHub and create a pull request to merge your changes into the `main` branch.
- Expected Output: A new pull request created on GitHub for review.

**Exercise 5: Review and Merge**
- Goal: Learn the process of reviewing code and merging branches.
- Task: As a class, review another student’s pull suggestions on their pull request. Once reviewed, perform a merge of `feature-yourname` into the `main` branch.
- Expected Output: Successfully merged branches without conflicts.

**Exercise 6: Handling Merge Conflicts**
- Goal: Learn how to resolve merge conflicts — a critical skill in collaboration and SCC.
- Task: Intentionally create a conflict by modifying the same block of text in `README.md` that another student has also changed in their branch. Attempt to merge these changes.
- Expected Output: Manually resolve the conflict and successfully merge the branches.

#### Possible Misconceptions and Solutions:
- **Misconception**: Any commit or branch affects the main project immediately.
  - **Correction**: Clarify that changes in branches do not affect the main project (`main` branch) until they are merged.
- **Misconception**: Merge conflicts are an error or a problem.
  - **Correction**: Teach that merge conflicts are a normal part of collaborating in SCC environments and provide an opportunity to align team members’ visions and implementations.
- **Misconception**: Pushing and committing are the same.
  - **Correction**: Explain that committing logs changes locally on your machine while pushing sends those changes to the remote repository.

These exercises, aligned with research-based strategies mentioned in "Using research-based strategies to help students master computational thinking", encourage practical engagement and provide multiple touchpoints for learning and review, scaffolding students into mastery of SCC practices. By engaging in this form of practical application, students can develop a deeper understanding and solidify their skills in using SCC effectively, as emphasized by the GANAG lesson planning schema which advocates for guided application and reflection in learning activities.

Sources:
Sarah McKibben (2017). [A Flight Plan for Coding in PreK and Beyond.](https://www.ascd.org/el/articles/a-flight-plan-for-coding-in-prek-and-beyond)

(2018). [Embed computational thinking into PBL.](https://www.iste.org/explore/Computational-Thinking/Embed-computational-thinking-into-PBL)

(2019). [CT Competencies: Embrace integration across the curriculum.](https://www.iste.org/explore/empowered-learner/ct-competencies-embrace-integration-across-curriculum)

Charlie Harper (2017). [The STEAM-Powered Classroom.](https://www.ascd.org/el/articles/the-steam-powered-classroom)

Educational Leadership Staff (2017). [Tell Me About … / A Problem-Solving Activity that Energizes Students.](https://www.ascd.org/el/articles/a-problem-solving-activity-that-energizes-students)
