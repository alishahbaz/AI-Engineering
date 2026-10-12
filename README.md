# AI-Engineering# AI-Native Software Engineering — GitHub Wiki

Copy-ready Markdown pages for a GitHub Wiki, based on a 10-chapter transcript about AI coding agents, spec-driven development, engineering orchestration, context, automation, and security.

## Where files go

**GitHub Wiki:** Put `Home.md`, the topic `.md` pages, `_sidebar.md`, `_header.md`, and `_footer.md` in the **root of the Wiki Git repository** (the repository ending in `.wiki.git`).

**Main code repository (optional):** Put `README.md` in the root of the normal repository. GitHub Wikis use **`Home.md` as their landing page**, not `README.md`.

## Install (Git clone method)

1. Enable Wiki in the repository settings if needed, then create an initial Wiki page to initialize it.
2. Clone the Wiki repository: `git clone https://github.com/OWNER/REPO.wiki.git`.
3. Copy `Home.md`, `_sidebar.md`, `_header.md`, `_footer.md`, and all topic pages into the clone's root.
4. Run `git add . && git commit -m "Add AI engineering wiki" && git push`.
5. Open `https://github.com/OWNER/REPO/wiki` and test sidebar navigation.

You can also create/edit each page in the GitHub Wiki web editor. Use each filename's basename as the Wiki page title (GitHub generally turns spaces into dashes in page URLs).

## Pages

- [Home](Home.md)
- [The Big Picture](The-Big-Picture.md)
- [AI Coding Inflection Point](AI-Coding-Inflection-Point.md)
- [Spec-Driven Development](Spec-Driven-Development.md)
- [Developer as Conductor](Developer-as-Conductor.md)
- [Context and Loop Engineering](Context-and-Loop-Engineering.md)
- [How LLMs Work](How-LLMs-Work.md)
- [Skills, Automations and Sub-Agents](Skills-Automations-and-Sub-Agents.md)
- [Agent Security](Agent-Security.md)
- [Future of Software Engineering](Future-of-Software-Engineering.md)
- [Implementation Playbook](Implementation-Playbook.md)
- [Glossary](Glossary.md)

## Navigation and diagrams

Wiki pages use normal relative links (e.g., `[Next](Agent-Security)`) and/or Wiki links (`[[Agent Security]]`). This package uses relative links for previous/next controls and Wiki links for references, all targeted at included pages. Mermaid diagrams are fenced with `mermaid` and render on GitHub where Mermaid is supported.

## Content integrity

Speaker opinions and anecdotes are attributed. Additional templates, checklists, and security best practices are labeled as practical guidance rather than claims made in the transcript.
