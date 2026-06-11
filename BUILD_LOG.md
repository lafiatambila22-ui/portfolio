# BUILD_LOG.md

## Task 1 — Scaffold repo and CLAUDE.md
- Brief: Create a new GitHub repo and author a CLAUDE.md with project conventions.
- What Claude proposed: A CLAUDE.md documenting single-file HTML/CSS structure, no dependencies, semantic HTML convention.
- What I changed before approving: Nothing, the conventions matched what I wanted.
- Verification: File exists and committed on main.
- One thing I learned: Writing CLAUDE.md first means Claude follows your rules from the first prompt.

## Task 2 — Build index.html
- Brief: Create a single HTML portfolio page with hero, skills, projects, and links sections.
- What Claude proposed: A clean single-file HTML page with all CSS in a style tag.
- What I changed before approving: Nothing, the structure was correct.
- Verification: Opened index.html in browser, all sections visible.
- One thing I learned: Being specific about the color scheme and layout in the brief saves back and forth.

## Task 3 — Add real personal info
- Brief: Update index.html with real name, bio, skills, projects, experience, and links from resume.
- What Claude proposed: Updated all sections with accurate content from the resume.
- What I changed before approving: Nothing, Claude used the info correctly.
- Verification: Opened index.html in browser and confirmed all info is accurate.
- One thing I learned: Pasting structured info into the brief is faster than letting Claude guess.

## AI Workflow
For planning I used Claude.ai chat to decide on the single HTML file approach and talk through what sections to include. For execution I used Claude Code with tight briefs that specified exactly what to build. For polish I used Copilot inline to fix small spacing and naming things. For review I pasted the final HTML into chat and asked for feedback on accessibility and structure.

The moment chat clearly outperformed Claude Code was during the initial design decision. Claude Code would have started building immediately without thinking through the tradeoffs. Chat helped me decide to keep it as a single file with no dependencies before any code was written, which saved time later.

The moment I switched tools mid-task was when I needed to update the content with real resume info. I switched from chat back to Claude Code because Claude Code could directly edit the file while chat would have just given me text to copy and paste.

## Reflection
The agentic workflow let me ship a real portfolio page in under 30 minutes that would have taken me at least two hours alone. The hardest part of building a portfolio solo is usually the CSS and layout decisions. Claude handled all of that while I focused on making sure the content was accurate and the structure made sense.

I had to step in and override Claude when it came to the personal information. Claude did not know anything about me so I had to provide all of it from my resume. That is the part where human knowledge is irreplaceable. Claude knows how to build a portfolio page but only I know what goes in it.

This project revealed that my judgment is strongest when I am giving Claude specific structured input. When my brief was vague Claude made reasonable guesses but they were not always right. When my brief was specific with real names, real projects, and real links Claude got it right the first time. The gap in my knowledge was around CSS layout and design, which Claude filled completely.

On day one of my internship I will start by reading the codebase with Claude Code before writing a single line. I will ask Claude to summarize the repo structure, identify the patterns being used, and draft a CLAUDE.md based on what it finds. That way I am contributing with context from the first day instead of spending a week just reading code.
