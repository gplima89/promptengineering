# Quick Reference: Prompt Templates

This file provides ready-to-use prompt templates that you can copy and customize for your own needs.

---

## Template 1: Basic Analysis

```
Analyze the following [document type] and provide:

1. A concise summary (3-4 sentences)
2. Key takeaways (3-5 bullet points)
3. Action items with owners and deadlines

[Paste your content here]
```

---

## Template 2: Executive Summary

```
You are a senior executive preparing a board-level summary. Review the content below and create:

1. Executive Summary (4-5 sentences highlighting critical issues)
2. Key Metrics (quantitative data points)
3. Top 3 Risks with mitigation strategies
4. Recommended actions with expected outcomes

Format professionally for board presentation.

[Paste your content here]
```

---

## Template 3: Task Extraction

```
Extract all action items from the following content and create a prioritized task list including:

- Task description
- Assigned person
- Due date
- Priority (Critical/High/Medium/Low)
- Dependencies
- Estimated effort

Present in a table format.

[Paste your content here]
```

---

## Template 4: HR Perspective

```
You are an HR Business Partner analyzing workforce implications. Review the content and provide:

1. Team Health Assessment
   - Engagement and morale indicators
   - Capacity utilization
   - Retention risks

2. Staffing Analysis
   - Current gaps
   - Short-term needs
   - Long-term planning

3. HR Action Plan
   - Immediate actions (next 7 days)
   - Short-term initiatives (next 30 days)
   - Success metrics

Focus on employee wellbeing and organizational health.

[Paste your content here]
```

---

## Template 5: Sales Perspective

```
You are a Sales Director assessing business impact. Analyze the content for:

1. Competitive Threat Assessment
   - Market positioning
   - Feature gaps
   - Competitor movements

2. Revenue Impact
   - At-risk revenue (quantify)
   - Opportunity cost
   - Customer churn risk

3. Sales Enablement Strategy
   - Talking points for customers
   - Competitive positioning
   - Account prioritization

4. Go-to-Market Adjustments
   - Messaging recommendations
   - Retention programs
   - Pricing considerations

Present as sales strategy brief.

[Paste your content here]
```

---

## Template 6: Engineering Perspective

```
You are an Engineering Lead conducting technical review. Analyze the content and provide:

1. Technical Delivery Status
   - Completion percentage by feature
   - Technical challenges and blockers
   - Quality risks

2. Resource & Capacity Analysis
   - Team utilization
   - Skill gaps
   - Sustainable workload assessment

3. Timeline Revalidation
   - Critical path analysis
   - Risk buffer recommendations
   - Milestone checkpoints

4. Technical Prioritization
   - Must-have vs. nice-to-have
   - Effort estimates
   - Architecture decisions needed

Focus on realistic commitments and technical trade-offs.

[Paste your content here]
```

---

## Template 7: Management Perspective

```
You are a CEO preparing strategic decisions. Synthesize the content into:

1. Executive Situation Summary
   - Current state (Green/Yellow/Red indicators)
   - Critical issues
   - Strategic implications

2. Key Decisions Required
   - Options analysis (2-3 alternatives per decision)
   - Resource requirements
   - Risk assessment
   - Recommended path forward

3. Cross-Functional Alignment
   - Department conflicts
   - Integration needs
   - Leadership interventions

4. 30-60-90 Day Roadmap
   - 30 days: critical actions
   - 60 days: key deliverables
   - 90 days: strategic objectives

5. Stakeholder Communication Plan
   - Board messaging
   - Customer communication
   - Team updates

Format as board-ready strategic brief.

[Paste your content here]
```

---

## Template 8: Risk Analysis

```
Conduct comprehensive risk analysis of the following content:

1. Risk Identification
   - List all risks mentioned or implied
   - Categorize by type (operational, financial, strategic, technical)

2. Risk Assessment Matrix
   Create table with: Risk | Likelihood | Impact | Severity | Mitigation

3. Top 5 Critical Risks
   - Detailed analysis of highest severity risks
   - Root cause analysis
   - Cascading effect analysis

4. Mitigation Strategies
   - Immediate actions (next 7 days)
   - Short-term plans (next 30 days)
   - Long-term strategies (next quarter)
   - Success metrics for each

5. Contingency Planning
   - Worst-case scenarios
   - Response protocols
   - Communication plans

[Paste your content here]
```

---

## Template 9: Customer Impact Analysis

```
You are a Customer Success Manager evaluating customer implications. Review the content and provide:

1. Customer Impact Summary
   - Affected customer segments
   - Severity of impact
   - Timeline of effects

2. At-Risk Accounts
   - List of high-value accounts at risk
   - Reason for risk
   - Estimated revenue impact
   - Priority level

3. Customer Communication Plan
   - Key messages
   - Communication channels
   - Timing strategy
   - FAQ preparation

4. Retention Strategy
   - Proactive outreach plan
   - Compensation/concessions if needed
   - Success story development
   - Escalation procedures

5. Voice of Customer Integration
   - Customer feedback themes
   - Feature request prioritization
   - Satisfaction improvement opportunities

[Paste your content here]
```

---

## Template 10: Financial Analysis

```
You are a CFO reviewing financial implications. Analyze the content for:

1. Budget Variance Analysis
   - Planned vs. actual by category
   - Variance explanation
   - Trend analysis

2. Financial Impact Assessment
   - Revenue implications
   - Cost implications
   - Cash flow impact
   - ROI calculations

3. Reallocation Recommendations
   - Budget optimization opportunities
   - Reallocation proposals
   - Investment priorities
   - Cost reduction areas

4. Financial Forecast
   - Q1 projection based on current trajectory
   - Best/worst/likely case scenarios
   - Risk-adjusted forecasts

5. Financial Controls
   - Recommended approval processes
   - Spending limits
   - Monitoring mechanisms
   - Reporting frequency

Present in format suitable for board financial review.

[Paste your content here]
```

---

## Customization Tips

### Adjusting Detail Level
- **High-level:** "Provide executive summary in 3-4 sentences"
- **Detailed:** "Provide comprehensive analysis with supporting data"
- **Technical:** "Include technical specifications and implementation details"

### Adjusting Output Format
- **Narrative:** "Write in paragraph form"
- **Structured:** "Use sections with headers"
- **Tabular:** "Present data in tables"
- **Visual:** "Describe visualizations that would be valuable"

### Adjusting Tone
- **Formal:** "Use professional business language suitable for board presentation"
- **Conversational:** "Use clear, accessible language for team communication"
- **Technical:** "Use industry-standard terminology and technical precision"
- **Empathetic:** "Use considerate language focusing on people impact"

### Adding Constraints
- **Length:** "Limit to one page" or "Maximum 500 words"
- **Focus:** "Focus only on [specific topic]"
- **Audience:** "Tailor for [specific audience]"
- **Urgency:** "Prioritize items requiring immediate attention"

---

## Prompt Enhancement Checklist

Before submitting your prompt, verify:

- [ ] Role/context specified (who is producing this?)
- [ ] Purpose defined (why is this needed?)
- [ ] Audience identified (who will read it?)
- [ ] Structure outlined (what sections to include?)
- [ ] Format specified (markdown, tables, bullets?)
- [ ] Constraints provided (length, focus, priorities?)
- [ ] Output quality criteria mentioned (actionable, data-driven, etc.)
- [ ] Data/content attached or referenced

---

## Examples of Strong vs. Weak Prompts

### ❌ Weak Prompt
```
Tell me about this meeting.
```
**Problems:** Vague, no context, no structure, no purpose

### ✅ Strong Prompt
```
You are a project manager creating post-meeting action items. Review the meeting notes and produce:
1. Summary of decisions made (3-4 sentences)
2. Action items table (task, owner, deadline, priority)
3. Open questions requiring follow-up
Format in markdown for team distribution.
```
**Strengths:** Role defined, clear structure, specific outputs, format specified

---

### ❌ Weak Prompt
```
What are the problems here?
```
**Problems:** No role, no analysis depth, no actionability

### ✅ Strong Prompt
```
You are a risk management consultant. Analyze the content and identify:
1. Top 5 risks with likelihood and impact ratings
2. Root cause analysis for each risk
3. Mitigation strategies with timelines
4. Success metrics to track risk reduction
Present as risk assessment report for executive review.
```
**Strengths:** Expert role, structured analysis, actionable outputs, clear audience

---

## Quick Modification Guide

### To Make Output More Detailed
Add: "Provide comprehensive analysis with supporting data and examples"

### To Make Output More Concise
Add: "Limit to key points only, maximum [X] words/sentences"

### To Add Quantitative Focus
Add: "Include specific metrics, percentages, and dollar amounts where available"

### To Add Actionability
Add: "For each insight, provide specific recommended actions with timelines"

### To Improve Structure
Add: "Use numbered sections, tables for data, and bullet points for lists"

### To Adjust Tone
Add: "Use [formal/conversational/technical/empathetic] language appropriate for [audience]"

---

## Practice Exercises

Use these scenarios with the sample meeting notes:

1. **Product Manager:** Create product roadmap based on customer feedback and competitive analysis
2. **Operations Manager:** Develop operational efficiency plan addressing capacity constraints
3. **Marketing Director:** Create competitive positioning and messaging strategy
4. **Investor Relations:** Prepare investor update highlighting growth trajectory and risks
5. **Board Member:** Evaluate management effectiveness and provide governance recommendations

For each exercise:
1. Choose the most relevant template above
2. Customize for the specific role/scenario
3. Apply to the sample meeting notes
4. Compare results with different template variations

---

**Remember:** The best prompt is one that gets you the exact output you need. Start with these templates and refine based on results!
