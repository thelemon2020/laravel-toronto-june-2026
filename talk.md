---
title: "Putting AI in the Driver Seat: AI @ Vehikl"
sub_title: "Laravel Toronto Meetup - June 2026"
author: "Chris Lemon"
---

Overview
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
1. Who? What? Why?
2. AI Tooling
3. The Level of AI Adoption
4. Skills
5. TDD
6. Mob Programming
7. Code Review
8. RAG as a Development Tool
9. Is AI The End of Software Development?
10. Staying True to Yourself in the Age of AI
<!-- end_slide -->

Who?
===
<!-- alignment: center -->
<!-- font_size: 2 -->
Chris Lemon

<!-- column_layout: [3,3] -->
<!-- column: 0 -->

![image](./assets/headshot.jpeg)

<!-- column: 1 -->
<!-- font_size: 3 -->
<!-- incremental_lists: true -->
<!-- list_item_newlines: 3 -->
- Team Lead @ Vehikl
- Meetup Organizer (GPUG)
- Former Archaeologist
- Avid Record Collector
- Bass Player
<!-- end_slide -->


What?
===
<!-- alignment: center -->
<!-- font_size: 3 -->
<!-- jump_to_middle -->
AI @ Vehikl

<!-- end_slide -->


What?
===
<!-- alignment: center -->
<!-- font_size: 2 -->
Vehikl
<!-- column_layout: [3,3] -->
<!-- column: 0 -->

![image](./assets/vehikl-logo.png)

<!-- column: 1 -->
<!-- font_size: 3 -->
<!-- incremental_lists: true -->
<!-- list_item_newlines: 3 -->
- Consultants based out of Waterloo
- Extend and Enhance Existing Teams
- Official Laravel Partner
- Ruby, JS, C#
- Caring, Growth, Delivery
- Mob Programming, TDD
- Pretty Great Place to Work
<!-- end_slide -->

Why? 
===
<!-- alignment: center -->

<!-- pause -->
![image](assets/so-hot-right-now.jpg)

<!-- end_slide -->

Why?
===
<!-- font_size: 2 -->
<!-- incremental_lists: true -->
<!-- list_item_newlines: 3 -->
- N+1 Ways to Use AI
- AI FOMO
- No Wrong Ways to Use AI<sup>*</sup>
- Your workflow doesn't need to change
- Knowledge sharing + Discussion
<!-- end_slide -->

<!-- font_size: 4 -->
<!-- jump_to_middle -->
<!-- alignment: center -->
Disclaimers

<!-- end_slide -->
<!-- font_size: 4 -->
<!-- jump_to_middle -->
<!-- alignment: center -->
These thoughts are my own
<!-- end_slide -->

<!-- font_size: 4 -->
<!-- jump_to_middle -->
<!-- alignment: center -->
I am not an expert


<!-- end_slide -->

<!-- font_size: 4 -->
<!-- jump_to_middle -->
<!-- alignment: center -->
Nobody is an expert

<!-- end_slide -->

The Levels of AI Adoption
===
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
<!-- font_size: 2 -->
1. The Google Replacement
2. Autocomplete
3. Prompting to victory
4. Single Agentic Plan and Implement
5. Multi-agentic workflow
6. Whatever it is Boris Cherny is doing
<!-- new_line -->
"I don't prompt Claude anymore. I have loops running that prompt Claude and figuring out what to do.
My job is to write loops. And this is transition we're going to see for the rest of the year." - Boris Cherny
<!-- end_slide -->

The Levels of AI Adoption
===
<!-- list_item_newlines: 3 -->
<!-- font_size: 2 -->
1. The Google Replacement
2. Autocomplete
3. Prompting to victory
4. Single Agentic Plan and Implement ← This is the goal
5. Multi-agentic workflow
6. Whatever it is Boris Cherny is doing
<!-- new_line -->
"I don't prompt Claude anymore. I have loops running that prompt Claude and figuring out what to do.
My job is to write loops. And this is transition we're going to see for the rest of the year." - Boris Cherny
<!-- end_slide -->

AI Tooling
===
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
<!-- font_size: 2 -->
- No standard at Vehikl
- Choose what works best for the team
- Claude Code, Cursor, Copilot, Windsurf, OpenCode
- Tool does not predetermine outcome
- Personally Claude Code + PHPStorm
<!-- end_slide -->

AI Tooling - cont.
===
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
<!-- font_size: 2 -->
- So many options beyond just Agents
- MCP servers can supercharge your agents
- Laravel Boost is a must
- Most of your favourite tools have MCP servers
- https://mcpservers.org/
- If they don't you can build them!
<!-- end_slide -->


Skills
===
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
<!-- font_size: 2 -->
- Simple but powerful
- Many come with Laravel Boost
- Great for repeated tasks
- AI Equivalent of a bash script
- Analyze your current workflow to find things to automate
<!-- end_slide -->

Skills - Some Examples
===
<!-- font_size: 2 -->
<!-- column_layout: [1, 1] -->

<!-- column: 0 -->
<!-- list_item_newlines: 3 -->
# Start The Day
- Use Linear MCP to get status of all in flight tickets
- Use GitHub MCP to check status of current PRs
- Use Notion MCP to draft up a game plan
<!-- new_lines: 3 -->
# TDD
- Take AC and Plan from Start Ticket
- Scaffold test cases (happy path, sad path, edge cases)
- Get user approval
- Either start TDDing or allow user to take over

<!-- column: 1 -->
# Start Ticket
- Read ticket name and description from Linear MCP
- Check out main, pull latest, open branch based on ticket name
- Summarize ticket, extract acceptance criteria, formulate plan
<!-- new_lines: 3 -->

# Close Out
- Post PR Cleanup
- Determines the current branch
- Checks that branch has been merged
- Checks out main, deletes old branch, closes ticket

<!-- end_slide -->
Skills - cont.
===
<!-- alignment: center -->
<!-- font_size: 3 -->
Need Inspiration?
![image](assets/skillsqr.png)
https://github.com/mattpocock/skills

<!-- end_slide -->
Test Driven Development
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- More important than ever
- AI works best with constraints and structure
- Writing tests first gives AI explicit outcomes
- Catches when AI goes rogue
- Red, Green, Refactor pattern
- Pest architecture tests
<!-- end_slide -->

Mob Programming
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- 3 Developers, 1 Problem
- Work collaboratively to implement features
- Navigator, Driver, Support
- Rotate at regular intervals
<!-- end_slide -->
Mob Programming - Strengths
=== 
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- On-boarding new developers
- Knowledge sharing
- Reduce bus factor risk
- Code quality
- Reduce need for code review
<!-- end_slide -->

Mob Programming - Weaknesses
=== 
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- Not all tasks are appropriate for mobbing
- Requires engagement from all parties
- Junior developers can get left behind

<!-- end_slide -->

Mob Programming - AI
=== 
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- Single agentic workflow is like being a Navigator full time
- Practicing mob programming helps articulate desired outcome
- Gain the ability to reframe and redirect
- Treat the AI as a Driver aka a junior developer
- Record learnings as Memories/Rules
- Extract common patterns to Skills

<!-- end_slide -->


Mob Programming - Advanced AI
=== 
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- Build your own mob with AI Orchestration
- Navigator agent takes in requirement, breaks it down into goals
- Goals are given to Driver agent to implement  
- Driver asks Support agent questions if it gets stuck
- Navigator reviews, reframes and pushes implementation further

<!-- end_slide -->

Code Review
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- Plenty of commercial tools; CodeRabbit, Cursor BugBot, etc.
- Effective, but generate a lot of noise
- Accomplish the same thing locally
- Orchestrator agent + subagents given specific criteria to look for
- AC met, potential bugs, refactor opportunities, test coverage
- Can be turned into a skill once fine-tuned

<!-- end_slide -->

RAG as a Development Tool
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
<!-- column_layout: [1,1] -->

<!-- column: 0 -->
# The Problem
- Colleague has a complex code base
- Total rebuild - vanilla PHP → Laravel
- Many branching paths
- Domain specific terms, acronyms, logic
- How to ensure complex logic isn't missed during rebuild?
<!-- pause -->
<!-- column: 1 -->
# The Solution
- Tokenize the codebase based on identified "signals"
- Summarize code metrics of each "signal" (code branches, nesting, number of function calls)
- Convert to vector embedding
- Build an agent to ask questions to
- Agent retrieves top 20 embeddings that match question, narrows down to 5
- Uses top 5 to generate answer

<!-- end_slide -->

Is AI The End of Software Development?
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- Short answer: no
- Long answer: nooooooooooooo, but things are changing
- Writing code has long been a solved problem
- People, product + organizational problems still need to be solved
- Are we building the right thing in the right way?
- Are we writing our requirements well?
- Are we all rowing in the same direction?

<!-- end_slide -->
Is AI The End of Software Development? - cont.
===
<!-- font_size: 2 -->
# Colin DeCarlo @ Laravel Live Japan
<!-- column_layout: [1,1] -->
<!-- column: 0 -->
![image](./assets/colin.png)
<!-- column: 1 -->
![image](./assets/youtube.png)
https://www.youtube.com/live/TR25AkhjiRc?si=oKnZARfi7lxhWlXD&t=23300  

<!-- end_slide -->

Staying True to Yourself in the Age of AI
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- Things are changing
- AI is a multiplier for good and bad
- Time of readjustment
- Find what works, automate and accelerate
- Throw away what doesn't, see if AI can fill that gap
- Does not need to happen overnight
- Align AI with your core principles
<!-- end_slide -->

Staying True to Yourself in the Age of AI - cont.
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
<!-- column_layout: [1,1,1] -->
<!-- column: 0 -->
# Caring
- Care about our colleagues
- Care about code quality
- Care about our clients
<!-- column: 1 -->
# Growth 
- Junior → Intermediate → Senior Pipeline
- Dedicated time to learn new techniques
- Grow our own AI agents with Skills, Rules and custom tools 
<!-- column: 2 -->
# Delivery
- Solving the right problem in the right way
- Accelerating delivery time
- Improving deliverables

<!-- end_slide -->
Conclusion
===
<!-- font_size: 2 -->
<!-- list_item_newlines: 3 -->
<!-- incremental_lists: true -->
- Many ways to use AI
- Pick what works for you
- Invest time in growth
- Put AI in the driver seat
- Make sure you're still the navigator

<!-- end_slide -->
<!-- alignment: center -->
<!-- font_size: 3 -->
<!-- jump_to_middle -->
Thank you!

<!-- end_slide -->


Shameless Self Promotion
===
<!-- alignment: center -->
<!-- font_size: 2 -->
<!-- column_layout: [1,1,1] -->
<!-- column: 0 -->
![image:width:50%](assets/linkedinqr.png)
https://www.linkedin.com/in/clemon89/
<!-- column: 1 -->
![image:width:50%](assets/gpugqr.png)
https://www.meetup.com/_gpug_/
<!-- column: 2 -->
![image:width:50%](assets/githubqr.png)
Page Object Models for Pest Browser Testing
<!-- end_slide -->
