# Get the Most Out of AI with the Prompt Framework (T-C-R-E-I)

*Personal study notes for understanding + memorization*
Notes By: Abhishek (EzAbyss)

---

## 🌱 The Big Idea: Inputs → Outputs

Using Generative AI is a simple loop:

* **Output** = what you want from the tool
* **Input** = the prompt that helps you get that output

Better inputs → better outputs.

---

## 🧠 The Prompting Framework

A reliable framework for great prompts:

### **T C R E I**

**Task · Context · References · Evaluate · Iterate**

### Memory phrase

> **Thoughtfully Create Really Excellent Inputs**

📌 Tip: Say it out loud or write it on a sticky note. You’ll use it throughout the course.

---

## 1️⃣ Task — Specify what you want the AI to do

The **task** is the foundation of every prompt.

Examples of tasks:

* Write a list
* Draft a speech
* Create an image

### ✅ Make the task specific

If you are vague, you usually get vague results.

### Add two boosters to avoid misunderstandings

#### 🎭 Persona

A **persona** tells the tool *what expert mindset to use*.

Examples:

* “You are a science expert…”
* “Act as an industry analyst…”
* “Write this for my manager/team…”

Why it helps: persona filters irrelevant info and improves accuracy + tone.

#### 📐 Format

A **format** tells the tool *how to present the output*.

Examples:

* Bullet list
* Table
* Outline
* Short sentences

---

### ✅ Example: Task + Persona + Format

**Prompt:**
You’re a movie critic that specializes in Italian film. Create a table that contains the greatest Italian films of the 1970s, and separate them into genres like thrillers, dramas, and comedies. Provide a 100-word summary of each movie as well as details about the production including director and release year.

---

## 2️⃣ Context — Add the details that make the output useful

**Context** = background information that helps the AI understand your situation.

Context can include:

* Your goal
* Why you need it
* What you tried before
* Constraints (budget, tone, audience, deadline)

### Example: weak vs strong

❌ “How was DNA discovered?”
✅ Add context: who you are, what you’re making, and the tone you need.

**Prompt:**
You’re a science expert developing a new curriculum at a local college. Tell me in a couple of engaging paragraphs how DNA was discovered and what kind of impact it had on the world. Write it in a way that people unfamiliar with science would understand. You have gotten feedback from students that they found this course dry and unintelligible before, so you want to make sure that the explanation grabs the students' attention and makes a good first impression.

### Pro tip

Context can become the **longest** part of your prompt.

---

## 3️⃣ References — Guide the AI with examples/materials

**References** are examples or resources that steer the model toward your preferred output.

Depending on the tool, references can be:

* Text
* Images
* Audio

### ✅ Key rule: Don’t just paste — **label + structure**

#### Best practices to structure references

**A) Transitional phrases**
Use phrases like:

* “Refer to these materials…”
* “Use the following examples…”

**B) Headings**
Label each reference clearly so the model knows what it is.

**C) XML-style tags (for complex prompts)**

```xml
<example01>
Your first example text here
</example01>
```

**D) Markdown formatting**
Use Markdown symbols to preserve formatting when pasting into AI tools:

* `_italic_`
* `**bold**`

### How many references?

✅ **2 to 5 references** is usually enough.
Too few → not enough guidance
Too many → creativity may shrink

---

## 4️⃣ Evaluate — Check the output before using it

Different AI models are trained differently, and even the **same prompt** can give different results across runs.

Before using AI output, evaluate:

* **Accuracy** (fact-check)
* **Bias** (watch for unfair assumptions)
* **Relevance** (does it match your goal?)
* **Consistency** (does it contradict itself?)

---

## 5️⃣ Iterate — Improve the prompt until it’s right

If the output isn’t what you need, refine the prompt.

### ABI rule

> **Always Be Iterating (ABI)**

Ways to iterate:

* Clarify the task
* Add missing context
* Change the persona
* Request a different format
* Add/adjust references

---

## 🧩 Copy-Paste Prompt Template (T-C-R-E-I)

Use this as a reusable base:

```md
**Task:**
Act as [persona]. Help me [do the task].

**Format:**
Return the result as [bullets/table/outline].

**Context:**
[Goal + audience + constraints + what I tried + any important details]

**References:**
Use the following examples/materials:
1) [Reference 1]
2) [Reference 2]

**Evaluate:**
Before finalizing, check for accuracy, clarity, and relevance.
If anything is missing, tell me what info you need.

**Iterate:**
Offer 2 improved versions of the prompt to get a better result.
```

---

## 🔑 One-Line Recall

**Task** (what) + **Context** (details) + **References** (examples) → **Evaluate** (check) → **Iterate** (improve)

---
