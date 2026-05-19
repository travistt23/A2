# 🧠 Developer Diary – Smart Finance Assistant

---

## Week 8 – Project Setup

<img width="1530" height="866" alt="image" src="https://github.com/user-attachments/assets/c156a80d-85f4-4e82-b8c6-94f922bfa540" />

**Goal:**  
Set up the development environment and install required libraries for the Smart Finance Assistant.

**AI Use:**  
Used AI to configure the Hands-on-AI environment, resolve installation issues, and ensure correct setup of dependencies.

**What I learned:**  
I learned how external AI APIs are integrated into a Python notebook and how environment configuration impacts the entire workflow.

**Reflection:**  
- **What worked:** Installation and setup went smoothly after following AI guidance.  
- **What didn’t:** Initial issues with missing packages and version mismatches caused errors.  
- **What I learned:** I learned the importance of environment setup and how small configuration mistakes can break the entire system.

---

## Week 9 – Data Processing

<img width="1535" height="842" alt="image" src="https://github.com/user-attachments/assets/3c6c42aa-8fb6-43ce-bdaf-b26602b05dcf" />

**Goal:**  
Develop a reliable data cleaning pipeline for financial transaction CSV files.

**AI Use:**  
AI assisted in designing data preprocessing logic including cleaning currency symbols, handling missing values, and grouping transactions.

**What I learned:**  
I learned that real financial data is messy and must be cleaned before meaningful analysis can be performed.

**Reflection:**  
- **What worked:** Successfully cleaned and structured transaction data using pandas.  
- **What didn’t:** Initially struggled with converting string currency values into numeric format.  
- **What I learned:** I learned how essential data cleaning is before any financial analysis can be done.

---

## Week 10 – AI Integration

<img width="1530" height="965" alt="image" src="https://github.com/user-attachments/assets/0d52a457-1f12-41a8-ae57-4c7748a44a11" />

**Goal:**  
Integrate chatbot functionality and implement a RAG system for financial insights.

**AI Use:**  
AI helped design chatbot behaviour, improve response quality, and structure retrieval-based answers using transaction data.

**What I learned:**  
I learned how AI can act as a contextual financial assistant using real data.

**Reflection:**  
- **What worked:** Chatbot and RAG system successfully returned meaningful responses.  
- **What didn’t:** Early versions gave generic responses without proper data grounding.  
- **What I learned:** I learned how important context is in AI systems to produce relevant and accurate answers.

---

## Week 11 – Tools & Automation

<img width="1535" height="797" alt="image" src="https://github.com/user-attachments/assets/9ef39e23-2d4c-4421-b271-f3130cde851f" />

**Goal:**  
Build a savings calculator tool for financial planning.

**AI Use:**  
AI helped design formulas for savings projection and convert them into a reusable function.

**What I learned:**  
I learned how simple calculations can be transformed into practical financial tools.

**Reflection:**  
- **What worked:** Savings calculator produced accurate time-to-goal results.  
- **What didn’t:** Initial version didn’t handle invalid inputs properly.  
- **What I learned:** I learned how financial planning tools can be automated using simple mathematical logic.

---

## Week 12 – Testing & Debugging

<img width="1535" height="868" alt="image" src="https://github.com/user-attachments/assets/68556db7-2ccc-499e-873a-0c5c97f4aa35" />

**Goal:**  
Develop a full testing suite to validate system functionality.

**AI Use:**  
AI generated test cases including edge cases, invalid inputs, and system validation checks.

**What I learned:**  
I learned the importance of testing to ensure reliability and robustness in data-driven applications.

**Reflection:**  
- **What worked:** Most core functions passed test cases successfully.  
- **What didn’t:** One or two edge cases initially failed due to missing validation logic.  
- **What I learned:** I learned how critical edge case testing is for building reliable real-world systems.
--------------------------------------------------------------------------------------------------
🧠 AI-Helped Development 
📌 Overview

Throughout the development of the Smart Finance Assistant, AI tools (including ChatGPT and hands-on-ai) were used as a collaborative development aid. AI supported ideation, coding, debugging, and testing across all stages of the project. All AI-generated outputs were critically reviewed, tested in Colab, and modified where necessary to ensure correctness and alignment with project requirements.

🤖 How AI Was Used
📊 Problem Design & Planning

AI assisted in refining the project scope by suggesting relevant personal finance use cases such as budgeting, spending awareness, and savings tracking. It also helped structure the six-step development methodology into a clear workflow.

🧹 Data Processing & Cleaning

AI was used to design and improve CSV handling logic, including:

removing currency symbols (e.g. $)
converting string values to numeric format
handling missing or inconsistent transaction data
grouping and aggregating spending by category

This improved the reliability of financial analysis outputs.

💬 Chatbot Development

AI helped design the financial assistant chatbot personality, ensuring responses were:

supportive and non-judgemental
easy to understand for users
focused on practical financial advice

It also assisted in structuring prompts for consistent conversational behaviour.

🔍 RAG System Integration

AI supported the design of a retrieval-augmented generation system by helping structure:

document ingestion logic
query handling flow
response generation based on transaction context and financial guidance

This enabled more context-aware financial Q&A functionality.

🛠️ Custom Tool Development

AI assisted in building a savings calculator tool by helping define the formula logic for:

time required to reach savings goals
impact of monthly contributions
structured output formatting for user readability
🧪 Testing & Debugging

AI generated a variety of test cases including:

normal spending patterns
edge cases (refunds, zero values, large transactions)
invalid or missing data scenarios

It also supported debugging during integration of multiple components (chatbot, RAG, UI, tools).

⚠️ Validation and Responsibility

All AI-generated suggestions were not used directly. Instead, they were:

tested in a live Colab environment
modified to fit project requirements
debugged when errors occurred
validated against expected outputs

This ensured correctness and maintained responsibility for all final implementations.

🧠 Reflection

Using AI significantly accelerated development and improved the structure of the system, particularly in data processing and RAG design. However, not all AI outputs were immediately correct, requiring iterative debugging and refinement.

This process highlighted the importance of:

understanding generated code rather than copying it directly
validating outputs through testing
combining AI assistance with critical thinking and problem-solving skills

Overall, AI acted as a development accelerator and learning support tool, rather than a replacement for technical decision-making.
