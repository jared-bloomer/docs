# Feature Development Pattern
This document describes the pattern used by the software engineer and copilot while working on a feature  
# Context
A software developer is going to be working in concert with Copilot to implement a feature in this software project  
## Documentation
- The base documentation folder for feature development is `copilot-docs/feat`  
- all documentation should be in markdown format
- The documents will be used by Copilot to to help guide and track implementation
- All new documents should start blank
- The `copilot-docs/feat/lessons-learned.md` document captures key lessons learned during the implementation of features. It is where we will store new information which is discovered during the course of implementation. It should be used by Copilot when making implementation choices. lessons learned should only included new lessons.
- The `copilot-docs/deps/` directory contains documentation on the dependencies, integrations and interfaces used in this project.
- Feature documentation is organized in a consistent manner under `copilot-docs/feat/[Phase number]-[feature-name]/` with standardized document naming
  - `intro.md`: Feature introduction and context 
  - `implementation-plan.md`: Detailed implementation milestones
    - each milestone will include a section describing the expected outcome
    - the implementation plan is high level
    - the implementation plan should not contain code, technical specifications or directory structures. prose only.
    - Each implementation milestone should include only a single discrete testable change. Break complex implementations into multiple smaller milestones, where each milestone can be independently verified.
  - `implementation-progress.md`: Track progress of implementation
    - Checklists make the progress report easy to understand
# Software Developer and Copilot working together
The feature will be implemented by Copilot with direction and feedback given by the software engineer.  
Focus on understanding the work to be done before getting to the code.  
## Software Engineers role
The software engineer plays an important role in the implementation pattern.  
The software engineer:
- Providing feedback on changes made by Copilot
- Validating milestone completion
- Providing context
- Makes git commits
- Gets documentation for Copilot
- Decides when to continue to the next activity
## Copilots role
Copilot manages the code. This pattern is single writer and copilot is the writer.  
Copilot:
- Writes the code
- Keeps documents up to date
- Asks software engineer for input
# General Pattern
- Copilot creates the docs for the new feature
- Software Engineer writes the intro file
- Copilot check's it's understanding of the intro file with the software engineer until consensus is reached.
- Copilot creates a implementation plan document.
- The software engineer reviews the implementation plan and provides feedback.
- The software engineer and copilot work together to refine the implementation plan until the software engineer is satisfied with the plan.
- Copilot begins implementation work, starting with the first milestone.
- Copilot runs builds and tests to verify the correctness of it's changes.
- After Copilot finishes implementation the software engineer checks the code and application.
- The software engineer provides feedback to Copilot
- Copilot makes updates to the implementation based on the software engineers feedback.
- The software engineer and copilot continue the milestone refinement cycle until the software engineer is satisfied.
- The milestone is considered complete and Copilot updates the implementation progress and lessons learned docs.
- At the software engineers direction Copilot begins work on the next milestone.
- This pattern continues until all the milestones are complete.
## Post feature completion
- Update project level docs such as the README file
# Directives
Do not begin implementating a milestone until the software developer agrees