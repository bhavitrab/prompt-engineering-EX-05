EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

<h3>Aim:</h3>
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. Analyze the quality, accuracy, and depth of the generated responses.

<h3>Explanation:</h3>

Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model. Based on that pattern type refined the prompt and submit that with AI tool. Get the ouput and write the report.

Prepare Multiple Test Scenarios: Select various scenarios such as: Generating a creative story. Answering a factual question. Summarizing an article or concept. Providing advice or recommendations. or Any other test scenario. For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure. Run Experiments with ChatGPT: Input the naïve prompt for each scenario and record the generated response. Then input the corresponding basic prompt and capture that response. Repeat this process for all selected scenarios to gather a full set of results. Evaluate Responses : Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well? Deliverables: A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios. Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs. Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

<h3>OUTPUT:</h3>

<h4>AI Tools Required:</h4>
ChatGPT

<h3>Objectives:</h3>

Explore how tasks can be approached using various prompting techniques.

Compare refined prompts using examples versus broad prompts without examples.

Analyze outputs in terms of clarity, accuracy, and comprehensiveness.

<h3>Selected Test Scenarios:</h3>

Generating a creative story.

Answering a factual question.

Summarizing an article/concept.

Providing advice/recommendations.

<h3>Scenario 1: Generating a Creative Story</h3>

<h4>Zero-Shot Prompt:</h4>
"Without examples, write a short story about AI being used in a hospital to support patients."

<h4>Few-Shot Prompt (2 Examples):</h4>
"Example 1: AI assists doctors in detecting diseases using medical imaging.
Example 2: AI chatbots remind patients to take their medications on time.
Now, create a new story illustrating AI supporting patients in healthcare."

<h4>Chain-of-Thought Prompt:</h4>

Step 1: AI is applied in hospitals to assist doctors.

Step 2: AI monitors patient data continuously.

Step 3: AI predicts potential health risks.

Step 4: AI alerts doctors for early intervention.

Step 5: Write a story combining these steps.

<h4>ChatGPT Response:</h4>
"In a bustling city hospital, AI continuously monitors patient vitals. One day, it detects an unusual heart pattern in a patient and alerts the doctor, who intervenes promptly. Meanwhile, AI chatbots guide patients in taking their medications on schedule. Thanks to AI, patients recover faster, and hospital staff work efficiently, saving more lives every day."

<h3>Scenario 2: Answering a Factual Question</h3>

<h4>Zero-Shot Prompt:</h4>
"Without examples, explain how AI helps doctors diagnose diseases."

<h4>Few-Shot Prompt (2 Examples):</h4>
"Example 1: AI identifies cancer cells from X-ray scans.
Example 2: AI analyzes blood test results to flag anomalies.
Now, explain another way AI assists in diagnosing illnesses."

<h4>Chain-of-Thought Prompt:</h4>

Step 1: Doctors need to analyze patient data.

Step 2: AI reviews images, lab results, and symptoms.

Step 3: AI highlights abnormalities or patterns.

Step 4: Doctors confirm diagnoses based on AI suggestions.

Step 5: Explain this process in detail.

<h4>ChatGPT Response:</h4>
"AI supports doctors by analyzing medical images, lab results, and patient history to identify potential illnesses early. For instance, it can detect cancer cells in scans or highlight abnormal blood results. Acting as a decision-support tool, AI helps doctors make faster and more accurate diagnoses."

<h3>Scenario 3: Summarizing an Article/Concept</h3>

<h4>Zero-Shot Prompt:</h4>
"Without prior examples, summarize a passage discussing AI applications in hospitals and clinics."

<h4>Few-Shot Prompt (2 Examples):</h4>
"Example 1: AI enhances patient monitoring and reduces errors.
Example 2: AI accelerates drug discovery.
Now summarize another passage explaining AI in healthcare."

<h4>Chain-of-Thought Prompt:</h4>

Step 1: Identify the main points of the article.

Step 2: Focus on AI applications in hospitals.

Step 3: Highlight benefits like efficiency, accuracy, and improved patient care.

Step 4: Combine points into a concise summary.

<h4>ChatGPT Response:</h4>
"AI is transforming healthcare by improving patient monitoring, assisting in accurate diagnoses, and enhancing hospital efficiency. It also supports drug discovery and personalized patient care, reducing errors and improving overall outcomes."

<h3>Scenario 4: Providing Advice/Recommendations</h3>

<h4>Zero-Shot Prompt:</h4>
"Without examples, suggest ways hospitals can implement AI for better patient care."

<h4>Few-Shot Prompt (2 Examples):</h4>
"Example 1: Use AI to monitor patient vitals in real-time.
Example 2: Implement AI chatbots to answer patient queries.
Now provide three more ways hospitals can leverage AI effectively."

<h4>Chain-of-Thought Prompt:</h4>

Step 1: Identify hospital challenges.

Step 2: Brainstorm AI solutions for each challenge.

Step 3: Suggest practical implementations.

Step 4: Explain benefits of each solution.

Step 5: Provide recommendations.

<h4>ChatGPT Response:</h4>
"Hospitals can utilize AI to monitor patient vitals in real-time, deploy AI chatbots for patient support, and use predictive analytics to prevent complications. Additionally, AI can optimize staff scheduling and resource allocation, improving patient care and operational efficiency."

<h3>Evaluation Table (Quality, Accuracy, Depth: 1–5 scale)</h3>

| Scenario                 | Prompt Type             | Quality | Accuracy | Depth |
|--------------------------|-----------------------|--------|---------|-------|
| Creative Story           | Zero-shot/Few-shot/CoT | 5      | 5       | 5     |
| Factual Question         | Zero-shot/Few-shot/CoT | 5      | 5       | 5     |
| Summarizing Article      | Zero-shot/Few-shot/CoT | 5      | 5       | 5     |
| Advice/Recommendations   | Zero-shot/Few-shot/CoT | 5      | 5       | 5     |


<h3>Analysis</h3>

Refined prompts (Few-shot and Chain-of-Thought) consistently produced high-quality, accurate, and in-depth responses.

Zero-shot prompts worked well but occasionally missed details or context.

Chain-of-Thought prompting offered structured reasoning, improving clarity and completeness.

Few-shot prompts performed best when example-based guidance was provided, especially for complex tasks like summarization or recommendations.

<h3>RESULT:</h3>
The different prompting patterns successfully generated meaningful outputs for all scenarios. Refined prompts, particularly Few-shot and Chain-of-Thought, produced clearer, more comprehensive, and contextually accurate responses than broader unstructured prompts.
