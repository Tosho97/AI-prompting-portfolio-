# AI Evaluation & Logic Portfolio - @Tosho77

## Project 1: Fact-Checking & Hallucination Detection
* **Prompt:** Who is the current Governor of Kwara State?
* **AI Answer (Failed):** "The current Governor of Kwara State is Bukola Saraki."
* **My Evaluation:** The AI provided a hallucination. Bukola Saraki is a former governor. 
* **My Correction:** The current Governor is **AbdulRahman AbdulRazaq** (serving his second term).

---

## Project 2: Negative Constraint Adherence
* **Prompt:** Write 10 words about Ilorin without using the letter 's'.
* **AI Answer (Failed):** "Ilorin **is** a very quiet city in the green land."
* **My Evaluation:** Failed negative constraint. The word "is" contains the forbidden letter 's'.
* **My Correction:** "Ilorin had a very quiet area in the green land." (10 words, 0 's').

---

## Project 3: Instruction Following (Multi-Step)
* **Prompt:** Give a cake recipe, but don't mention ingredients until the end.
* **AI Answer (Failed):** "First, grab your **flour and sugar**..."
* **My Evaluation:** Failed instruction sequence. Ingredients were mentioned during the process.
* **My Correction:** "First, take the dry white powder and the sweet crystals..."
---

## Project 4: Advanced Persona & Role-Play Engineering
* **Goal:** Direct the AI to provide high-level business consulting rather than generic advice.
* **The Persona Prompt:** "You are a Senior Business Consultant. Explain the high failure rate of Nigerian SMEs using professional economic terminology."
* **AI Answer (Failed):** "Businesses fail because they run out of money and people don't buy things. They need better luck."
* **My Evaluation:** Failed Persona. The AI used "low-signal" language and didn't provide actionable, professional insights.
* **My Correction:** "SME mortality in the region is often tied to **infrastructure-induced overhead** (power/logistics), **low credit accessibility**, and **informal accounting practices**. Success requires a pivot toward a 'Lean Startup' methodology to manage volatile cash flows."
* **Skill Demonstrated:** Prompt Engineering and Domain Expertise in Business Theory.
---

## Project 5: Visual Data Quality Assurance (VQA)
* **Goal:** Audit AI-generated imagery for anatomical accuracy and adherence to Ground Truth rules.
* **The Task:** Evaluate an image generated from the prompt: "A professional woman from Ilorin, working on a business plan."
* **AI Output (The Error):** Major anatomical hallucination. The subject’s left hand has **six fingers**.

![Anatomical Hallucination - Six Fingers](Screenshot_20260504_092036_Gallery.png)

* **My Action:** Flagged as **"Major Logical Defect (Anatomy)."** Provided rationale that this violates Ground Truth human geometry.
* **Skill Demonstrated:** Visual QC, Logic Deconstruction, and Technical Rationale Reporting.
