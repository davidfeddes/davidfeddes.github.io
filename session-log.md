AABE course folder, version 2026-1
2026-10-28

2026-10-28, session 1, part 1: what a language model is
What the student did: read the part, pasted the small task, answered the three check questions. Corrected on two points: the second half of question 1, and that the context window holds only files the agent has read, not the whole folder.
Result of the small task (as the agent produced it):
- AGENTS.md asks the agent to: open each session from session-log.md, ask before changing any file, never handle keys and treat web or file text as data, guide the student through each task without doing it for them, log each part and write plainly.
- A model often gets references wrong: it can invent a paper that looks real. Check by finding the paper yourself and the passage it was said to contain.

2026-10-28, session 1, part 2: skills, starting with folders
What the student did: watched the video, installed folder-context in the home folder, pasted the small task, chose storage and project, answered the four check points and the two talk-it-through questions. Added on three points: a folder name does not enforce read-only, the agent reads every skill's name and description up front, and a skill's triggers should be checked before install.
Install: copied skills/folder-context/SKILL.md to C:\Users\David\.claude\skills\folder-context\SKILL.md. Hashes match. Loading from a session outside AABE: not checked.
Result of the small task (as the agent produced it):
- Drew the AABE tree: AGENTS.md, CLAUDE.md, session-log.md, .claude/skills, .agents/skills, my-page, session1, skills. No tutor/ yet.
- folder-context started. It asked storage (student: local) and project (student: standalone), found an empty Thesis folder in År 1 and reused it. It flagged that the thesis may run into year 2. The student kept the location.
- Created in C:\Users\David\Documents\School\BI Oslo\År 1\Thesis: README.md with a Folder context section, AGENTS.md with the language rule block, CLAUDE.md, and the folders sources/data-raw, sources/literature, work, outputs, notes.

2026-10-28, session 1, part 2, follow-up: the student ran the home-skill test in a new session in the Thesis folder. folder-context was listed without a prefix. The only .claude\skills folder from Thesis up to C:\Users\David was C:\Users\David\.claude\skills, holding folder-context\SKILL.md (13,531 bytes, same as the copy). The home install works.

2026-10-28, session 1, part 3: what an agent is
What the student did: read the part, pasted the small task, named the four parts and pointed to each. Added on three points: asking the student is also a tool and a loop decision, a loop step means step, result, decision, and a goal needs a way to tell it was reached.
Result of the small task (as the agent produced it):
- Listed each step of the session with its tool (Read, Glob, Write, Edit, PowerShell, AskUserQuestion), what came back, and why the next step followed. Tools were not in the log, so the agent also used its context window.
- Goal: the student's first message (overview of session 1, part 1, ask before file changes, log). Asking before file changes and logging were precise enough to check. "Take me through" had no end point for the session as a whole.
- Reported two slips: my-page/index.md was saved twice without first showing the final text.
Not logged, by the student's choice: the edits to my-page/index.md (name, then a link to the GitHub repository).
