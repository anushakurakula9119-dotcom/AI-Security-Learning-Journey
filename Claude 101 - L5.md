Claude 101: **Introduction to Projects**

Beginner-friendly notes from Claude Academy → Claude 101 → Lesson 5 (about 15 min). Source: https://academy.claude.com/courses/claude-101/introduction-to-projects

📑 **Table of Contents**
What is a Project?
Why use Projects?
When should you create one?
Create your first project (step by step)
Writing good project instructions
Building the knowledge base
What is RAG?
Sharing and permissions
Example project ideas
Best practices
Glossary
Quick cheat sheet

🧠 **What is a Project**?

A Project is a dedicated workspace inside Claude for one specific piece of ongoing work.

Think of it like a folder on your desk for one topic. Inside that folder you keep:

Part	                                What it means
💬 **Chats**            	     All conversations related to this topic live together
📚 **Knowledge base**	       Files you upload that Claude can read in every chat
📝 **Instructions**	        Rules telling Claude how to behave in this project

A normal chat starts from scratch every time. A project remembers its files and instructions, so you don't have to explain everything again.

✅ Why use Projects?
No more re-uploading. Upload a file once, and every chat in the project can use it.
Consistent answers. Your instructions (tone, format, style) apply to every chat automatically.
Handles lots of content. Large knowledge bases are managed automatically (see RAG).
Teamwork. On Team/Enterprise plans, you can share a project so everyone works from the same context.
🤔 When should you create one?

Use a project when your work is ongoing, not a one-off question.

Good signs you need a project:

🔁 You keep re-uploading the same documents (reports, notes, guidelines).
🎯 You want Claude to always respond in a certain way (formal tone, cite sources, follow a template).
👥 Multiple people need the same background information.

💡 Rule of thumb: If you'd explain the same background to Claude more than twice, make a project.

🚀 **Create your first project** (step by step)

**Step 1**: Set up the project
Click Projects in the left sidebar (or go to claude.ai/projects).
Click + New Project (top right).
Give it a clear name, e.g. Q4 Marketing Campaign.
Add a short description of your goal.
ℹ️ Claude does not read this description. It's just to help you and teammates remember the purpose.
Choose visibility:
🔒 Private: only you
👥 Shared with your organization: for Team/Enterprise users

**Step 2**: Add instructions

Click Instructions, write your guidance, then click Save instructions.

**Step 3**: Add knowledge

Use the files panel on the right side of the project page and click + to upload.

**Step 4**: Start chatting

Open a new chat inside the project. Claude automatically uses your instructions and files.

Other handy options
⭐ Star a project for quick access
✏️ Edit project details
🗄️ Archive or 🗑️ delete a project
📝 Writing good project instructions

Instructions apply to every chat in the project. They work together with your personal preferences and chosen style.

Good instructions usually cover:

What to include	           Example
**Context**	              "This project is for writing marketing content for our B2B software."
**Process**	              "First plan a blog structure that will interest the audience, then write the draft."
**Tone and style**	      "Professional but conversational. Avoid jargon."
**Specific rules**	      "Always end marketing copy with a call-to-action."

**Bonus**: automate small workflows

You can tell Claude what to do when you give it something specific:

text
When I upload a meeting transcript, create a structured summary
using this template: [Attendees / Decisions / Action items]

💡 Be specific. Vague instructions give inconsistent results.

📚 Building the knowledge base

The knowledge base is the set of files Claude can reference in all chats in the project.

Supported file types: PDF, DOCX, CSV, TXT, HTML and more. You can also connect Google Drive.

**Good things to upload**:

📘 Reference docs: brand guidelines, style guides, templates
🗒️ Background material: research reports, meeting notes, requirement docs
✨ Examples of work you'd like Claude to imitate
🔧 Technical documentation or specifications
🏷️ Pro tip: name files clearly

Claude uses file names to find the right information.

❌ Not helpful	✅ Helpful
document1.pdf	Q4-2025-Brand-Guidelines.pdf
report.pdf	Q4-2025-Sales-Report.pdf
Uploading in a chat vs. uploading to the project
Where you upload	What happens
Project knowledge base	Available in all chats in the project
Directly in one chat	Used only in that conversation, doesn't clutter the knowledge base

⚠️ Context isn't shared between separate chats in a project unless it's added to the knowledge base.

🔍 **What is RAG**? (simple explanation)

RAG = **Retrieval Augmented Generation**.

Imagine a huge textbook. Instead of reading every page before answering a question, you flip straight to the relevant pages. RAG works the same way:

**Your knowledge base is small → Claude reads everything each time.
Your knowledge base gets big and nears the limit → Claude switches to RAG mode.
In RAG mode, Claude searches your files and pulls in only the relevant parts.**

Result: Up to 10x more capacity with similar answer quality. You'll see an indicator when RAG is on, but you don't need to do anything.

👥 Sharing and permissions (Team & Enterprise plans)

This section only applies to Claude for Work users. Individual users can skip it.

Three permission levels
Level	                     Can do
👀 **Can view**	          See contents, use knowledge, chat. Cannot change anything (read-only + chat)
✏️ **Can edit**         	Change instructions, update knowledge, manage members, contribute fully
👑 **Owner** (creator)	   Everything, plus controls who can see the project

**How to share**
Open the project.
Click Share project (next to the project name).
Add people by name or email (you can paste many emails at once), or share with Everyone at [your organization].
Good to know
📧 People get an email notification when you share with them.
📥 Shared projects appear in the Shared with me tab.
🔧 Creators can change or remove access any time.
💬 Chats can be made visible so teammates can build on your work.
💡 Example project ideas

**Project	What you'd upload	What Claude helps with**
🚀 Product launch	Specs, competitor analysis, messaging notes	Drafts and answers with launch context
🔬 Research support	Reviews, user research, customer feedback	Summaries, reports, consistent recommendations
🤝 Client hub	Brand guidelines, past work, communications	Proposals that match the client's tone
🎪 Event planning	Venue contracts, speaker bios, attendee data	Schedules, emails, post-event reports
💼 Job descriptions	Old JDs, team charters, headcount docs	Descriptions that fit your team culture
💰 Personal finance	Budgets and goals	Spending analysis and planning
🏠 Home renovation	Quotes, design ideas, decisions	Budget math and idea generation
🏆 Best practices
Start focused. Make a project for one specific use case, then grow it.
Keep files up to date. Old documents lead to old answers.
Write clear instructions. Specific beats vague.
Name files descriptively and keep related files together.
Mention documents by name in your questions.
Example: "Based on our Q3 report, what were the top customer concerns?"

📖 **Glossary**
Term	                                Meaning
**Project**                   A workspace with its own chats, files, and instructions
**Knowledge base**	           Files uploaded to a project for Claude to reference
**Project instructions**	     Rules guiding how Claude responds in that project
**Context window**	         How much information Claude can handle at once
**RAG**                   	Searching files and using only relevant parts when there's too much to load
**Claude for Work**	        Team and Enterprise plans, which include sharing features

🧾 **Quick cheat sheet**
text
Project = Chats + Knowledge (files) + Instructions

**Create**:   Projects → + New Project → name + description → visibility
**Teach**:    Instructions → write rules → Save instructions
**Feed**:     Files panel → "+" → upload (PDF, DOCX, CSV, TXT...)
**Use**:      Start a chat inside the project
**Share**:    Share project → people or whole org (Team/Enterprise only)

🤔 **Reflection questions**
What ongoing work of mine would benefit from a dedicated project?
Which documents do I keep re-uploading or re-explaining?
If I'm on a team, which projects would benefit from shared knowledge?
