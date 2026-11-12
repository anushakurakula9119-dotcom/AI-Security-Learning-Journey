Claude 101, Lesson 8: **Connecting Your Tools**

Course: Claude 101 (Claude Academy), lesson 8 of 13 Module: Expanding Claude's reach Lesson length: about 15 min (written lesson, no video, no formal exercise)

Source: the lesson page. The "In simple words" lines and analogies marked "my own" are mine. On the page, the "What are connectors?" section has no text and the interactive demo didn't load, so the explanation below comes from the key takeaways and the other sections. The page has no plan-requirements section, so I'm not stating plan limits; I'll check my own account.

**Learning goals**
Explain what connectors are and why they matter for my work with Claude.
Navigate the connectors directory and set up my first connection.
Use connected tools effectively in my conversations with Claude.


1. **What are connectors**?

In simple words: a connector is a link between Claude and another app I use (like my email, files, or task list). Once linked, Claude can see that app's information and sometimes do things in it, so I don't have to copy and paste.

Analogy (my own): without connectors, Claude is a helper locked in a room, and I pass notes under the door. With connectors, I give it keys to specific rooms, and it can look things up itself.

2. **Key takeaways** (from the lesson)
Connectors make Claude an informed collaborator. It can work with the same tools, data, and context I use, so it doesn't start every chat from scratch.
Connectors let Claude read and act. Depending on the permissions I give, Claude can search files, retrieve documents, analyze data, create content, update records, and run tasks in connected apps.
MCP (Model Context Protocol) powers connectors. The page calls it "USB-C for AI": an open, universal standard, so developers can build connectors for many tools.

**Two types of connectors**:
Type	What it is	Examples
Web connectors	Link to cloud services	Google Drive, Notion, Slack, Asana
Desktop extensions	Run locally through the Claude Desktop app and reach local files and native apps	Local file access, browser control, Figma

3. **Finding connectors**
Directory: Anthropic's recommended connectors are at claude.ai/directory, in two tabs:
Web: Gmail, Notion, Slack, Asana, Linear, Stripe, and more
Desktop extensions: local tools that run through the Claude Desktop app
Browse from a chat: click + (lower left of the chat window), then Connectors.
Entries cover services, not single apps. Example: the Atlassian Rovo connector covers both Jira and Confluence, so search "Atlassian."
If a tool isn't listed, add it as a custom connector.

4. **Setting up a web connector** (5 steps)
#	Step
1	Find the connector at claude.ai/directory, or click + > Connectors in any chat
2	Click Connect
3	Authenticate: sign in on that service's login page with my existing credentials
4	Review the permissions it asks for and authorize access
5	Test it: go back to Claude and ask, "Can you access my [tool name]?"

After this, Claude can search, read, and in some cases act in that service, within the permissions I granted.

5. **Setting up a desktop extension** (4 steps)

Needs: the Claude Desktop app on macOS or Windows.

What they can do: local file access (read and organize documents), browser control (automated web tasks), native app integration (Figma for design work).

#	Step
1	Download and install the Claude Desktop app (claude.ai/download)
2	Open the app and go to Settings > Extensions
3	Browse extensions and click Install
4	Complete any setup steps specific to that extension

6. **Using connectors**: example prompts by category
Category	              Tools	                                      Example prompts
**Project management**	    Asana, Linear, Jira	                 "What are my highest priority tasks due this week?" / "Create a new task for reviewing the Q4 budget proposal" / "Summarize the status of our product launch project"
**Communication**       	Slack, Gmail                	     "Find the email thread where we discussed the vendor contract" / "Draft a reply to the latest message in the #marketing channel" / "What did the team decide about the timeline in yesterday's discussion?"
**Documentation**	      Notion, Google Drive, Confluence	       "Search our documentation for our brand voice guidelines" / "Summarize the meeting notes from last week's product review" / "What does our style guide say about using contractions?"
**Business tools**	      Stripe, PayPal, HubSpot	                 "Show me revenue trends for the past quarter" / "What's the status of the Acme Corp opportunity?" / "List recent transactions over $1,000"

(The lesson's interactive demo shows a request where turning on each source adds to what Claude can do. It didn't load in my copy.)

7. **Security and permissions** (important)
Scoped access: permissions match what each connector needs. I can toggle individual permissions in each application's menu.
Claude sees what I see: it can only access data I can access. Connecting my work email doesn't expose anyone else's inbox.
Revocable: I can disconnect through Claude's settings or the other service's security settings.
Be careful with custom connectors: as with Skills, install only connectors from trusted sources.

8. **Practice** (no formal exercise in the lesson)

The closest hands-on parts are the setup steps above.

**My own practice ideas**
 Open claude.ai/directory and look at both tabs (Web and Desktop extensions).
 Choose one low-risk tool I use (for example, a notes or calendar app). Check which permissions it asks for before I click authorize.
 After connecting, ask: "Can you access my [tool name]?"
 Try one read-only request first (for example, "What's on my calendar this week?"), before asking Claude to create or change anything.
 Find where to disconnect it, so I know how to undo it.
**Do-it-yourself checklist**
 Found the directory and the + > Connectors menu
 Read the permissions before authorizing
 Tested the connection with a question
 Tried a read-only request first
 Know how to revoke access

9. **Reflection questions** (answer in my own words)
Which of my daily tools would be most valuable to connect to Claude?
(write here)
What tasks currently need me to copy and paste information that connectors could handle automatically?
(write here)
Are there workflows where combining data from several connected sources would save a lot of time?
(write here)

**Quick revision**
**Connector** = a link between Claude and another app, so Claude can read and act there.
**MCP (Model Context Protocol)** = the open standard behind connectors ("USB-C for AI").
**Web connectors** (cloud apps) vs. Desktop extensions (local, need the Claude Desktop app on macOS or Windows).
**Directory**: claude.ai/directory, or + > Connectors in a chat. No listing? Use a custom connector.
**Setup**: find, Connect, authenticate, review permissions, test.
**Desktop extensions**: install the app, Settings > Extensions, Install, finish setup.
**Security**: scoped permissions, Claude sees only what I can see, revocable, trusted sources only for custom connectors.

**Link to my goals**
Everyday use: connecting a few tools means less copy-paste and answers based on my real information.
AI Security (later): this is one of the most important lessons for security.
Connectors give Claude access to real data and the power to act, which is the Agency idea from AI Fluency.
Anything Claude reads (an email, a document, a web page) could contain hidden instructions (prompt injection). With connectors, that can lead to real actions.
Least privilege (give only the permissions needed), read-only first, review before authorizing, and revoking access are core security habits.
Custom connectors from untrusted sources are a supply-chain risk, like untrusted Skills.
