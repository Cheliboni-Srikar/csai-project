# Module outline and development status

Team: DLLM. Module: Software and Symbolic AI. Version 1.0 draft prepared 29 October 2026.

Audience: first-year students and other beginners. Basic computer use and reading ordinary IF–THEN statements are enough. No programming or formal logic course is required.

## Learning sequence

Start with the software task, express its knowledge, reason with it, search for actions, combine the pieces, and test the result. The same fictional study-space adviser gives the sequence a common purpose.

## Meaning of the status labels

- Outline only: topics or goals listed, but no developed teaching text.
- Drafted: substantive text, examples, and exercises exist; team review is unfinished.
- Checked: a named reviewer records what they checked and an actual outcome for an identified version.
- Needs revision: a recorded issue remains unresolved.

All six chapters are drafted in this prepared version. Automated and assistant checks do not establish that a team member has checked the chapter. No real learner trial is claimed.

## Chapter 1: Software foundations

- Read: [Chapter 1](study-guide.md#chapter-1-software-foundations).
- Prerequisites: Basic computer use.
- Learning outcome: Distinguish software types and hardware; specify input, processing, output, and a test.
- Subtopics: Software/hardware; application/system software; algorithms/programs; requirements; input validation and testing.
- Worked example: Design a study-space adviser on paper; correct a rule that ignores the room’s quietness.
- Learner activity: Label two inputs and one output, then write a missing-information test.
- Check understanding: four quiz questions with explained answers in the chapter.
- Status: Initial Chapter 1 content agreed in a lab according to team updates. This revision is drafted; teammate review pending.

## Chapter 2: Symbols, facts, and logic

- Read: [Chapter 2](study-guide.md#chapter-2-symbols-facts-and-logic).
- Prerequisites: Chapter 1 and ordinary true/false statements.
- Learning outcome: Define symbols and predicates; translate facts; evaluate AND/OR/NOT; follow implication direction.
- Subtopics: Symbolic AI; representation; facts; predicates and argument order; knowledge bases; simple variables; logical connectives; unknown versus false.
- Worked example: Translate Enrolled(Mina, AI101), instantiate a rule, and check a three-condition room rule.
- Learner activity: Write facts and an AND rule; compare true, false, and missing input cases.
- Check understanding: four quiz questions with explained answers in the chapter.
- Status: Drafted; Content Lead research and adaptation in progress; teammate review pending.

## Chapter 3: Reasoning with rules

- Read: [Chapter 3](study-guide.md#chapter-3-reasoning-with-rules).
- Prerequisites: Chapter 2, especially AND and IF–THEN.
- Learning outcome: Trace forward/backward reasoning, explain dependencies, and identify missing support.
- Subtopics: Premises/conclusions; rule IDs; forward chaining; backward chaining; subgoals; proof traces; cycles and repeated facts.
- Worked example: R1 and R2 derive suitable then recommend; remove open and explain the blocked step.
- Learner activity: Act as the inference engine with cards, then apply a new group-room rule.
- Check understanding: four quiz questions with explained answers in the chapter.
- Status: Developed demonstration lesson; teammate review and learner trial pending.

## Chapter 4: Search and planning

- Read: [Chapter 4](study-guide.md#chapter-4-search-and-planning).
- Prerequisites: Chapter 2; queues/stacks are introduced in the chapter.
- Learning outcome: Separate exploration order from a returned path; compare BFS/DFS; check a plan.
- Subtopics: States/actions/goals; frontier; queue/stack; visited states; BFS/DFS; parent paths; action preconditions/effects.
- Worked example: BFS returns S–A–G; DFS choosing B first finds S–B–C–G. Check walk then plug in.
- Learner activity: Trace the frontier and remove socket_working from the action model.
- Check understanding: four quiz questions with explained answers in the chapter.
- Status: Drafted; confirm the expected depth of formal search with the teacher; teammate review pending.

## Chapter 5: Build a small expert system

- Read: [Chapter 5](study-guide.md#chapter-5-build-a-small-expert-system).
- Prerequisites: Chapters 1–3; Python is optional.
- Learning outcome: Separate general rules, case facts, and the inference engine; trace a supported recommendation.
- Subtopics: Knowledge base; working memory; interface; inference engine; positive rules; sets; missing and stale facts.
- Worked example: R4 and R5 derive needs_quiet_power then recommend_A from five facts.
- Learner activity: Build the adviser with cards; optionally compare four runnable cases.
- Check understanding: four quiz questions with explained answers in the chapter.
- Status: Drafted with an optional example; team review and a beginner trial pending.

## Chapter 6: Test, explain, and improve

- Read: [Chapter 6](study-guide.md#chapter-6-test-explain-and-improve).
- Prerequisites: Chapter 5 and its rules.
- Learning outcome: Design normal, missing, conflicting, and changed-input tests; explain a limitation.
- Subtopics: Expected/actual results; validation policy; regression testing; stale facts; model coverage; symbolic/learned cooperation.
- Worked example: Reject open_A plus closed_A; recompute when availability changes.
- Learner activity: Write four test cases and propose one improvement such as fact timestamps.
- Check understanding: four quiz questions with explained answers in the chapter.
- Status: Drafted; teammate review and learner feedback pending.

## Gaps and scope decisions

- Detailed coverage: definitions, small rule systems, worked traces, and paper exercises.
- Introductory coverage: first-order notation, BFS/DFS, and action models.
- Outside this draft: resolution proofs, advanced search, industrial expert-system implementation, and neural-network training.
- Confirm with the teacher whether a deeper treatment of formal logic and specific search algorithms is expected.
- Team chapter ownership beyond the Content Lead’s work on Chapter 2 needs confirmation.
- Test whether beginners can complete activities from the supplied information, then revise confusing steps.

## Connections to later deliverables

- Study guide: keep the definitions, worked examples, activities, and answer explanations.
- Slides: use the same diagrams and one decision or reasoning step per slide.
- Video: narrate a supported rule chain, pause for a prediction, then remove a fact and explain the changed result.

See the [review and resource-use plan](../docs/review-and-use.md).
