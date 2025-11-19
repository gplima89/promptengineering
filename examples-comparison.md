# Visual Examples: Prompt Quality Impact

This document shows side-by-side comparisons of outputs from different prompt qualities, demonstrating the real impact of prompt engineering.

---

## Example 1: Meeting Summary Comparison

### ❌ Poor Prompt
```
Summarize the meeting.
```

### Expected Output (Poor)
```
The meeting covered several topics including product launch, resources, budget, customers, 
and team morale. Various issues were discussed and some action items were assigned. The 
meeting ended with plans for follow-up meetings.
```

**Problems:**
- Too vague and generic
- No specific insights
- No actionable information
- Doesn't prioritize important vs. trivial
- Could apply to almost any meeting

---

### ✅ Good Prompt
```
Analyze the meeting notes and provide:
1. Executive summary (3-4 sentences) highlighting critical issues
2. Top 3 priorities requiring immediate action
3. Key decisions made
4. Potential risks identified
```

### Expected Output (Good)
```
## Executive Summary
The Q4 product launch is 75% complete but faces a critical 2-week delay in mobile 
integration. The engineering team operates at 110% capacity with 3 members on medical 
leave, creating significant delivery risk. Customer churn at 12% is directly linked to 
missing mobile capabilities—the same feature competitors are using to gain 15% market share.

## Top 3 Immediate Priorities
1. **Staffing Plan** - Engineering at breaking point (110% capacity + 3 on leave)
2. **Timeline Revalidation** - Mobile integration delayed, beta testing at risk
3. **Competitive Response** - Market share loss to competitors with mobile apps

## Key Decisions Made
- Security audit scheduled for November 25th
- Beta testing starts December 1st (pending timeline review)
- Emergency staffing meeting set for November 17th
- Board presentation November 29th

## Potential Risks
- Q4 launch delay due to resource constraints
- Team burnout and attrition
- Customer churn acceleration
- Market share loss to competitors
- Budget overrun (currently +3%)
```

**Improvements:**
- Specific and actionable
- Prioritized information
- Clear structure
- Quantitative data included
- Identifies critical issues

---

## Example 2: Task List Comparison

### ❌ Poor Prompt
```
List the tasks.
```

### Expected Output (Poor)
```
- Mike to do something with mobile
- Jennifer to work on staffing
- Sarah to coordinate testing
- Tom to prepare strategy
- Lisa to work on dark mode
- David to review budget
- Everyone submit Q1 plans
```

**Problems:**
- No context or details
- No deadlines
- No priorities
- No dependencies
- Not actionable

---

### ✅ Good Prompt
```
Extract all action items and create a prioritized table with:
- Task description
- Owner
- Deadline
- Priority (Critical/High/Medium/Low)
- Dependencies
- Estimated effort

Sort by priority and deadline.
```

### Expected Output (Good)
```
| Priority | Task | Owner | Deadline | Dependencies | Effort |
|----------|------|-------|----------|--------------|--------|
| CRITICAL | Emergency staffing meeting | Jennifer & Mike | Nov 17 | None | 2h |
| CRITICAL | Reassess mobile integration timeline | Mike | Nov 18 | Engineering team input | 8h |
| CRITICAL | Develop interim staffing plan | Jennifer | Nov 20 | Capacity analysis | 16h |
| HIGH | Budget reallocation review | David | Nov 22 | Finance analysis | 12h |
| HIGH | Competitive response strategy | Tom | Nov 22 | Market research | 20h |
| MEDIUM | Beta testing logistics | Sarah | Dec 1 | QA team availability | 10h |
| MEDIUM | Dark mode design prioritization | Lisa | Nov 25 | Design backlog review | 6h |
| LOW | Q1 2025 planning inputs | All | Nov 30 | Dept reviews | 4h each |
```

**Improvements:**
- Complete information for each task
- Clear priorities and timeline
- Shows dependencies
- Helps with resource planning
- Enables tracking

---

## Example 3: Role-Specific Output Comparison

### Same Data, Different Perspectives

**Context:** Same meeting notes, different audience needs

---

### 👔 CEO Perspective

**Prompt Focus:** Strategic decisions, board messaging, cross-functional alignment

**Key Output Sections:**
```
## Strategic Situation
🔴 CRITICAL: Resource capacity crisis threatening Q4 launch
🟡 HIGH: Competitive market share erosion
🟢 GOOD: Customer satisfaction at 89%

## Decision Required
STAFFING INVESTMENT
- Option A: Hire 2 contractors ($75K, 2-week start)
- Option B: Scope reduction (defer 2-3 features)
- Option C: Timeline extension (delay launch 4 weeks)
Recommendation: Option A - prevents revenue loss > cost

## Board Messaging (Nov 29)
1. On track for Q4 with controlled risks
2. Proactive investment in capacity
3. Strong customer satisfaction foundation
4. Competitive response strategy in place
```

---

### 👥 HR Perspective

**Prompt Focus:** Team health, capacity, retention, wellbeing

**Key Output Sections:**
```
## Team Health ALERT
- Engagement: 7.2/10 (down 0.6 - concerning trend)
- Utilization: 110% (unsustainable)
- On leave: 3 engineers (impacting capacity)
- Burnout risk: HIGH

## Immediate HR Actions (Next 7 Days)
1. Emergency staffing meeting with Mike (Nov 17)
2. Develop contractor job descriptions
3. Reach out to at-risk team members
4. Plan stress-reduction initiatives

## Retention Risk Assessment
HIGH RISK: Engineering team members under extreme pressure
- Estimated replacement cost: $150K per engineer
- Knowledge loss impact: 3-6 month project delays
- Recommended: Recognition program + workload relief
```

---

### 💰 Sales Perspective

**Prompt Focus:** Revenue impact, competitive threats, customer retention

**Key Output Sections:**
```
## Competitive Threat Assessment
⚠️ URGENT: Competitor A gained 15% market share with mobile app
⚠️ WATCH: Competitor B announcing AI features Q1 2025
📉 IMPACT: 12% churn directly attributed to missing mobile

## Revenue at Risk
- Q4 projected churn cost: ~$240K ARR
- Delayed mobile app opportunity cost: ~$500K
- At-risk enterprise accounts: 8 accounts, $1.2M ARR
TOTAL RISK: $1.94M

## Sales Team Actions
1. Proactive outreach to 8 at-risk accounts (this week)
2. Prepare "mobile app beta access" retention offer
3. Develop competitive talking points
4. Update sales deck with timeline
```

---

### 🔧 Engineering Perspective

**Prompt Focus:** Technical delivery, capacity, quality, timeline

**Key Output Sections:**
```
## Technical Status
✅ Core features: 75% complete
⚠️ Mobile integration: BLOCKED (Android API compatibility)
⚠️ Timeline: +2 weeks delay
🔴 Testing: Compressed schedule = quality risk

## Capacity Reality Check
Current: 110% utilization
On leave: 3 engineers (25% capacity loss)
Sales request: 2 engineers for client work (conflicting priority)
Sustainable: Need to reduce to 85-90% utilization

## Engineering Recommendation
CANNOT COMMIT TO CURRENT TIMELINE without:
1. Additional 2-3 senior engineers (contractors)
2. Scope reduction (defer 2-3 features), OR
3. Timeline extension (4 weeks)

Technical debt risk: HIGH if we rush
Quality risk: HIGH with compressed testing
```

---

## Example 4: Data Visualization Descriptions

### ❌ Poor Prompt
```
What charts should we make?
```

### Expected Output (Poor)
```
You could make charts about the budget, timeline, and team.
```

---

### ✅ Good Prompt
```
Suggest specific data visualizations for this content. For each, describe:
1. Chart type
2. Data points to include
3. Key insight it would reveal
4. Intended audience
```

### Expected Output (Good)
```
## Visualization 1: Project Timeline Gantt Chart

**Chart Type:** Gantt chart with critical path highlighting

**Data Points:**
- All 7 action items with start/end dates
- Dependencies shown with arrows
- Resource allocation per task
- Current completion status
- Critical path highlighted in red

**Key Insights:**
- Identifies scheduling conflicts (multiple tasks hitting Mike)
- Shows which delays impact launch date
- Reveals resource bottlenecks
- Highlights critical path: mobile integration → beta → launch

**Audience:** Engineering, Product, Leadership

**Business Value:** Enables proactive schedule management, shows where to focus resources

---

## Visualization 2: Resource Capacity Heat Map

**Chart Type:** Heat map showing utilization over time

**Data Points:**
- Engineering: 110% (red)
- Sales: 100% (orange)
- Design: 85% (yellow)
- 3-month projection with/without interventions

**Key Insights:**
- Visualizes unsustainable engineering workload
- Shows cascading impact of medical leaves
- Demonstrates ROI of contractor hiring (reduction to 90%)
- Identifies when capacity normalizes

**Audience:** HR, Engineering Leadership, CEO

**Business Value:** Justifies staffing investment, prevents burnout

---

## Visualization 3: Customer Churn Root Cause

**Chart Type:** Sankey diagram or waterfall

**Data Points:**
- 12% total churn
- Breakdown: Mobile app absence (67%), Competitor features (20%), Other (13%)
- Revenue impact per category
- Timeline of churn over 6 months

**Key Insights:**
- Quantifies business case for mobile app (67% of churn)
- Shows churn accelerating (trend line)
- Connects churn to specific missing features
- ROI calculation: $240K annual churn cost vs. $150K mobile app development

**Audience:** Sales, Product, Leadership, Board

**Business Value:** Prioritizes product roadmap, justifies development investment
```

---

## Example 5: Actionability Comparison

### ❌ Poor Output (Descriptive Only)
```
The team discussed resource constraints. Engineering capacity is an issue. 
There are concerns about the timeline. Customer feedback was reviewed.
```

**Problems:**
- Just describes what happened
- No insights
- No actions
- No priorities
- Not useful for decision-making

---

### ✅ Good Output (Actionable)
```
## Critical Issue: Resource Capacity Crisis
**Problem:** Engineering at 110% utilization with 3 on medical leave
**Impact:** Q4 launch at risk, team burnout imminent
**Root Cause:** Headcount not scaled with product ambition

**Immediate Actions (This Week):**
1. Jennifer: Develop 3 staffing options by Nov 20
2. Mike: Provide realistic timeline estimate by Nov 18
3. David: Pre-approve $100K contractor budget

**Success Metrics:**
- Reduce utilization to 85-90% within 3 weeks
- Maintain launch timeline OR proactively reset expectations
- Zero additional team member attrition

**Decision Needed:** CEO must choose Option A, B, or C by Nov 21
```

**Improvements:**
- Clear problem statement
- Quantified impact
- Root cause identified
- Specific actions with owners and dates
- Measurable success criteria
- Clear decision point

---

## Key Takeaways

### Quality Indicators of Good Prompts:
1. ✅ Specific role and context
2. ✅ Clear structure and sections
3. ✅ Output format specified
4. ✅ Length/detail level defined
5. ✅ Audience identified
6. ✅ Purpose stated

### Quality Indicators of Good Outputs:
1. ✅ Specific and quantified
2. ✅ Prioritized information
3. ✅ Actionable recommendations
4. ✅ Clear ownership
5. ✅ Timeline defined
6. ✅ Success metrics included

### The Prompt Engineering Formula:

```
[ROLE/CONTEXT] + [SPECIFIC TASK] + [STRUCTURE] + [FORMAT] + [CONSTRAINTS] = HIGH-QUALITY OUTPUT
```

**Example:**
```
[You are a CFO] + [analyzing budget variances] + [provide: 1) summary, 2) risks, 3) recommendations] 
+ [use tables for data] + [focus on top 3 variances] = Executive-ready financial analysis
```

---

## Practice Challenge

Take the sample meeting notes and try to generate:

1. **Three different outputs from the same data:**
   - One for quick team sync (5 minutes)
   - One for detailed project review (30 minutes)
   - One for board presentation (executive level)

2. **Compare your prompts:**
   - What changed between them?
   - How did structure differ?
   - What level of detail did you request?

3. **Evaluate the results:**
   - Did you get what you needed?
   - What would you refine?
   - Which worked best for its purpose?

---

**Remember:** The goal isn't just to get "an answer" — it's to get the *right answer* for your *specific need* in the *right format* for your *intended audience*.

Good prompt engineering = Better results + Less time + More value!
