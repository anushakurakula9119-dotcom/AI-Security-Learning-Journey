## AI-Security-Learning-Journey
My learning journey in AI Security, Claude, LLM Security, Cybersecurity, practical labs and projects.

# CLAUDE 101
**What is Claude?**

Imagine a very well-read assistant who has read a huge chunk of the internet, books, and code, and can now write, explain, and reason in response to whatever you type. That’s Claude. Technically it’s an AI model (a “large language model”). It learned patterns in language so well that it can hold a conversation, write an email, or debug code.

A simple chatbot is like a **vending machine: press button A, get snack A**. Claude is closer to a **smart coworker**. You can give it **messy, open-ended problems**, like “help me figure out why my client keeps ghosting me after the quote,” and it works through them with you.

**The key ideas, one by one**

1. **Constitutional AI (how Claude is taught to behave)**
Picture raising a child. You don’t only say “no” each time they misbehave. You also teach them a set of values they can apply to new situations. Anthropic gives Claude a written set of principles (a “constitution”) like avoid harmful or discriminatory outputs, don’t help with illegal or unethical things, and be honest. Claude is trained to follow them. This is the safety side of the lesson, and it’s the part most relevant to your AI Security goal, so remember the term.

2. **Steerable**
Like a radio dial. You can tell Claude “be formal,” “explain like I’m 10,” or “act like a tough interviewer,” and it adjusts. This is why how you ask matters so much.

3. **Capabilities**
The lesson lists writing, research and analysis, coding, problem-solving, and learning.

**_Two terms to know:_**

**Context window:** Claude’s short-term memory for one conversation. Think of a desk. A bigger desk means more documents open at once. The lesson says 200K+ tokens, which is about 500 pages. A token is a small chunk of text, roughly three-quarters of a word. 

[**[!IMPORTANT]**
**Token**: a small piece of a word

Claude doesn’t read whole sentences the way you do. It chops text into tiny pieces first, like cutting a chapati into bite-sized bits before eating. Each bite is a token.

“cat” is 1 token
“unbelievable” might be 3 tokens (“un”, “believ”, “able”)

So a token is just a small piece of text, usually a bit smaller than one word. About 100 tokens is roughly 75 words.

**Context window:** how much Claude can hold in mind at once

Claude has no endless memory inside a chat. It can only keep a certain amount of text “in view” at one time. That limit is the context window.

**Imagine you’re studying at a desk:

A small desk fits two notebooks. You can only look at those two at once.
A big desk fits twenty notebooks. You can compare them all together.**

Claude’s desk is the context window. Everything in your conversation sits on it: your messages, Claude’s replies, and any documents you upload. If something doesn’t fit on the desk, Claude can’t see it.

**What “200K tokens” means**

The lesson says Claude’s desk holds about 200,000 tokens. That’s roughly 150,000 words, or about 500 pages of a book. So you could upload a whole long report, or a few of them, and ask Claude, “What are the main points?” and it can look at all of it together.]

**Thinking**: Claude can answer instantly, or “think first,” working through a hard problem step by step, like a student writing out the math instead of blurting an answer.

4. **Learning mode**
Instead of handing you answers, Claude guides your reasoning, like a tutor who asks “what do you think the next step is?” Useful for you while learning.

5. **Ways to access Claude**
It’s the same brain in different places:

Claude.ai (web, desktop, mobile): chatting, writing, research. This is where you’ll start.
Claude Code: for developers. It can edit files and run commands on a computer.
Claude Tag: Claude inside Slack.
Claude Design: turns ideas into interface prototypes.
Claude for Microsoft 365: Claude inside Word, Excel, PowerPoint, and Outlook.
Why this matters for AI Security

Everything above is something that can be attacked or protected. The context window is where “prompt injection” attacks hide. Steerability is what “jailbreaks” try to abuse. And Constitutional AI is one defense. You’ll meet those later, and knowing the basics now makes them easy.
