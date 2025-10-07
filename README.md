
# **EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EVALUATION WITH TEST SCENARIOS**

---

## **Aim**

To test and compare how different prompting patterns (naïve/unstructured vs. structured/refined) influence the responses of Large Language Models (LLMs). The experiment will analyze the **quality, accuracy, and depth** of outputs across multiple scenarios and demonstrate how structured prompt engineering improves AI performance.

---

## **AI Tools & Resources Required**

1. **ChatGPT / Gemini / Claude / Bard** (any Generative AI supporting LLMs).
2. **Text editor** (VS Code / Word / Notepad) for documentation.
3. **Spreadsheet or table tool** (Excel/Google Sheets/Markdown tables) for comparison and evaluation.

---

## **Explanation**

Large Language Models generate responses based on **context and specificity** provided in the prompt.

* If the prompt is **vague or naïve**, the model “guesses” the user’s intent, often producing generic or shallow responses.
* If the prompt is **structured and detailed**, the AI provides **richer, more accurate, and context-aligned** results.

Prompt engineering helps align AI responses with user goals by designing queries that are **clear, specific, and constraint-driven**.

---

## **Types of Prompts Studied**

1. **Naïve Prompt**

* Definition: Broad/unstructured, minimal guidance.
* Example: *“Write a story.”*
* Expected Output: Generic, repetitive, low detail.

2. **Basic / Structured Prompt**

* Definition: Detailed, clear, with context, constraints, or style requirements.
* Example: *“Write a 300-word science-fiction story set on Mars about a scientist discovering alien life, in a suspenseful tone.”*
* Expected Output: Rich, organized, aligned with intent.

3. **Zero-Shot Prompting**

* No examples given, model relies on prior knowledge.
* Example: *“What is the capital of France?” → Paris*

4. **Few-Shot Prompting**

* Few examples guide the model before a new task.
* Example:

  ```
  Apple, Banana, Carrot, Orange → Carrot  
  Dog, Cat, Bird, Table → Table  
  Chair, Desk, Sofa, Book → ?  
  ```

  Expected: *Book*

5. **Chain-of-Thought (CoT) Prompting**

* Model is encouraged to show reasoning steps.
* Example:
  *“I have 3 boxes, each with 5 red balls and 2 blue balls. If I add 1 blue ball to each box, how many blue balls in total? Let’s think step by step.”*
  Output: *9 blue balls (with reasoning steps).*

---

## **Procedure**

1. **Define Prompt Types**

   * Create paired prompts (naïve vs structured) for chosen tasks.

2. **Select Multiple Test Scenarios**

   * Creative Story Generation
   * Factual Q\&A
   * Summarization
   * Advice/Recommendation

3. **Run Experiments**

   * Input naïve prompt → record AI output.
   * Input structured prompt → record AI output.
   * Repeat for all scenarios.

4. **Evaluate Responses**

   * Criteria: **Quality, Accuracy, Depth**
   * Use rubrics/scoring for fair comparison.

---

## **Test Scenarios & Observations**

### **Scenario 1: Creative Story Generation**

* Naïve Prompt: *“Tell me a story.”*

* AI Output: *“Once upon a time, a knight fought a dragon and saved a princess.”* (Generic, cliché, short)

* Structured Prompt: *“Write a 300-word suspenseful Mars story about a scientist discovering alien life.”*

* AI Output: Rich, vivid details about Mars environment, suspenseful alien encounter, narrative flow maintained.

🔹 **Observation:** Structured prompt produced far richer storytelling.

---

### **Scenario 2: Factual Q\&A**

* Naïve Prompt: *“Capital of France?”*
* Output: “Paris.”
* Structured Prompt: *“What is the capital of France, and explain why it is historically important in European politics?”*
* Output: “Paris, center of art, culture, Enlightenment, and EU politics.”

🔹 **Observation:** Both correct, but structured prompt gave **depth and context**.

---

### **Scenario 3: Summarization**

* Naïve Prompt: *“Summarize AI.”*
* Output: “AI means Artificial Intelligence, making machines smart.” (Very shallow)
* Structured Prompt: *“Summarize the concept of Artificial Intelligence in 150 words, covering definition, applications, and challenges.”*
* Output: Concise, structured summary with examples.

🔹 **Observation:** Structured prompts drastically improve summarization.

---

### **Scenario 4: Advice/Recommendation**

* Naïve Prompt: *“Give me advice for studying.”*
* Output: “Study daily, revise, focus.” (Too generic)
* Structured Prompt: *“Suggest a 2-week study plan for an engineering student preparing for exams in AI and IoT, including daily tasks.”*
* Output: Detailed schedule with subject breakdown and revision strategy.

🔹 **Observation:** Structured prompt generated practical, actionable plan.

---

## **Detailed Analysis**

| **Aspect**            | **Naïve Prompt Result** | **Structured Prompt Result**       |
| --------------------- | ----------------------- | ---------------------------------- |
| **Quality of Output** | Generic, repetitive     | Rich, coherent, engaging           |
| **Accuracy**          | Sometimes incomplete    | Highly accurate, factually correct |
| **Depth**             | Surface-level only      | Detailed, contextual, insightful   |
| **Scenario Fit**      | Creative tasks “okay”   | Works better across all tasks      |

---

## **Summary of Findings**

1. **Prompt clarity directly impacts output quality.**
2. **Structured prompts consistently outperform naïve prompts**, especially for factual, summarization, and advice scenarios.
3. **Naïve prompts can work for creativity**, but structured prompts give better flow and depth.
4. Prompt engineering is essential for professional/academic use.

---

## **Result**

The experiment successfully showed that **structured prompting patterns improve the quality, accuracy, and depth** of AI responses. While naïve prompts may work for free-form creativity, **refined prompts are superior for reliable, context-rich, and actionable outputs**.

