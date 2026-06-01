<<<<<<< HEAD
Project: Physical AI & Humanoid Robotics Textbook

Purpose:
Create a complete, AI-native textbook that teaches Physical AI, humanoid robotics, embodied intelligence, and simulation-based robotics using ROS 2, Gazebo, Unity, NVIDIA Isaac, and VLA. The constitution defines the rules, standards, and boundaries for producing the book through specification-driven development.

Core Principles:
- Accuracy: All robotics, simulation, and AI concepts must be verified against official documentation or primary sources.
- Clarity: Content must be understandable for intermediate university students and beginner roboticists.
- Learnability: Each chapter must have learning objectives, outcomes, checkpoints, and practical exercises.
- Consistency: Follow a single writing voice, formatting style, and structure across the entire book.
- Modularity: Chapters must be independent but connect logically across the curriculum.
- AI-Nativity: Content must be optimized for Docusaurus, Claude Code, and RAG-based future learners.

Key Standards:
- Format: Markdown (MDX allowed for Docusaurus components).
- Structure: Chapters → Sections → Subsections → Exercises → Checkpoints.
- Book Metadata: Each file must include frontmatter for future RAG indexing.
- Visuals: Diagrams allowed (ASCII, Mermaid, or references to images).
- Technical Accuracy: ROS 2, Gazebo, Unity, and Isaac examples must follow official current versions.
- Teaching Style: Practical, hands-on, challenge-driven learning.

Constraints:
- Total chapters: 15–25.
- Word count per chapter: 1,000–3,000 words.
- Only use tools and concepts from the actual course modules.
- No invented hardware specs; must match real humanoid robotics principles.
- Do not include long mathematical derivations unless essential for understanding.
- Book must be fully buildable in Docusaurus and deployable to GitHub Pages.

Not Building:
- A full ROS 2 or Isaac SDK manual.
- A generic AI or robotics encyclopedia.
- Product/vendor comparisons.
- A hardware buying guide.
- A backend system for RAG (separate project).
- A course grading system or teaching plan.

Success Criteria:
- Complete 4-module coverage + Intro + Capstone + Appendix.
- All chapters follow the same structure and metadata scheme.
- Explanations are accurate, modern, and aligned with official documentation.
- Book compiles cleanly in Docusaurus without errors.
- Each chapter includes: examples, diagrams, checkpoints, and a small assignment.
- Readers can understand and build humanoid robotics simulations by the end.

Deliverables:
- Constitution (this file)
- Specification (sp.specify)
- Book master plan (sp.plan)
- Chapter outlines
- Markdown source files for all chapters
- Simulation labs and capstone instructions
- Final Docusaurus-ready book repo
=======
# [PROJECT_NAME] Constitution
<!-- Example: Spec Constitution, TaskFlow Constitution, etc. -->

## Core Principles

### [PRINCIPLE_1_NAME]
<!-- Example: I. Library-First -->
[PRINCIPLE_1_DESCRIPTION]
<!-- Example: Every feature starts as a standalone library; Libraries must be self-contained, independently testable, documented; Clear purpose required - no organizational-only libraries -->

### [PRINCIPLE_2_NAME]
<!-- Example: II. CLI Interface -->
[PRINCIPLE_2_DESCRIPTION]
<!-- Example: Every library exposes functionality via CLI; Text in/out protocol: stdin/args → stdout, errors → stderr; Support JSON + human-readable formats -->

### [PRINCIPLE_3_NAME]
<!-- Example: III. Test-First (NON-NEGOTIABLE) -->
[PRINCIPLE_3_DESCRIPTION]
<!-- Example: TDD mandatory: Tests written → User approved → Tests fail → Then implement; Red-Green-Refactor cycle strictly enforced -->

### [PRINCIPLE_4_NAME]
<!-- Example: IV. Integration Testing -->
[PRINCIPLE_4_DESCRIPTION]
<!-- Example: Focus areas requiring integration tests: New library contract tests, Contract changes, Inter-service communication, Shared schemas -->

### [PRINCIPLE_5_NAME]
<!-- Example: V. Observability, VI. Versioning & Breaking Changes, VII. Simplicity -->
[PRINCIPLE_5_DESCRIPTION]
<!-- Example: Text I/O ensures debuggability; Structured logging required; Or: MAJOR.MINOR.BUILD format; Or: Start simple, YAGNI principles -->

### [PRINCIPLE_6_NAME]


[PRINCIPLE__DESCRIPTION]

## [SECTION_2_NAME]
<!-- Example: Additional Constraints, Security Requirements, Performance Standards, etc. -->

[SECTION_2_CONTENT]
<!-- Example: Technology stack requirements, compliance standards, deployment policies, etc. -->

## [SECTION_3_NAME]
<!-- Example: Development Workflow, Review Process, Quality Gates, etc. -->

[SECTION_3_CONTENT]
<!-- Example: Code review requirements, testing gates, deployment approval process, etc. -->

## Governance
<!-- Example: Constitution supersedes all other practices; Amendments require documentation, approval, migration plan -->

[GOVERNANCE_RULES]
<!-- Example: All PRs/reviews must verify compliance; Complexity must be justified; Use [GUIDANCE_FILE] for runtime development guidance -->

**Version**: [CONSTITUTION_VERSION] | **Ratified**: [RATIFICATION_DATE] | **Last Amended**: [LAST_AMENDED_DATE]
<!-- Example: Version: 2.1.1 | Ratified: 2025-06-13 | Last Amended: 2025-07-16 -->
>>>>>>> 391d81e (Initial commit from Specify template)
