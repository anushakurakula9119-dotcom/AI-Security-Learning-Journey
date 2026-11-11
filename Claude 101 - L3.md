Claude 101, Lesson 3: **Getting Better Results**

Course: Claude 101 (Claude Academy), lesson 3 of 13 Lesson length: about 10 min

Source: the lesson page (text, video summary, exercise, reflection). Analogies and example prompts marked "my own" are mine, in simple words.

**Learning goals**
Spot common problems when starting with AI and fix them with simple techniques.
Define AI Fluency and know where to learn more.
Explain how to set up evals (simple tests) to see how well Claude does on my own tasks.

1. **The big idea**

A not-so-good first answer is normal. It's a chance to improve my instructions, not a sign that Claude "doesn't work."

2. **Five common problems and how to fix them**
   
Problem	                                    Why it happens	                                                                                                  The fix
**Too generic**	                 My prompt didn't give enough about my situation	                                                                        Add details: who the audience is, my role, and any limits
**Too long or too short**        	Claude is guessing the length	                                                                                        Say the length: "two paragraphs," "under 100 words," or "as detailed as needed"
**Format not followed**	           Claude got the content but not the layout	                                                                          Show an example of the format, or describe the structure (e.g. "bullet points with a bold heading for each")
**Confident but wrong**	          Claude can write believable but incorrect details, especially specific facts or niche topics	                        Check important facts myself. Ask for sources or a confidence level. Turn on web search to use current information
**Wrong tone**	                  Claude defaults to helpful and professional                                                                            	Describe the tone in plain words ("more conversational," "formal and authoritative") or paste a writing sample

Example of fixing "too generic" (from the lesson, shortened)
**Weak**: "Write an email about the project delay."
**Strong**: names the audience (an enterprise client), the facts (a two-week delay in integration, then a second delay), and the tone (professional but apologetic).
My own example
**Weak**: "Write a message to my teacher."
**Strong**: "I'm a student who missed class due to illness (stage). Write a polite message asking for the notes and a new deadline (task). Under 60 words, respectful tone (rules)."

3. **The iteration mindset**

The first prompt starts a conversation. It's not a one-shot request.

**Treat first drafts as starting points. Notice what works and what doesn't, then refine.
Give specific feedback. "Make it shorter" works, but "cut the second paragraph and make the ending ask for a reply" works better.
Know when to start fresh. If the chat drifted off, a new chat with a clearer prompt can be faster than steering it back.**

4. **What is AI Fluency?**

AI Fluency = the ability to work well with AI: not just knowing where the buttons are, but having the judgment to use it well in different situations. It comes from the 4D Framework, created by Professors Rick Dakan and Joseph Feller (the one I already studied).

D	                              In simple words
**Delegation**	           Decide what I do, what AI does, and how to split the work
**Description**	          Communicate clearly with AI (what I want, how to do it, how to behave)
**Discernment**	          Check AI's output, reasoning, and behavior for quality and accuracy
**Diligence**	             Use AI responsibly, be transparent, and take accountability

How it connects to this course:

The Lesson 2 prompt checklist (stage, task, rules) = Description.
The troubleshooting techniques above = Discernment and Diligence.
Learn more in the free AI Fluency course on Claude Academy (the one I've just finished).

5. **Evals**: how do I know if Claude is good at my task?

Eval = short for evaluation: a test of how well Claude does on my own tasks.

Why bother? My work is unique. Claude may be great at marketing copy but need more help with technical documents. A simple test helps me:

Find where Claude is most useful.
See which tasks need more context or examples.
Build confidence for tasks I repeat.

Analogy (my own): trying on shoes before buying a pair. Test first, then trust.

A simple eval in 4 steps (no special tools needed)
**Gather examples**: 5 to 10 samples of a regular task (emails, reports, analyses).
**Create test prompts**: write prompts that would produce similar results, with the context I'd normally give.
**Compare outputs**: Did Claude get the key information? Does the tone fit? What's missing?
**Refine**: adjust the prompts, add examples of good output, or note where a human must always review.

6. Example in the lesson: Rio's data analysis

Rio is a program director at a veterans' services nonprofit. Every quarter he spends hours analyzing attendance vs. employment results. He tests Claude using last quarter's data, where he already knew the right answers.

The loop he used (the page calls it the **"delegation diligence loop"**)

**Delegate**: pick a specific, regular task.
**Use past data**: choose data whose correct analysis I already know, so I can judge Claude's work.
**Reproduce and evaluate**: have Claude redo my past analysis, and check each answer against what I know is true.
**Refine and retest**: some gaps are fixed by better description (and go into future prompts). Others are real limits.
**Decide**: if Claude matches my known results, I can trust it for similar future work. If it doesn't after several tries, I've learned not to delegate that task.

What happened
**Result 1**: Claude found the right attendance-and-job-placement link but missed something about the combined housing and job program.
Fix: Rio asked Claude to try again, paying attention to program type. Claude caught it. Rio noted: always mention program type in future.
**Result 2**: Rio asked for a view by enrollment date. Claude didn't have that data and would have tried to guess it, which Rio didn't want. Rio noted it for later checking.
Outcome: Claude can reproduce his manual analysis with the right description, he knows its limits, and he has notes on what context to give.
Ongoing responsibility (Diligence)

With new data, Rio still checks that numbers make sense, takes accountability for the final report, and is open about AI's role if asked. Testing builds confidence but doesn't remove responsibility.

If I'm not comfortable with data

Claude can brainstorm solutions, write Excel formulas, and tidy messy data. Ask it to explain its steps, as I would with a data analyst on my team, so I can follow along.

This approach works for any analysis task (budgets, surveys, tracking results, and so on): test first, then trust more, or learn what not to delegate.

7. **Practice** (the lesson's exercise)
Find a dataset I've analyzed manually.
Ask Claude to do the same analysis.
Compare Claude's results with mine.
Note patterns and refine the prompt (for example, Claude may get the numbers right but miss the overall pattern).

**Goal**: build a feel for working with Claude and know where to focus my checking.

If I don't have a dataset (my own alternative)
Test on a task I already know well. Example: take an email or message I wrote before, describe the same situation to Claude, and compare its version with mine. Does it capture the key points? Is the tone right? What's missing?
Test the fixes: write a deliberately weak prompt, then apply the five fixes one at a time, and watch how the answer improves.


**Do-it-yourself checklist**
 Fixed a "too generic" answer by adding audience, role, and limits
 Asked for a specific length
 Asked for a specific tone, or pasted a writing sample
 Asked Claude for sources, and checked one myself
 Ran one mini eval with a task I already know the answer to

**Key takeaways**
A weak first answer is normal; refine it.
Context, length, format, and tone instructions fix most problems.
Verify facts in high-stakes work.
AI Fluency rests on the 4Ds: Delegation, Description, Discernment, Diligence.
Evals on known past work show where Claude is reliable and where a human must review.

**Quick revision**
5 fixes: add context, state length, show the format, verify facts (ask for sources, turn on web search), describe the tone.
Iterate: specific feedback beats vague feedback; start fresh if the chat drifts.
Eval = a simple test of Claude on my own tasks: gather 5 to 10 examples, test prompts, compare, refine.
Rio's loop: delegate, use known data, reproduce and check, refine and retest, decide.
I'm still responsible for the final result.

**Link to my goals**
Everyday use: the five fixes make everyday prompts work better.
AI Security (later): "confident but wrong" answers (hallucinations) are a real risk, and evals are how teams test AI systems before trusting them. **Testing before trusting is a core security habit.**
