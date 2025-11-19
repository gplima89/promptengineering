# Getting Started with Prompt Engineering
## A Beginner's Guide

Welcome! If you're new to prompt engineering, this guide will help you get started quickly.

---

## What is Prompt Engineering?

**Simple Definition:** Prompt engineering is the skill of asking AI systems questions in a way that gets you the best possible answers.

**Analogy:** It's like the difference between:
- Asking someone "What's for dinner?" vs.
- Asking "Can you suggest a healthy dinner recipe with chicken that takes under 30 minutes and serves 4 people?"

The second question gives you a much better answer because it's specific!

---

## Why Does It Matter?

The same AI can give you:
- 😞 A vague, unhelpful response (with a poor prompt)
- 😊 An amazing, exactly-what-you-needed response (with a good prompt)

**The AI doesn't change. Your prompt does.**

---

## The 5-Second Rule

Before you hit enter on your prompt, ask:

1. **Who?** - What role should the AI play?
2. **What?** - What exactly do I need?
3. **Why?** - What will I do with this information?
4. **How?** - What format do I want?
5. **How much?** - How detailed should it be?

---

## Quick Start: The Basic Template

```
You are a [ROLE].
[What I need you to do].
Include: [specific things to include].
Format: [how to present it].
```

### Example:
```
You are a project manager.
Summarize these meeting notes.
Include: key decisions, action items with owners, and risks.
Format: Use bullet points and a table for action items.
```

---

## Your First 5 Minutes: Try This Exercise

### Step 1: Read the Sample Data
Open `sample-meeting-notes.md` and skim through it (2 minutes).

### Step 2: Try a Bad Prompt First
Copy the meeting notes and use this prompt with your AI:
```
Summarize this.
```

Look at what you get. Is it useful? Probably not very!

### Step 3: Try a Better Prompt
Now try:
```
You are an executive assistant. Create a concise meeting summary with:
1. Top 3 most important points (2-3 sentences)
2. Action items in a table (task, owner, deadline)
3. Any urgent issues that need immediate attention

Keep it professional and to-the-point.
```

**See the difference?** That's prompt engineering in action!

---

## Common Beginner Mistakes

### ❌ Mistake 1: Being Too Vague
**Bad:** "Tell me about the meeting"
**Better:** "Summarize the key decisions and action items from the meeting"

### ❌ Mistake 2: No Context
**Bad:** "List the tasks"
**Better:** "You are a project manager. Extract all action items from the meeting notes and organize by priority."

### ❌ Mistake 3: No Format Specified
**Bad:** "Give me information about budget"
**Better:** "Create a budget summary table showing: category, planned amount, actual amount, and variance."

### ❌ Mistake 4: No Constraints
**Bad:** "Analyze this" (might get 10 pages!)
**Better:** "Provide a 1-paragraph executive summary and 3 bullet points of recommendations"

### ❌ Mistake 5: Asking Multiple Unrelated Things
**Bad:** "Summarize the meeting and also tell me about quantum physics"
**Better:** Focus on one topic per prompt

---

## The Progressive Improvement Technique

Start simple, then add detail:

### Level 1: Basic
```
Summarize the meeting.
```

### Level 2: Add Structure
```
Summarize the meeting. Include:
1. Key points
2. Decisions made
3. Action items
```

### Level 3: Add Detail
```
Summarize the meeting. Include:
1. Key points (3-4 sentences)
2. Decisions made (bullet points)
3. Action items (table with owner, task, deadline)
```

### Level 4: Add Context and Format
```
You are a project manager preparing a post-meeting summary for the team.

Summarize the meeting. Include:
1. Key points (3-4 sentences highlighting critical issues)
2. Decisions made (bullet points)
3. Action items (table with: task, owner, deadline, priority)

Use professional language and format in markdown.
```

**Pro tip:** You can always start at Level 1, see what you get, then refine!

---

## Your Learning Path

### Week 1: Basics
- ✅ Read this guide
- ✅ Try the 5-minute exercise above
- ✅ Practice with 3-5 different prompts on the sample meeting notes
- ✅ Notice what makes prompts better or worse

### Week 2: Structure
- ✅ Read the main `workshop.md` document
- ✅ Try the Level 1, 2, and 3 examples
- ✅ Compare the outputs
- ✅ Use the `quick-reference.md` templates

### Week 3: Perspectives
- ✅ Try the role-specific prompts (HR, Sales, Engineering, Management)
- ✅ Notice how the same data produces different insights
- ✅ Think about your own role - what prompt would be most useful?

### Week 4: Mastery
- ✅ Apply to your own work documents
- ✅ Build your personal template library
- ✅ Experiment with combinations
- ✅ Share prompts with colleagues

---

## 10 Quick Tips for Better Prompts

1. **Be specific** - "Summarize in 3 sentences" not "summarize"
2. **Set a role** - "You are a [role]" gives context
3. **Define format** - "Use a table" or "Use bullet points"
4. **Give examples** - Show what you want if unclear
5. **Set constraints** - "Maximum 500 words" or "Focus on budget only"
6. **Ask for structure** - "Include: 1) X, 2) Y, 3) Z"
7. **Specify audience** - "For executives" vs. "For technical team"
8. **Request actionability** - "Include recommended actions"
9. **Iterate** - Refine based on what you get
10. **Save good prompts** - Reuse what works!

---

## Simple Prompt Formulas

### Formula 1: Role + Task + Format
```
You are a [role].
[Do this task].
Format: [specify format].
```

### Formula 2: Task + Include + Constraints
```
[Do this task].
Include: [specific elements].
Constraints: [length/focus/style].
```

### Formula 3: Context + Task + Output
```
Context: [situation and background]
Task: [what you need]
Output: [format and structure]
```

---

## Practical Examples for Common Tasks

### Email Summary
```
You are an executive assistant. Summarize this email thread:
1. What's being requested (1 sentence)
2. Who needs to respond
3. Deadline if mentioned
4. Recommended action

Keep it brief - maximum 4 sentences.
```

### Meeting Notes
```
You are a project manager. Create meeting action items:
1. Task description (clear and specific)
2. Assigned person
3. Due date
4. Priority (High/Medium/Low)

Present as a table sorted by priority.
```

### Report Summary
```
You are a business analyst. Summarize this report for executives:
1. Top 3 key findings (1 sentence each)
2. Business impact (2-3 sentences)
3. Recommended next steps (3 bullet points)

Use professional language suitable for C-level.
```

### Research Summary
```
You are a researcher. Summarize these findings:
1. Main topic (1 sentence)
2. Key insights (3-5 bullet points)
3. Practical applications
4. Further questions to explore

Make it accessible for non-experts.
```

---

## Troubleshooting Common Issues

### Problem: Output is too long
**Solution:** Add constraints like "maximum 200 words" or "limit to 3 points"

### Problem: Output is too vague
**Solution:** Be more specific about what you want. Use "Include: [list specific things]"

### Problem: Output is not actionable
**Solution:** Add "Include recommended actions with timelines" to your prompt

### Problem: Output is in wrong format
**Solution:** Specify format clearly: "Use a table" or "Use numbered list" or "Use markdown with headers"

### Problem: Output misses important information
**Solution:** Explicitly list what to cover: "Include: budget, timeline, risks, and resources"

### Problem: Output is too technical (or not technical enough)
**Solution:** Specify audience: "Explain for non-technical executives" or "Use technical terminology for engineers"

---

## Practice Scenarios

Try creating prompts for these real-world scenarios:

### Scenario 1: Team Update
You need to update your team on project status.
- What role should the AI play?
- What sections do you need?
- What format is best for a team email?

### Scenario 2: Budget Review
You need to explain budget variance to your manager.
- What key information must be included?
- How should numbers be presented?
- What level of detail is appropriate?

### Scenario 3: Customer Response
You need to draft a response to a customer complaint.
- What tone should it have?
- What must be addressed?
- What's the desired outcome?

### Scenario 4: Competitive Analysis
You need to analyze competitor movements for your team.
- What perspective is most valuable?
- What format helps comparison?
- What action items should emerge?

---

## Your Prompt Engineering Toolkit

### Essential Resources in This Repository:

1. **This file (getting-started.md)** - Start here for basics
2. **sample-meeting-notes.md** - Practice data to use
3. **workshop.md** - Comprehensive guide with examples
4. **quick-reference.md** - Ready-to-use templates
5. **examples-comparison.md** - Side-by-side quality comparisons

### Recommended Learning Order:

```
1. Read getting-started.md (this file) ← YOU ARE HERE
   ↓
2. Do the 5-minute exercise with sample-meeting-notes.md
   ↓
3. Review examples-comparison.md to see good vs. bad
   ↓
4. Read workshop.md for comprehensive understanding
   ↓
5. Use quick-reference.md templates for your work
   ↓
6. Apply to your own documents and iterate!
```

---

## Success Metrics: How to Know You're Improving

### Week 1 Success:
- ✓ You understand the difference between vague and specific prompts
- ✓ You can write a basic structured prompt
- ✓ You get more useful responses than before

### Month 1 Success:
- ✓ You use role-based prompts naturally
- ✓ You specify format and structure automatically
- ✓ You can adapt prompts for different audiences

### Month 3 Success:
- ✓ You have a personal library of effective prompts
- ✓ You rarely need to ask AI the same thing twice
- ✓ Colleagues ask you for prompt advice
- ✓ You save 2-3 hours per week with better prompts

---

## Final Tips for Success

1. **Start simple** - Don't try to write the perfect prompt on day 1
2. **Iterate** - Refine prompts based on what you get back
3. **Save what works** - Build your personal prompt library
4. **Learn from others** - Use the templates in this repository
5. **Practice regularly** - Like any skill, it improves with use
6. **Be patient** - It takes a few weeks to develop good habits
7. **Have fun** - Experiment and see what works!

---

## Next Steps

**Ready to begin?** Here's your action plan:

1. ✅ **Right now:** Try the 5-minute exercise above
2. ✅ **Today:** Read through `examples-comparison.md`
3. ✅ **This week:** Try 3-5 different prompts with the sample data
4. ✅ **Next week:** Read the full `workshop.md`
5. ✅ **After that:** Apply to your real work!

---

## Questions?

If you're stuck, try:
1. Looking at the `examples-comparison.md` for inspiration
2. Using a template from `quick-reference.md`
3. Reviewing the role-specific examples in `workshop.md`
4. Starting simple and gradually adding detail

---

**Remember:** Every expert prompt engineer started exactly where you are now. The only difference is practice!

You've got this! 🚀
