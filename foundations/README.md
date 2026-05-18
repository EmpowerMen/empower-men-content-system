Foundations

This folder contains the foundational knowledge sources that inform all EmpowerMen content. These materials represent the core psychological, philosophical, and theoretical frameworks that guide our approach to masculine development.

Purpose

The /foundations/ directory serves as:





Source of Truth - Primary reference material for all content creation



AI Agent Knowledge Base - Structured data that AI agents can query and cite



Theoretical Framework - The psychological and philosophical underpinnings of EmpowerMen



Citation Library - Authoritative sources for quotes, concepts, and frameworks

Structure

/foundations/
├── README.md                    (this file)
├── moore-lectures/              Dr. Robert Moore's lecture transcripts
│   ├── README.md
│   ├── INDEX.json
│   ├── transcripts/
│   ├── quotes/
│   └── concepts/
└── core-concepts/               (future) Distilled frameworks and models


Current Contents

Dr. Robert Moore Lectures (/moore-lectures/)

Complete lecture transcripts from Dr. Robert Moore, the neo-Jungian psychologist whose work on masculine archetypes forms the theoretical foundation of EmpowerMen.

What’s included:





Full lecture transcripts with timestamps



Organized by series and topic



Searchable index (INDEX.json)



Curated quotes by theme



Key concepts extracted and explained

Primary frameworks:





The Four Archetypal Energies (King, Warrior, Magician, Lover)



Shadow work and integration



Masculine initiation and development



Archetypal psychology applied to men’s lives

See: moore-lectures/README.md for detailed usage instructions.

How to Use This Folder

For Content Creators

When writing EmpowerMen content:





Reference Moore’s work - Check /moore-lectures/INDEX.json for relevant topics



Use exact quotes - Pull quotes with proper timestamps and citations



Ground concepts - Link your content back to foundational frameworks



Maintain integrity - Ensure content aligns with Moore’s psychological principles

For AI Agents

When generating EmpowerMen content:





Check foundations first - Before creating content on archetypes, shadow work, or masculine development



Cite properly - Use the citation format: Dr. Robert Moore, [Lecture Title] ([timestamp])



Cross-reference - Link concepts across lectures and to EmpowerMen voice/tone



Validate alignment - Ensure generated content reflects Moore’s frameworks accurately

For Developers

When building features or tools:





INDEX.json is your API - Use it for programmatic access to lectures and quotes



Metadata matters - All transcripts include frontmatter for filtering and search



Preserve structure - Maintain the folder hierarchy when adding new content



Version control - Track changes to foundational materials carefully

Citation Standards

Citing Dr. Moore’s Lectures

Format:

> "[Quote text]"
> — Dr. Robert Moore, *[Lecture Title]* ([timestamp])


Example:

> "The King in his fullness is the energy of just and creative ordering."
> — Dr. Robert Moore, *The King Archetype* (00:05:30)


With file reference (for internal documentation):

> "Blessing is the King's primary function."
> — Dr. Robert Moore, *The King Archetype* (00:23:15)
> [Source: `/foundations/moore-lectures/transcripts/kwml/02-king-archetype.md`]


When to Cite

Always cite when:





Using direct quotes from Moore



Explaining archetypal concepts



Discussing shadow work principles



Referencing specific frameworks or models



Making claims about masculine psychology

Citation not required for:





General EmpowerMen brand voice



Your own interpretations or applications



Practical exercises you’ve created



Community-specific terminology

Adding New Foundational Sources

As EmpowerMen grows, you may add additional foundational sources to this folder.

Criteria for Inclusion

A source belongs in /foundations/ if it:





Informs core theory - Shapes how we understand masculine development



Is authoritative - Comes from recognized experts or research



Is referenced frequently - Will be cited across multiple content pieces



Requires structure - Benefits from organized, searchable formatting



Guides content creation - AI agents and writers need to access it regularly

Suggested Future Additions





Jungian Psychology - Carl Jung’s original works on archetypes and shadow



Initiation Literature - Cross-cultural research on masculine rites of passage



Neuroscience of Masculinity - Research on male psychology and development



Philosophy - Stoicism, existentialism, and other relevant philosophical traditions



EmpowerMen Original Research - Surveys, case studies, and community insights

How to Add New Sources





Create a new subfolder: /foundations/[source-name]/



Include a README.md explaining the source and usage



Create an INDEX.json for searchability (if applicable)



Structure content consistently (transcripts, quotes, concepts)



Update this README.md with the new source



Update /governance/glossary.json under foundational_sources



Update AI agent instruction files (CLAUDE.md, AGENTS.md, etc.)

Relationship to Other Folders

/foundations/ vs /shared/





Foundations = Source material and theory (Moore’s lectures, research)



Shared = Operational standards (voice, style, accessibility)

Think of it this way:





Foundations = “What we believe and why”



Shared = “How we communicate it”

/foundations/ vs /skills/





Foundations = Knowledge base to reference



Skills = Workflows for creating content

Example:





Foundation: Moore’s lecture on the King archetype



Skill: Writing a blog post about leadership using the King framework

Integration Example

When an AI agent writes a blog post about masculine leadership:





Check /foundations/moore-lectures/ for King archetype material



Apply /shared/voice.md for EmpowerMen tone



Follow /skills/editorial-and-blog/writing-blog-posts/ workflow



Reference /governance/glossary.json for terminology

Maintenance

Regular Updates





Add new lectures as they’re transcribed



Refine INDEX.json as search patterns emerge



Extract key concepts into /concepts/ for quick reference



Curate quotes by theme as content needs evolve

Quality Standards

All foundational materials must:





Include complete metadata (dates, sources, context)



Use consistent formatting (see individual README files)



Be searchable via INDEX.json or similar



Include proper citations and attributions



Be version controlled with clear commit messages

Governance

Changes to /foundations/ should be:





Reviewed carefully - This is source material, not operational content



Documented - Explain what was added/changed and why



Announced - Let the team know when major sources are added



Validated - Ensure accuracy before committing

Questions?





About Moore’s lectures: See moore-lectures/README.md



About adding sources: Open an issue or discussion in the repo



About citations: Check /governance/glossary.json under foundational_sources



About AI agent access: See CLAUDE.md, AGENTS.md, or .cursorrules



Last Updated: May 18, 2026
Maintained By: EmpowerMen Content Team
Primary Source: Dr. Robert Moore Lectures (1980s-2000s)
