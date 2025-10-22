# 📖 [Index](#-index)
-   [Course 4](#-course-4-prompt-tuning--iteration)
    - [Worksheet](#-course-4-worksheet-prompt-tuning--iteration)
-   [Course 5](#-course-5-chain-of-thought--step-by-step-reasoning)
    - [Worksheet](#-course-5-worksheet-chain-of-thought--step-by-step-reasoning)
-   [Course 6](#-course-6-worksheet-role-prompting--context-framing)
    - [Worksheet](#-course-6-worksheet-role-prompting--context-framing)
-   [Experienced Level Exercise](#-end-of-level-exercise-prompt-refinement-lab)

---


# 🧠 [Course 4: Prompt Tuning & Iteration](#-course-4-prompt-tuning--iteration)
*[Back to Top](#-index)*

## 🎯 Learning Objectives
By the end of this session, participants will be able to:

- Understand the concept of prompt tuning through iterative refinement.
- Identify when and why a prompt needs adjustment.
- Apply a structured approach to improving prompt performance.
- Use feedback loops to guide prompt evolution.


🗂️ Course Structure (Live Session)
1. Icebreaker: “AI Misinterpretation Theater” (5 min)

**Activity:** Show a vague or poorly tuned prompt and its hilariously off-target output.<br>
**Humor Injection:** “Prompt tuning: because sometimes your AI thinks ‘summarize this report’ means ‘write a Shakespearean sonnet about quarterly losses.’”

2. What Is Prompt Tuning? (10 min)

**Definition:** The process of refining a prompt through trial, error, and feedback to improve output quality.<br>
**Analogy:** “It’s like adjusting your GPS instructions—if you keep ending up in a lake, maybe reword ‘take a left’.”<br>
**Example:** Show how a vague prompt evolves into a precise one through 3–4 iterations.


3. Why Iteration Matters (10 min)

**Concepts:**

AI models interpret language probabilistically.<br>
Small changes in phrasing can lead to big changes in output.

**Humor:** “AI doesn’t read minds—it reads syntax. And sometimes it reads it like a tired intern on a Monday.”


4. The Iteration Framework (10 min)

| Step | Action |
|------|--------|
| 1. Draft | Write your initial prompt. |
| 2. Test | Run it and observe the output. |
| 3. Diagnose | Identify what’s missing or off. |
| 4. Refine | Adjust wording, add constraints, clarify intent. |
| 5. Repeat | Iterate until the output meets expectations. |

**Tip:** Keep a “Prompt Lab Notebook” to track changes and results.


5. Practice Activity (5 min)

**Activity:** Participants are given a vague prompt and asked to refine it in 3 iterations.<br>
**Example:** Start with “Write something about meetings” → end with “Write a humorous 3-paragraph blog post about common meeting mistakes in remote teams.”


6. Wrap-Up & Q&A (5 min)

## ✅ Knowledge Check (Multiple Choice)


What is prompt tuning?

A) Changing the AI’s personality<br>
B) Refining a prompt through iteration<br>
C) Adjusting the model’s temperature<br>
D) Writing prompts in rhyme<br>

Why is iteration important in prompt engineering?

A) It makes the AI faster<br>
B) It helps improve output quality<br>
C) It reduces server load<br>
D) It makes the AI more polite<br>

What’s the first step in the iteration framework?

A) Diagnose<br>
B) Refine<br>
C) Draft<br>
D) Repeat<br>

Which of the following is a sign your prompt needs tuning?

A) The output is perfect<br>
B) The output is vague or off-topic<br>
C) The AI asks for clarification<br>
D) The AI refuses to respond<br>

What’s a good practice when tuning prompts?

A) Use random emojis<br>
B) Keep a log of prompt versions and results<br>
C) Always use the same prompt<br>
D) Avoid constraints<br>


📝 Take-Home Worksheet (Markdown)

# 🧠 [Course 4 Worksheet: Prompt Tuning & Iteration](#-course-4-worksheet-prompt-tuning--iteration)
*[Back to Top](#-index)*

## ✍️ Key Concepts

- Prompt Tuning is the process of refining a prompt through trial and error.
- Small changes in wording can significantly affect AI output.
- Iteration helps align the prompt with the desired outcome.

## 🔁 Iteration Framework

1. **Draft** your initial prompt.
2. **Test** it with the AI.
3. **Diagnose** what’s missing or unclear.
4. **Refine** the prompt.
5. **Repeat** until satisfied.

## 🧪 Try It Yourself

Start with this vague prompt:  
**“Write something about meetings.”**

Iterate 3 times to improve it. Track your changes below:

| Version | Prompt | Notes |
|---------|--------|-------|
| 1 | | |
| 2 | | |
| 3 | | |

## 📚 Suggested Reading
- [OpenAI Cookbook: Prompt Iteration](https://github.com/openai/openai-cookbook)
- [Anthropic: Prompt Refinement Tips](https://www.anthropic.com/index/prompt-engineering)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

## 💬 Reflection
What did you learn from refining your prompt? How might this help in your work?

---
# 🧠 [Course 5: Chain-of-Thought & Step-by-Step Reasoning](#-course-5-chain-of-thought--step-by-step-reasoning)
*[Back to Top](#-index)*

## 🎯 Learning Objectives
By the end of this session, participants will be able to:

- Understand the concept of chain-of-thought prompting.
- Apply step-by-step reasoning to guide AI through complex tasks.
- Recognize when reasoning improves output quality.
- Write prompts that encourage logical progression and transparency.


## 🗂️ Course Structure (Live Session)
1. Icebreaker: “AI Logic Leap” (5 min)

**Activity:** Show an AI response that jumps to a conclusion without explanation.<br>
**Humor:** “AI logic sometimes skips steps like a kid doing math homework with invisible ink.”


2. What Is Chain-of-Thought Prompting? (10 min)

**Definition:** A technique that encourages the AI to reason through a problem step-by-step before giving an answer.<br>
**Analogy:** “It’s like asking the AI to show its work—because even robots need to pass math class.”<br>
**Example:** Compare “What’s 17% of 240?” vs. “Let’s solve this step-by-step: What’s 17% of 240?”


3. Why Reasoning Matters (10 min)

**Concepts:**

- Improves accuracy for multi-step problems.
- Reduces hallucinations and overconfident wrong answers.
- Makes outputs easier to audit and trust.


**Humor:** “Chain-of-thought prompting: because ‘just trust me bro’ isn’t a valid business strategy.”


4. Building Step-by-Step Prompts (10 min)

| Prompt Style | Example |
|--------------|---------|
| Direct | “Calculate the total cost of 3 items priced at $12, $15, and $20.” |
| Step-by-Step | “Let’s solve this step-by-step. First, add the prices. Then calculate the total.” |
| Explain Your Reasoning | “Explain how you arrived at the total cost.” |

**Tip:** Use phrases like “Let’s think step-by-step,” “First… then…,” or “Explain your reasoning.”


5. Practice Activity (5 min)

**Activity:** Participants rewrite a direct prompt into a chain-of-thought version.<br>
**Example:** “What are the pros and cons of remote work?” → “Let’s think step-by-step. First, list the pros. Then, list the cons. Finally, summarize the trade-offs.”


6. Wrap-Up & Q&A (5 min)

✅ Knowledge Check (Multiple Choice)


What is chain-of-thought prompting?

A) A way to make AI poetic<br>
B) A technique for step-by-step reasoning<br>
C) A method for shortening responses<br>
D) A way to confuse the AI<br>

Why is step-by-step reasoning useful?

A) It makes the AI faster<br>
B) It improves accuracy and transparency<br>
C) It reduces server load<br>
D) It adds humor<br>

Which phrase encourages chain-of-thought reasoning?

A) “Just answer quickly”<br>
B) “Let’s think step-by-step”<br>
C) “Make it sound fancy”<br>
D) “Use emojis”<br>

What’s a benefit of chain-of-thought prompting?

A) It hides the AI’s logic<br>
B) It makes responses shorter<br>
C) It helps audit and trust the output<br>
D) It removes constraints<br>

Which prompt best uses chain-of-thought?

A) “List 5 benefits of exercise.”<br>
B) “Explain the benefits of exercise step-by-step, starting with physical health.”<br>
C) “Write about exercise.”<br>
D) “Make exercise sound fun.”<br>


📝 Take-Home Worksheet (Markdown)

# 🧠 [Course 5 Worksheet: Chain-of-Thought & Step-by-Step Reasoning](#-course-5-worksheet-chain-of-thought--step-by-step-reasoning)
*[Back to Top](#-index)*

## ✍️ Key Concepts

- **Chain-of-Thought Prompting** encourages the AI to reason step-by-step.
- It improves accuracy, transparency, and auditability.
- Use phrases like “Let’s think step-by-step” or “Explain your reasoning.”

## 🧪 Try It Yourself

Rewrite the direct prompt below into a chain-of-thought version:

**Direct Prompt**:  
“What are the pros and cons of remote work?”

**Chain-of-Thought Version**:  
(Write your version here)

## 🔁 Practice Prompt

Create a step-by-step prompt for this task:  
“Calculate the total cost of a $12 item, a $15 item, and a $20 item.”

## 📚 Suggested Reading
- [OpenAI: Chain-of-Thought Prompting](https://platform.openai.com/docs/guides/gpt-best-practices)
- [Anthropic: Reasoning with AI](https://www.anthropic.com/index/prompt-engineering)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

## 💬 Reflection
How does chain-of-thought prompting change the way you think about AI responses?

---
# 🧠 [Course 6: Role Prompting & Context Framing](#-course-6-role-prompting--context-framing)
*[Back to Top](#-index)*

## 🎯 Learning Objectives
By the end of this session, participants will be able to:

- Use role prompting to shape tone, expertise, and perspective.
- Apply context framing to guide AI understanding and output.
- Combine roles and context to tailor responses for specific audiences.
- Recognize when and how to use personas effectively.


## 🗂️ Course Structure (Live Session)
1. Icebreaker: “AI in Costume” (5 min)

**Activity:** Ask the AI to respond as a pirate, therapist, and barista to the same question.<br>
**Humor:** “Role prompting: because sometimes you need your AI to wear a monocle and speak in Shakespearean verse.”


2. What Is Role Prompting? (10 min)

**Definition:** Assigning a persona or role to the AI to influence tone, style, and domain expertise.<br>
**Example:** “Act as a financial advisor and explain compound interest to a teenager.”<br>
**Analogy:** “It’s like casting your AI in a movie—give it a role, and it’ll play the part.”


3. What Is Context Framing? (10 min)

**Definition:** Providing background information or situational setup to guide the AI’s response.<br>
**Example:** “Given the following meeting notes, draft a summary for the executive team.”<br>
**Humor:** “Context framing is like giving your AI a map before asking it for directions.”


4. Combining Roles + Context (10 min)

| Technique | Example | 
| Role Only | “Act as a career coach and review my resume.” |
| Context Only | “Based on this data, write a summary.” |
| Role + Context | “Act as a data analyst. Based on this dataset, identify trends and write a summary for senior leadership.” |

**Tip:** Use roles to set tone and expertise, and context to guide task relevance.


5. Practice Activity (5 min)

**Activity:** Participants choose a task (e.g., writing a report, giving feedback) and write three versions:

- Role only
- Context only
- Role + Context


6. Wrap-Up & Q&A (5 min)

✅ Knowledge Check (Multiple Choice)


What does role prompting do?

A) Changes the AI’s programming<br>
B) Assigns a persona to influence tone and expertise<br>
C) Adds emojis to the response<br>
D) Makes the AI faster<br>

What is context framing?

A) Giving the AI a background or situational setup<br>
B) Changing the font of the prompt<br>
C) Asking the AI to be funny<br>
D) Removing constraints<br>

Which of the following is a role prompt?

A) “Summarize this report.”<br>
B) “Act as a project manager and summarize this report.”<br>
C) “Write a summary.”<br>
D) “Make this sound professional.”<br>

Why combine role and context?

A) To confuse the AI<br>
B) To improve tone and relevance<br>
C) To shorten the response<br>
D) To reduce server load<br>

Which prompt uses both role and context?

A) “Act as a chef.”<br>
B) “Based on this recipe, write a shopping list.”<br>
C) “Act as a chef. Based on this recipe, write a shopping list.”<br>
D) “Write a shopping list.”<br>


📝 Take-Home Worksheet (Markdown)

# 🧠 [Course 6 Worksheet: Role Prompting & Context Framing](#-course-6-worksheet-role-prompting--context-framing)
*[Back to Top](#-index)*

## ✍️ Key Concepts

- **Role Prompting** assigns a persona or expertise to the AI (e.g., "Act as a financial advisor").
- **Context Framing** provides background information to guide the AI’s response.
- These techniques help shape tone, depth, and relevance.

## 🎭 Role Prompting Examples

| Role | Prompt |
|------|--------|
| Teacher | "Act as a history teacher and explain the causes of WWI." |
| Career Coach | "Act as a career coach and review my resume." |
| Customer Support Agent | "Act as a support agent and respond to this complaint professionally." |

## 🧪 Try It Yourself

Write a role-based prompt for each scenario:

1. You need advice on improving your LinkedIn profile.
2. You want a humorous explanation of quantum physics.
3. You’re drafting a response to a customer complaint.

## 🧠 Context Framing Examples

| Context | Prompt |
|--------|--------|
| Background data | "Given the following sales data, write a summary for the executive team." |
| Prior conversation | "Based on our earlier discussion, suggest next steps for the project." |
| Audience info | "Explain blockchain to a group of high school students." |

## 🧪 Try It Yourself

Write a context-framed prompt for this task:<br>
"Create a report on employee engagement survey results."

## 📚 Suggested Reading
- [OpenAI: Role Prompting](https://platform.openai.com/docs/guides/gpt-best-practices)
- [Anthropic: Contextual Prompting](https://www.anthropic.com/index/prompt-engineering)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

## 💬 Reflection
How does assigning a role or providing context change the AI’s response?

---

# 🧩 [End-of-Level Exercise: “Prompt Refinement Lab”](#-end-of-level-exercise-prompt-refinement-lab)
*[Back to Top](#-index)*

## 🎯 Objective
Apply all concepts from the Experienced level (Courses 4–6) to iteratively design, refine, and optimize a multi-step prompt that solves a real-world problem using role prompting, context framing, and chain-of-thought reasoning.

## 🗂️ Exercise Structure
**Part 1:** Scenario Selection<br>
Participants choose one of the following real-world tasks (or bring their own):

- Draft a performance review summary for a team member.
- Generate a customer support response for a delayed shipment.
- Create a step-by-step plan for launching a new internal dashboard.
- Analyze survey results and summarize key insights.


**Part 2:** Prompt Drafting<br>
Write an initial prompt using:

- Clear intent
- A defined role
- Relevant context
- A request for step-by-step reasoning

*Example:*<br>
“Act as a business analyst. Given the following survey results, summarize the top 3 concerns raised by employees, and explain your reasoning step-by-step.”

**Part 3:** Iteration & Refinement<br>
Participants run their prompt through an AI tool and:

- Diagnose issues with the output (e.g., vague, missing steps, wrong tone).
- Refine the prompt using the iteration framework from Course 4.
- Track at least 2–3 versions and document changes.


**Part 4:** Final Submission
Submit:

- Final version of the prompt
- Summary of changes made during iteration
- Explanation of how role/context/reasoning improved the output


**Part 5:** Reflection
Answer the following:

- What was the most challenging part of refining your prompt?
- How did combining role, context, and reasoning affect the result?
- Where do you see yourself applying this skill in your work?

---


[Back to Overview](README.md)<br>
[Back to Main](/README.md)