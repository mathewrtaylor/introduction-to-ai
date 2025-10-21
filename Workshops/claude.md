# Claude AI Workshop: From Basics to Power User

**Duration:** 90-120 minutes | **Participants:** Up to 30 | **Skill Level:** Mixed (Beginner to Advanced)

---

## Part 1: Introduction (15-20 minutes)

### What is Claude?
- **Large Language Model (LLM)** created by Anthropic
- Built on transformer architecture trained on vast text data
- Predicts and generates human-like text based on patterns
- **Current version:** Claude Sonnet 4.5 (latest and smartest model)

### Core Capabilities Overview
1. **Natural Conversation** - Ask questions, brainstorm, discuss ideas
2. **Analysis & Research** - Analyze data, documents, images
3. **Content Creation** - Write, edit, summarize, translate
4. **Code & Technical Work** - Write, debug, explain code in many languages
5. **Visual Creation** - Build interactive web apps, diagrams, data visualizations
6. **Problem Solving** - Break down complex problems, strategic thinking

### What Makes Claude Unique?
- **Extended context window** - Can process 200,000+ tokens (≈150,000 words)
- **Artifact system** - Creates separate, editable documents and applications
- **Strong reasoning** - Thoughtful, nuanced responses with step-by-step logic
- **Safety-focused** - Designed to be helpful, harmless, and honest
- **File handling** - Works with PDFs, images, CSVs, spreadsheets, documents
- **Web search** - Can search the internet for current information
- **Visual analysis** - Understands and analyzes images, charts, diagrams

### Key Limitations to Know
- Knowledge cutoff: January 2025 (but can search for current info)
- Cannot access external websites directly (unless using search/fetch)
- Cannot remember between separate conversations (unless in same thread)
- No real-time data unless searching
- Cannot execute code or access your local files

---

## Part 2: Live Demonstrations (15-20 minutes)

### Demo 1: The Power of Context
**Prompt:** "I'm preparing a presentation on renewable energy for executive stakeholders. Help me create an outline that focuses on ROI and risk mitigation rather than environmental benefits."

**What this shows:** Understanding nuanced requests, adapting tone for audience

### Demo 2: Artifacts in Action
**Prompt:** "Create an interactive calculator that helps me compare the total cost of ownership between buying vs leasing a car over 5 years. Include insurance, maintenance, depreciation, and let me adjust the variables."

**What this shows:** Building functional tools on the fly

### Demo 3: Visual Analysis
**Upload a chart or diagram**
**Prompt:** "Analyze this image and explain the key insights. What story does this data tell?"

**What this shows:** Multimodal understanding

### Demo 4: Complex Problem Solving
**Prompt:** "I need to schedule 8 team members across 3 projects, each requiring different skill sets. Team members have varying availabilities. Help me think through an approach to optimize this."

**What this shows:** Structured thinking, breaking down complexity

### Demo 5: Document Processing
**Upload a PDF or document**
**Prompt:** "Summarize the key action items from this document and create a prioritized task list."

**What this shows:** Document analysis and synthesis

---

## Part 3: Workshop Game - "The Claude Challenge" (45-60 minutes)

### Game Format: Team-Based Prompt Competition

**Setup:**
- Divide into 5-6 teams of 5-6 people
- Each team needs at least one device with Claude access
- Teams rotate through challenge stations

### Scoring System:
- **Speed:** First team to complete (10 points)
- **Quality:** Best output judged by facilitator (15 points)
- **Creativity:** Most innovative approach (10 points)
- **Bonus:** Using artifacts or advanced features (5 points)

---

### CHALLENGE 1: The Translator (8 minutes)
**Scenario:** Your company is expanding to Japan. You need to translate your product tagline and explain cultural considerations.

**Task:** 
- Translate your tagline (facilitator provides one: e.g., "Innovation that moves you forward")
- Get Claude to explain cultural nuances and suggest adaptations
- Create 3 alternative versions optimized for Japanese market

**Success criteria:** Accurate translation + cultural insights + creative alternatives

---

### CHALLENGE 2: The Data Detective (10 minutes)
**Scenario:** You've received a CSV of customer feedback scores. Find the insights!

**Task:** 
- Upload a sample CSV (facilitator provides: customer_feedback.csv)
- Ask Claude to analyze patterns
- Create a visualization showing the key finding
- Identify one actionable recommendation

**Success criteria:** Artifact created + clear insight + business recommendation

**Facilitator prep:** Create a simple CSV with columns like: Date, Customer_ID, Product, Rating, Comment

---

### CHALLENGE 3: The Rapid Prototyper (12 minutes)
**Scenario:** Your boss wants to see a mockup of a new feature—in the next 15 minutes!

**Task:**
- Build an interactive prototype for: "A team mood tracker where employees can check in daily with emoji + optional note"
- Must be functional (people can actually click/interact)
- Must look professional

**Success criteria:** Working artifact + good UX + visual appeal

---

### CHALLENGE 4: The Problem Solver (10 minutes)
**Scenario:** Office chaos! Multiple problems need solving simultaneously.

**Task:** 
Present Claude with this multi-problem scenario and get actionable solutions:
- "We have: A team member out sick (owns critical path items), a client meeting moved up 2 days, budget cuts requiring 15% reduction, and a key vendor delayed shipment. Help me triage and create a 48-hour action plan."

**Success criteria:** Prioritized plan + specific actions + risk mitigation

---

### CHALLENGE 5: The Creative Brief (10 minutes)
**Scenario:** Marketing needs fresh campaign ideas for a fictional product.

**Task:**
- Facilitator provides a quirky product (e.g., "Solar-powered umbrella with built-in phone charger")
- Get Claude to generate:
  - 3 campaign concepts with taglines
  - Target audience analysis
  - One social media post (with hashtags)
  - Potential objections + how to address them

**Success criteria:** Creative concepts + strategic thinking + ready-to-use content

---

### CHALLENGE 6: The Code Rescue (8 minutes)
**Scenario:** A junior developer wrote code that's broken. Fix it and explain what went wrong!

**Task:**
- Facilitator provides broken code snippet (Python or JavaScript)
- Ask Claude to:
  - Identify the bugs
  - Fix the code
  - Explain what was wrong in simple terms
  - Suggest how to prevent this error

**Success criteria:** Working code + clear explanation + learning moment

**Facilitator prep example:**
```python
def calculate_average(numbers):
    total = 0
    for num in numbers:
        total += num
    return total / len(numbers)

scores = []
print(calculate_average(scores))  # This will crash!
```

---

## Part 4: Tips & Best Practices (10-15 minutes)

### Prompt Engineering Quick Wins

**1. Be Specific**
- ❌ "Write about dogs"
- ✅ "Write a 500-word blog post about golden retrievers as family pets, focusing on temperament and care requirements, in a friendly tone for first-time dog owners"

**2. Provide Context**
- ❌ "Make this better"
- ✅ "I'm revising this email to a client who's upset about delays. Make it more empathetic while maintaining professionalism and clearly stating next steps"

**3. Use Examples**
- "Format the output like this: [provide example]"
- "Here's the style I'm going for: [paste sample]"

**4. Iterate and Refine**
- Claude can update artifacts—just ask!
- "Make it shorter / more formal / funnier"
- "Add a section about X"

**5. Ask for Step-by-Step**
- "Think through this step-by-step"
- "Break this down into phases"
- "What are the pros and cons?"

### Power User Tricks
- **Chain of thought:** Ask Claude to "think out loud" for complex problems
- **Role-play:** "You're a financial advisor. Help me understand..."
- **Multiple perspectives:** "Give me arguments both for and against..."
- **Template creation:** "Create a template I can reuse for..."
- **Learning mode:** "Explain this like I'm [beginner/expert]"

---

## Part 5: Open Practice & Q&A (15-20 minutes)

### Suggested Practice Prompts
Let participants choose their own adventure:

**For Writers:**
- "Help me write a compelling LinkedIn post about [topic]"
- "Analyze this paragraph and suggest improvements for clarity"

**For Analysts:**
- Upload a spreadsheet: "What trends do you see?"
- "Create a dashboard visualization for this data"

**For Managers:**
- "Help me structure a difficult conversation with an underperforming team member"
- "Create an agenda for a strategic planning meeting about [topic]"

**For Developers:**
- "Explain [technical concept] and show me example code"
- "Build a simple [tool] that does [function]"

**For Creatives:**
- "Generate 10 name ideas for [product] with explanations"
- "Create a visual mockup for [concept]"

---

## Facilitator Notes

### Pre-Workshop Prep
- [ ] Create sample CSV file for Challenge 2
- [ ] Prepare broken code snippet for Challenge 6
- [ ] Have product example ready for Challenge 5
- [ ] Test all demo prompts beforehand
- [ ] Prepare scoreboard (physical or digital)
- [ ] Have prizes ready (optional but fun!)

### Materials Needed
- Projector for demonstrations
- Devices with Claude access (ensure participants can access)
- Sample files (CSV, PDF, image)
- Printed challenge cards (optional)
- Scoreboard
- Timer

### Timing Flexibility
- Can compress to 60 minutes by reducing demo time and selecting 3-4 challenges
- Can extend to 2 hours by adding more open practice time
- Adjust challenge time limits based on team speed

### Judging Tips
- Focus on creativity and learning, not perfection
- Celebrate unique approaches
- Give bonus points for teams that help each other
- Keep energy high and moving quickly

### Common Participant Questions
- **"Can Claude access the internet?"** - Yes, it has web search capabilities
- **"Will it remember our conversation next time?"** - Only within the same conversation thread
- **"Can it see my screen?"** - No, only what you upload or type
- **"Is this secure for work data?"** - Cover your organization's AI usage policy

---

## Follow-Up Resources

**Share with participants:**
- Anthropic's prompting guide: https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview
- Support documentation: https://support.claude.com
- Encourage: Create a "Claude Tips" channel for ongoing learning

**Encourage experimentation:**
- Daily practice: One task per day for a week
- Share wins: Create a space for team members to share clever uses
- Build a prompt library: Collect and share successful prompts

---

## Success Metrics

**Immediate (end of workshop):**
- 90%+ participants try at least 3 different prompt types
- Every team completes at least 4 challenges
- Participants report increased confidence (quick survey)

**Long-term (2-4 weeks later):**
- Track Claude usage across team
- Collect examples of how Claude helped with real work
- Gather feedback on most valuable use cases

---

**Remember:** The goal isn't perfection—it's demystifying AI and building confidence through hands-on practice!

---


[Back to Workshops](README.md)<br>
[Back to Main](/README.md)