Claude 101, Lesson 7: **Working with Skills**

Course: Claude 101 (Claude Academy), lesson 7 of 13 Module: **Organizing your work and knowledge** Lesson length: about 15 min (written lesson, no video, no formal exercise)

Source: the lesson page. The "In simple words" lines and analogies marked "my own" are mine. Menus and names may change over time. 

**Learning goals**
Explain what Skills are and how Claude uses them.
Identify Anthropic's built-in Skills for creating documents.
Enable and manage Skills in settings.

**Plan availability**
Skills are a feature preview for **Pro, Max, Team, and Enterprise plans**.

**Free plan**: I can read the lesson to understand the idea, but should skip the hands-on steps.
1. **What are Skills**?

In simple words: **a Skill is a saved "how to do this job" package that Claude opens only when a task needs it**.

Analogy (my own): a recipe card. Claude is a good cook, but a recipe card for my favourite dish makes it come out the same way every time.

**From the lesson**:

**Skills are bundles of instructions, scripts, and resources that Claude loads on demand to do specialized tasks better**.
The lesson calls them **"expertise packages"** that teach Claude to complete specific tasks in a repeatable way.
Skills already work behind the scenes when Claude creates Excel, PowerPoint, Word, or PDF files.
Custom Skills can capture whole repeatable workflows, such as a quarterly variance analysis, a brand voice review, or a compliance checklist.

(This is the "Skills" idea mentioned in Lesson 2 under Personalizing Claude.)

2. **Two types of Skills**
Type	                       Who makes it	                                    What it does	                                                                                                                How it's used
**Anthropic Skills**     	Anthropic builds and maintains them	           Better document creation for Excel, Word, PowerPoint, and PDF	Available to all paid users.                                       Claude uses them automatically when relevant
**Custom Skills**          	Me or my organization                      	Specialized workflows, e.g. apply brand guidelines to presentations, format meeting notes, run a data analysis workflow	             Appear in the same list as built-in Skills. Claude uses them automatically on relevant tasks

3. **Turning Skills on**
Go to Settings > Capabilities.
Make sure Code execution and file creation is on. (Skills need Claude's sandboxed computing environment, a safe, closed workspace.)
Scroll to the Skills section.
Toggle individual Skills on or off.

**Plan notes**:

**Enterprise**: Organization Owners must first enable both Code execution and Skills in Admin settings before members can use them.
**Team**: on by default at the organization level.

Once on, Skills show in settings, including Anthropic's built-in ones and any custom Skills I've uploaded.

4. **Using Skills in practice**
I usually don't need to call a Skill myself. Claude picks it based on my request.
When Claude uses a Skill, it shows up in Claude's chain of thought (its visible thinking steps) while it works.
The result is a downloadable file I can save locally or to Google Drive.

**Example prompts that use Skills**:

"Create an Excel spreadsheet tracking monthly expenses with formulas for totals."
"Turn this meeting notes document into a PowerPoint presentation."
"Generate a PDF report summarizing this data."
"Build a financial model in Excel with scenario analysis."
File execution (working with real files)
Claude can work with my actual files (slides, spreadsheets, contracts, or .xlsx, .pptx, .docx, .pdf) inside a contained environment.
It can analyze, create slides, and suggest edits.
In Chat, Claude creates a new version of the document. It does not edit the original.
Download the files, or open them in Drive, when finished.
Tip: turn on **"Allow limited network access"** when Claude asks, because it needs to reach external data sources.

5. **Security considerations** (important)
Only install custom Skills from trusted sources.
Anthropic's built-in Skills are tested and maintained by Anthropic.
Custom Skills I upload are private to my own account.
Review the contents of any outside Skill before using it, because Skills can include executable code (programs that run).

6. **Creating a custom Skill** (no coding needed)

The lesson stresses I don't need to write code or make files by hand. Claude builds the structure for me.

Step	                                                                             What I do
1. **Start a new chat**	                                             Describe the Skill: "I want to create a skill for writing quarterly business reviews" or "a skill that applies our brand guidelines to presentations"
2. **Answer Claude's questions**	                                   Claude interviews me: What should the Skill do? What does good output look like? When will I use it? Can I give examples?
3. **Upload reference materials** (if I have them)	                  Templates, style guides, brand assets, work examples
4. **Save the Skill**	                                                 Claude creates a properly structured file. Saving makes it ready to use

**Managing my Skills**:

Open the Customize tab in the left sidebar to see my available Skills.
I can edit them by hand or by chatting with Claude.
To improve a Skill, ask Claude to edit it, and it will update the files.

7. **Skills vs. Projects**

**Guiding idea**: Projects store knowledge. Skills perform tasks.

**Analogy** (my own): a project is a library shelf (information). A skill is a recipe (steps). A good cook uses both: the shelf supplies the ingredients, the recipe says what to do.

	                         **Projects**	                                                                       **Skills**
**Purpose**	                  Store knowledge                                                          Claude refers to	Define processes Claude carries out
**Best for**	               Long-term context, reference materials, team collaboration	         Repeatable workflows, multi-step tasks, consistent method
**Example**                 	Customer hub, research buddy, feedback generator	                 Brand or legal guidelines, blog drafting, PDF creation
**Persistence**             	Knowledge available in all chats in the project	                             Instructions applied when the Skill is used

**Projects hold reference material (specs, meeting notes, research). Skills are procedural: steps, order, and method, so the process runs consistently.
They work together. Example: a "customer call prep" Skill can use customer profiles stored in a project. The project supplies the information, and the Skill supplies the process.**

8. **Practice** (no formal exercise in the lesson)

The closest hands-on parts are turning Skills on and creating a custom Skill. These need a paid plan.

**On the Free plan** (my own ideas)
 Read the "Security considerations" section again and note the 4 rules.
 Write down one repeatable job I do and the steps (this is the "interview" Claude would ask me).
 Practice the interview in a normal chat: ask Claude "Interview me, one question at a time, to design a step-by-step process for [my task]." Keep the result as a plan for a future Skill.

Ideas for my own Skills (for later, on a paid plan)
**Skill idea**	                    **What it would do**
**Follow-up email writer**	        Draft a friendly 100-word follow-up in my style
**Study notes formatter**	          Turn lesson text into my GitHub notes format (goals, simple words, quick revision, link to goals)
**Resume summary helper**         	Rewrite resume points in a clear, plain style

**Do-it-yourself checklist** (paid plan)
 Settings > Capabilities: Code execution and file creation on
 Toggled on the Skills I want
 Asked Claude for an Excel/PowerPoint/Word/PDF file and noticed the Skill in its thinking
 Created one custom Skill by answering Claude's questions
 Found it in the Customize tab

9. **Reflection questions** (answer in my own words)
What kinds of documents do I create regularly that could benefit from Anthropic's built-in Skills?
(write here)
Which repetitive workflows in my work could be good custom Skills?
(write here)
How might Skills change the way I create documents and analyze data?
(write here)

**Key takeaways**
Skills are reusable expertise packages that Claude loads when a task calls for them.
Anthropic Skills handle document creation automatically. Custom Skills capture my own workflows.
Skills need Code execution and file creation turned on. Plan rules vary (Enterprise needs admin enablement; Team is on by default).
Projects hold knowledge. Skills define process. They work best together.
Use trusted custom Skills only, and review outside Skills before using them.

**Quick revision**
Skill = saved instructions, scripts, and resources Claude loads on demand.
2 types: Anthropic (Excel, Word, PowerPoint, PDF) and Custom (mine).
Turn on: Settings > Capabilities > Code execution and file creation, then toggle Skills.
Plans: Pro, Max, Team, Enterprise (feature preview). Free: read only.
Create: describe it, answer Claude's questions, upload references, save. Manage in Customize.
In Chat, Claude makes a new version of a file. It doesn't edit the original.
Security: trusted sources only; review outside Skills; they can contain code.
Projects = knowledge. Skills = process.

**Link to my goals**
Everyday use: Skills mean I explain a job once and Claude repeats it the same way later.
AI Security (later): this lesson is a supply-chain security lesson in small form.
A Skill can contain executable code, so a malicious Skill is a real risk.
"Only trusted sources" and "review before use" are core security habits.
It also connects to Delegation and Diligence from AI Fluency: I decide what to hand over and I stay responsible.
