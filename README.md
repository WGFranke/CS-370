# CS-370

Work Breakdown: Given vs. Created Code
**What code were you given?**
The foundational structure of the maze environment, the grid rendering mechanics, and the basic simulation loop utilities were provided. This included the skeletal framework for defining grid states, visual rendering, and baseline interfaces for interacting with the environment.

**What code did you create yourself?**
I created the complete Deep Q-Learning architecture, including the sequential neural network model for Q-value approximation, the experience replay memory buffer, and the training loop integrating the Bellman equation. I also implemented the epsilon-greedy exploration decay schedule, action selection logic, loss calculation (Mean Squared Error), and the optimization steps required to achieve 100% convergence and win-rate stability in complex maze layouts.

**Connecting Learning to Computer Science**
What do computer scientists do and why does it matter?
Computer scientists design, build, and optimize systematic solutions to complex, abstract, and real-world problems. Rather than manually hardcoding rules for unpredictable environments, computer scientists build adaptive models—such as reinforcement learning agents—that learn from feedback, data, and trial. This matters because it enables automation and intelligent decision-making in dynamic domains where traditional deterministic algorithms fall short, spanning autonomous robotics, pathfinding, resource optimization, and game theory.

**How do I approach a problem as a computer scientist?I approach problems through a structured, modular, and iterative engineering process:**
Decomposition: Breaking down a complex objective (like maze navigation) into discrete components: state representation, action spaces, reward structuring, and policy evaluation.
Algorithmic Modeling: Selecting appropriate mathematical frameworks and data structures—such as deep neural networks for function approximation and experience replay buffers to break correlation between consecutive training samples.
Testing and Refinement: Iteratively tuning hyperparameters, monitoring loss convergence, and validating performance metrics against edge cases.

**What are my ethical responsibilities to the end user and the organization?**
As a software engineer and machine learning practitioner, ethical responsibility centers on safety, transparency, fairness, and reliability. When deploying automated decision-making systems or intelligent agents:
Safety and Predictability: Ensuring the model behaves reliably within defined boundaries and gracefully handles unexpected states without catastrophic failure.
Data Privacy & Governance: Respecting data integrity and ensuring that algorithmic models do not exploit user data or propagate biased decisions.
Transparency: Maintaining explainability in how models derive conclusions so that stakeholders and end-users can trust, audit, and understand system behavior.
