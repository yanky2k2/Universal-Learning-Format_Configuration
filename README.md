# Universal-Learning-Format_Configuration
An extensible, subject-independent AI learning framework.

Universal Learning Format (ULFC)
A reusable, subject-independent framework for helping AI explain, teach, and organize information so people can understand it and remember it.
Current configuration: ULFC v1.0

ULFC is a set of reusable instructions that guides an AI assistant through a clear learning process. It is designed to work across many subjects—not just technology or computer science—and can be adapted as a learner's needs change.
What is ULFC?
ULFC stands for Universal Learning Format Configuration.

It is a human-readable learning framework written in Markdown. You can give the configuration to a compatible AI assistant so it can use the framework when explaining a topic, helping with an assignment, or turning source material into a study resource.

ULFC is not a standalone application, programming language, or AI model. It does not require Python, JavaScript, or other programming languages to use. It provides the learning instructions; the AI assistant applies them.
The three learning stages
ULFC organizes learning around three complementary stages:
1. 📖 EXPLANATION — Learn the topic
The assistant should explain the material clearly and at an appropriate level.
- Define important terms, concepts, methods, formulas, commands, and processes.
- Expand important acronyms and abbreviations when they first appear.
- Use direct, accessible language without removing important subject-specific terminology.
- Explain what something is, what it does, and why it matters.
2. 💡 UNDERSTAND — Make it click
The assistant should help the learner connect ideas and understand how and why things work.

Depending on the subject, it can use:
- Real-world examples, comparisons, scenarios, and analogies.
- Flowcharts for processes and decisions.
- Timelines for historical events and sequences.
- Labeled diagrams for science, technology, and systems.
- Concept maps, comparison tables, worked examples, and step-by-step demonstrations.
Visuals should teach something—not simply decorate the page.
3. 🧠 MEMORIZE — Keep the important points
The assistant should make essential information easier to review and retain.

This can include:
- Key facts, definitions, formulas, dates, vocabulary, commands, and rules.
- Memory tricks and mnemonics.
- Recap tables and quick-reference sheets.
- Concise summaries for review.
Designed for many subjects
ULFC is subject-independent. The teaching method and visuals should fit the material rather than forcing every subject into one template.

Examples:
Subject	Useful learning approaches
Mathematics	Explain formulas, show calculation steps, work through examples, and identify common mistakes.
Science	Explain concepts, label structures, and show systems, processes, and cause and effect.
History and social studies	Organize events chronologically and explain causes and consequences with timelines or maps.
Languages	Explain grammar, provide vocabulary and example sentences, and add pronunciation or dialogue practice when requested.
Writing and literature	Explore themes, structure, evidence, vocabulary, and writing techniques.
Computer and IT	Explain architecture, protocols, commands, workflows, and troubleshooting with diagrams.
Business and economics	Explain models, processes, comparisons, formulas, and practical scenarios.


These are examples, not limits. The framework should adapt to other subjects too.
Working with assignments and source material
ULFC is intended to support learning while respecting the actual task.

When a learner provides course notes, PDFs, slides, screenshots, instructions, or a rubric, the assistant should:
- Treat the supplied material and assignment instructions as the primary source.
- Preserve important terminology, framing, order, and level of detail when appropriate.
- Avoid inventing facts or claiming that a source says something it does not.
- Distinguish source-based information from added explanations, examples, or outside research.
- Follow the assignment's required format rather than forcing the three learning stages into a submission that needs a different structure.
The goal is to help the learner understand and prepare the work while ensuring the final deliverable still follows the assignment requirements.
Documents and visual study guides
When a learner requests a standalone learning document or PDF, ULFC recommends a clear, polished, subject-appropriate result.

A document may include:
- A logical structure and useful overview.
- Clear explanations at the right level.
- Meaningful diagrams and visual teaching aids.
- A memorization or review section where appropriate.
- Readable tables, spacing, headings, and page organization.
The design should fit the subject. A learning document should be useful and readable—not just plain text placed inside colorful boxes.

Practice questions and answer keys are not included in PDFs by default. They can be provided separately or added when the learner explicitly requests them.

ULFC does not require a PDF for every ordinary question. A document should be created when requested or when the learner's established workflow clearly calls for one.
How to use ULFC
You do not need to program or install software to use the configuration.
1. Open the ULFC-v1.0.md configuration file in this repository.
2. Copy its contents.
3. Paste the instructions into a compatible AI assistant conversation or instruction area.
4. Ask the assistant to use it as your learning framework.
5. When you want it applied to a task, use a phrase such as "Apply Learning Format" or "Use my Learning Format."
You can then provide a topic, assignment, or learning material and explain what you want to achieve.

The exact way to provide instructions may differ between AI tools. ULFC is a human-readable configuration, not a guarantee that every AI assistant will interpret every instruction identically.
Customization and extension
ULFC is designed to be a living configuration.

You can adapt it to your learning preferences over time. For example:
- Add a preference: "Update my Learning Format: add more worked examples."
- Change a preference: "Change my Learning Format: use shorter explanations."
- Make a temporary exception: "For this assignment only, use a formal academic tone."
- Remove a preference: "Remove this preference from my Learning Format."
- Review the configuration: "Show me my current Learning Format."
When updating the framework, preserve existing preferences unless you intentionally choose to replace or remove them. If instructions conflict, the newest explicit instruction for the task should take priority.
Project files
The repository can grow as the framework develops. A simple starting structure could be:
universal-learning-format/
├── README.md
├── ULFC-v1.0.md
├── CHANGELOG.md
└── LICENSE
- README.md — introduces the project and explains how to use it.
- ULFC-v1.0.md — contains the complete v1.0 configuration.
- CHANGELOG.md — records changes between versions.
- LICENSE — states the terms under which others may use, modify, and share the project.
Only add a license after choosing the terms you want to apply. Until a license is included, do not assume that the repository's contents are open for unrestricted reuse.
Contributing ideas
Ideas for improving ULFC can include clearer instructions, better ways to explain difficult concepts, useful subject-specific examples, accessibility improvements, and more effective ways to organize learning material.

When proposing a change, try to explain:
1. What should change?
2. What learning problem does it address?
3. How would the change help learners?
4. Does it preserve the framework's subject-independent purpose?
The aim is to improve the framework without making it unnecessarily complicated.
Version
ULFC v1.0 is the initial subject-independent configuration.

Future releases can document additions, refinements, and changes while keeping earlier versions available for reference.
Project principle
Teach clearly. Make it understandable. Help it stick. Adapt to the learner.

ULFC is a reusable starting point for building a more understandable and adaptable learning experience with AI.
