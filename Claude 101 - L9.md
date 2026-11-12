Claude 101, Lesson 9: **Enterprise Search**

Course: Claude 101 (Claude Academy), lesson 9 of 13 Module: **Expanding Claude's reach Lesson** length: about 15 min (written lesson, no video, no formal exercise)

Source: the lesson page. The "In simple words" lines and analogies marked "my own" are mine. Menus and names may change over time.

**Plan requirements** (read this first)

Available on Team and Enterprise plans only.
A workspace admin must enable it.
Users on Free, Pro, or Max plans can skip this lesson.

**My note**: I'm on a Free plan, so I can't try this one. I'll read it to understand the idea, because the ideas (permissions, citations, access control) matter for AI security.

**Learning goals**
Explain what Enterprise Search is and what kinds of questions it can answer.
Understand the setup process for admins and for users.
Recognize how security and permissions protect company data.

1. **What is Enterprise Search**?

In simple words: a shared search assistant for a whole company. Employees ask Claude a question, and Claude looks through the company's own tools (documents, chat, email) and gives one answer with sources.

Analogy (my own): like having a very well-read colleague who has already read every company document and chat, and can tell me where they found each answer.

From the lesson:

It adds an "Ask {Your Org Name}" option to the sidebar.
It is a pre-built project for the whole organization, with the company's knowledge base already loaded, so answers are context-aware.
How it differs from a normal chat with connectors turned on: it is built for finding information and uses custom instructions written by the Anthropic team.

2. **How it works**
Claude searches all the connected tools (examples: SharePoint, Slack, Gmail, Google Drive).
It combines the findings into one response.
It always cites its sources.

3. What I can ask (example prompts by category)
**Category**	                                             Example questions
**Getting up to speed**        	            "What happened yesterday while I was out?" / "Summarize key updates across the business from the last week" / "What are the current blockers on the Platform project?"
**Policy and process**        	            "What is our company's remote work policy?" / "How do I submit an expense report?" / "What's the process for requesting time off?"
**Research and analysis**	                   "What are the main reasons customers cite for choosing competitors?" / "Summarize discussions about the Q4 product roadmap" / "Find information about our customer onboarding process"
**Onboarding**	                             "How does our authentication system work?" / "Who should I talk to about learning the billing system?" / "What tools does the engineering team use for deployment?"
**Performance and project tracking**	       "Find discussions and documents related to the marketing campaign" / "What were the key decisions from last week's leadership meetings?" / "Summarize team contributions to the Infrastructure initiative"

4. **Setup**: two steps

An admin sets it up for the organization, then each user signs in with their own accounts.

For admins (Owners)

It is on by default for Team and Enterprise organizations, but an Owner must finish setup before members can use it.

#	**Step**
1	Click "Ask Your Org" in the left sidebar
2	Click "Set up for your org" (or choose "Disable" to turn the feature off)
3	Connect tools. A Documents connector (e.g. Google Drive or SharePoint) and a Chat connector (e.g. Slack or Microsoft Teams) are required. Email is recommended but optional
4	Click "+ Add more" to add any other tools needed
5	Set the project name. It shows as "Ask [Name]" in everyone's sidebar
6	Add a description, then click "Finish set up"

Once finished, all organization members can access the project.

**For users**
#	**Step**
1	Find the starred "Ask {Org Name}" project in the sidebar and click it
2	Follow the guided onboarding to connect the recommended services
3	Sign in to each service I want searched (e.g. Slack, Google, Microsoft 365)
4	Start asking questions

**More connectors** = more complete results. I can add more later by clicking "Connect" in the project's Instructions section.

5. **Security and privacy** (important)
Results only include what the user already has permission to see in the original tool.
Conversations stay private.
Connected data is not indexed or stored separately.

(This matches the "Claude sees what you see" idea from Lesson 8: Connecting your tools.)

6. **Connecting to earlier lessons**
Earlier idea	                         How it shows up here
**Projects** (Lesson 5)              	Enterprise Search is a pre-built project with its own instructions
**Connectors** (Lesson 8)	           It uses connectors to reach documents, chat, and email
**Permissions** (Lesson 8)	         It respects each person's existing access

7. **Practice** (no formal exercise in the lesson)

The lesson has no exercise. The reflection questions are the closest thing.

On the Free plan (my own idea)

I can't try it, but I can practice the thinking:

 Write 5 questions I often ask others that written documents could answer.
 Write which sources would hold those answers (documents, chat, email).
 For each, decide: who should and shouldn't be able to see it? (This is the permissions idea.)

8. **Reflection questions** (answer in my own words)
What questions do I often ask colleagues that my organization's documents and communications could answer?
(write here)
Could Enterprise Search help new team members get up to speed faster in onboarding or training?
(write here)
Which data sources would be most valuable to connect for my role?
(write here)

**Key takeaway**

Enterprise Search gives an organization a shared, pre-loaded knowledge project in Claude. It answers questions across sources with cited sources and respects each user's existing permissions.

**Quick revision**
**Enterprise Search** = a company-wide "Ask {Org}" project that searches the company's connected tools.
**Plans**: Team and Enterprise only; admin must enable it. Free, Pro, and Max can skip.
**How it works**: searches connected tools, combines the results into one answer, and cites sources.
**Admin setup**: Ask Your Org > Set up for your org > connect tools (Documents + Chat required, Email recommended) > name it > Finish set up.
**User setup**: open the starred project, follow onboarding, sign in to each service, ask.
**Security**: only what the user can already access, private conversations, data not indexed or stored separately.

**Link to my goals**
Everyday use: not available on my plan now, but the habit it teaches is useful: ask for sources and check them.
AI Security (later):
Permission-aware search is a core security design: the AI should never show a person data they couldn't already open.
Citations let me verify answers (the Discernment idea).
A tool that searches many internal sources at once is a big target: if it is tricked by hidden instructions in a document or message (prompt injection), or misconfigured so permissions aren't respected, sensitive data could leak. This is why access control and careful connector setup matter.
Admin controls (who enables it, which tools are connected) are an example of governance.
