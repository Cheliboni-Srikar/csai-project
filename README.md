# DLLM — Software and Symbolic AI

A beginner learning project for the Artificial Intelligence and Computational Science course.

Version 1.0 content draft, prepared 29 October 2026. Six chapters, worked examples, original diagrams, learner activities, and answered quizzes are present. Human peer review and repository evidence remain unfinished. This revision is later than the Stage 1 deadline; it is not evidence of an earlier submission.

Repository URL: TODO — add the actual GitHub repository URL.

## Team members

- 陈奕凯 — CEO: team coordination and milestones. GitHub username: TODO.
- LIM HAO CHEN — CIO: research resources and repository organization. GitHub username: TODO.
- CHELIBONI SARASWATHIBAVANI SRIKAR — Content Lead: learning content and Chapter 2 drafting. GitHub username: TODO.
- 乔尔 — Quality Lead: accuracy, clarity, and activity review. GitHub username: TODO.
- 张朝瞳 — Video and Visual Design Lead: diagrams and presentation/video planning. GitHub username: TODO.

Each member contributes substantive work and helps review the shared learning material.

## Purpose and intended learners

We are developing an accessible introduction to software and symbolic AI. The shared Markdown content will form the foundation for a study guide, presentation slides, and video tutorials.

The intended learners are first-year students and other beginners. Basic computer use is sufficient; prior programming or formal logic knowledge is not required. New technical terms will be defined when they first appear.

We use a fictional study-space adviser to connect the concepts: describe a learner's needs, represent room facts, apply explicit rules, and explain the result.

## Learning outcomes

Learners should be able to:

- Distinguish hardware, system software, and application software.
- Explain inputs, processing, outputs, algorithms, and programs.
- Represent simple knowledge using symbols, facts, predicates, and rules.
- Evaluate AND, OR, and NOT, and follow the direction of an IF–THEN rule.
- Trace simple forward and backward reasoning and identify missing support.
- Interpret a basic search graph and check an action's preconditions and effects.
- Identify the components of a small expert system and test its recommendations.
- Explain a strength and a limitation of symbolic AI.

## Where to find the materials

- [Module outline](content/module-outline.md): sequence, prerequisites, outcomes, examples, and section status.
- [Study guide](content/study-guide.md): all six drafted chapters, activities, quizzes, explained answers, glossary, and references.
- [Project plan](docs/project-plan.md): scope, workflow, milestones, and planned resource use.
- [Task list](docs/tasks.md): completed preparation and remaining team tasks.
- [Review and resource-use record](docs/review-and-use.md): content checks and the pending team review.
- [Stage 1 checklist](docs/stage1-checklist.md): requirements A–F, repository evidence, and final submission requirements.
- [Optional Python example](examples/study_space_adviser.py): a small runnable adviser using the Chapter 5 rules.
- [Assets and attribution](assets/README.md): seven PNG diagrams and their editable SVG sources.

`content/` contains learner material; `docs/` contains public project records; `assets/` contains original diagrams; `examples/` contains optional demonstration code. Image paths are relative to the Markdown file that uses them. Keep these folders together.

## Module outline and development status

The six-chapter structure was agreed by the team. All six chapters now have AI-assisted draft text in this prepared version. “Drafted” means text is present; it does not mean a teammate has approved it.

1. Software foundations — software types, inputs/outputs, algorithms, requirements, and tests. Drafted; the team reported agreeing on initial Chapter 1 content during a lab. Review of this revision is pending.
2. Symbols, facts, and logic — knowledge representation, predicates, AND/OR/NOT, IF–THEN rules, and missing information. Drafted; Content Lead research and team adaptation remain in progress.
3. Reasoning with rules — forward/backward chaining, proof traces, missing support, and a card activity. Developed demonstration lesson; team review pending.
4. Search and planning — states, goals, BFS/DFS, preconditions, and effects. Drafted; scope/depth confirmation and team review pending.
5. Build a small expert system — knowledge base, working memory, inference engine, and the study-space adviser. Drafted with an optional runnable example; team review pending.
6. Test, explain, and improve — test cases, conflicts, updates, regression tests, strengths, and limitations. Drafted; learner trial and team review pending.

The [module outline](content/module-outline.md) records the detailed outcomes and gaps.

## Teaching approach

Use a short explanation, a defined vocabulary, a worked example, and an activity before each quiz. The fictional study-space adviser connects the chapters. Chapter 2 translates ordinary statements into facts and rules. Chapter 3 traces the same logical structure forward and backward, then removes one fact to expose missing support.

Quizzes have click-to-reveal explanations on GitHub. Activities use paper/cards; programming is optional. The diagrams are included as images, so their display does not depend on a Mermaid renderer.

## Current progress

- Team-reported: topic and roles selected; six-chapter sequence agreed; initial Chapter 1 content discussed in a lab; Chapter 2 research and early GitHub work started.
- Prepared in this revision: six substantive chapter drafts, seven diagrams, 24 answered quiz questions, six activity sets, project plan/task files, source checks, and an optional demonstration.
- Still required: confirm usernames and repository URL, review/adapt the draft as a team, record a real peer-review outcome, confirm individual contributions, and capture actual repository history and changes.
- Planned: turn checked content into slides and video tutorials for Stage 2.

## Project plan and task list

See the [public project plan](docs/project-plan.md) and [current task list](docs/tasks.md).

- Stage 1 deadline: 24 October 2026, 23:59 Beijing time. Completion of that submission has not been established by these files.
- Stage 2 deadline: 7 November 2026; proposed internal review on 4 November.
- Stage 3 deadline: 28 November 2026; proposed internal review on 25 November.

## Collaboration, references, and review

- Make focused changes and use commit messages that explain what was added or improved.
- Where practical, each member commits their own work. Identify both author and uploader when work is uploaded on another member's behalf.
- Put identifiable references alongside the relevant learning content. Use source labels such as `Source 1`, while reserving `R1`, `R2`, and `R3` for reasoning rules.
- Have another member check technical accuracy, beginner accessibility, activities, answers, sources, and working assets. Record actual outcomes rather than marking unreviewed drafts as checked.
- Keep personal logs, student IDs, and private information out of a publicly accessible repository. Submit required private evidence through the course submission package.

## AI assistance

AI has assisted with initial planning, draft learning material, Markdown diagrams, and this README. Team members are responsible for verifying, adapting, and explaining the content. Significant AI interactions and verification evidence belong in the relevant project and personal logs submitted for assessment.

## Before using this README as submission evidence

- Replace the repository URL and GitHub username placeholders.
- Confirm member details and update statuses to match actual work.
- Upload the complete folder structure and confirm the relative links and images in the actual repository.
- Check that the README, learning content, plan, review records, and submitted snapshot agree.
