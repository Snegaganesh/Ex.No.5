
# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different prompting patterns respond to various prompts, such as broad or unstructured prompts versus clear and refined prompts, across multiple test scenarios, and to analyze the generated responses based on quality, accuracy, and depth.

### AI Tools Required: 
ChatGPT

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.
# 1.INTRODUCTION

Prompt engineering is the process of designing effective instructions for an Artificial Intelligence model to obtain accurate, relevant, and useful responses.
A simple or broad prompt may produce a general answer, whereas a clear and structured prompt can guide the AI to generate a more specific and organized response.
<img width="1376" height="768" alt="image" src="https://github.com/user-attachments/assets/0c1691f5-fa34-4a45-8918-2c0f26735f0f" />

# 2.TYPES OF PROMPT
## 2.1 Naïve Prompt
A naïve prompt is a simple, broad, or unstructured instruction given to an AI model. It provides minimum information about the expected output.

Example
~~~
Explain Artificial Intelligence.
~~~

The AI has to decide the content, depth, structure, and target audience by itself.
## 2.2 Basic / Refined Prompt
A basic prompt is a clearer and more structured instruction that provides context, task requirements, audience, output format, and constraints.

Example
~~~
Explain Artificial Intelligence to a beginner.
Include its definition, major applications, advantages,
limitations, and two real-world examples.
Use simple language and clear headings.
~~~
This gives the AI better guidance and generally produces a more focused response.
# 3. Comparative Prompting Test Scenarios
The following scenarios are used to compare naïve and basic prompts.
## Scenario 1 – Creative Story Generation
## Naïve Prompt
~~~
Write a story about a robot.
~~~
## Basic Prompt
~~~
Write a 200-word creative story about a friendly robot
that helps students in a school. Include a beginning,
a problem, a solution, and a positive ending. Use simple
and engaging language.
~~~
# Comparison
| Parameter  | Naïve Prompt | Basic Prompt   |
| ---------- | ------------ | -------------- |
| Quality    | Moderate     | High           |
| Accuracy   | Good         | High           |
| Depth      | Limited      | Detailed       |
| Creativity | General      | Focused        |
| Structure  | Basic        | Well organized |
## Observation: 
The basic prompt generates a more structured and meaningful story because it specifies the length, characters, problem, solution, and ending.
## Scenario 2 – Factual Question
## Naïve Prompt
~~~
What is cloud computing?
~~~
## Basic Prompt
~~~
Explain cloud computing for a beginner who has no
technical knowledge. Give a simple definition, explain
how it works, provide three examples, and list two
advantages and two limitations.
~~~
# Comparison
| Parameter    | Naïve Prompt | Basic Prompt |
| ------------ | ------------ | ------------ |
| Quality      | Good         | Very High    |
| Accuracy     | Good         | High         |
| Depth        | Basic        | Detailed     |
| Clarity      | Moderate     | Excellent    |
| Organization | Simple       | Structured   |
## Observation: 
Both prompts can produce a correct answer, but the basic prompt provides a more complete and beginner-friendly explanation.
## Scenario 3 – Summarization
## Naïve Prompt
~~~
Summarize Artificial Intelligence.
~~~
## Basic Prompt
~~~
Summarize Artificial Intelligence in approximately
100 words. Include its definition, applications,
benefits, and one limitation. Use simple language and
include only the most important points.
~~~
# Comparison
| Parameter   | Naïve Prompt | Basic Prompt |
| ----------- | ------------ | ------------ |
| Quality     | Moderate     | High         |
| Accuracy    | Good         | High         |
| Depth       | Variable     | Appropriate  |
| Relevance   | Moderate     | High         |
| Conciseness | Moderate     | Excellent    |
## Observation:
The refined prompt produces a focused summary because the required points and approximate length are clearly specified.
## Scenario 4 – Advice and Recommendation
## Naïve Prompt
~~~
How can I learn Java?
~~~
## Basic Prompt
~~~
Create a 30-day Java learning plan for a college student
with basic programming knowledge. Divide the plan into
weekly stages covering Java syntax, OOP, arrays, collections,
exception handling, and problem-solving. Include daily
practice activities and a small final project.
~~~
# Comparison
| Parameter    | Naïve Prompt | Basic Prompt |
| ------------ | ------------ | ------------ |
| Quality      | Moderate     | High         |
| Practicality | General      | Very High    |
| Depth        | Limited      | Detailed     |
| Organization | Low          | Excellent    |
| Usefulness   | Moderate     | High         |
## Observation:
The basic prompt provides an actionable learning plan instead of only giving general suggestions.
## Scenario 5 – Technical Explanation
## Naïve Prompt
~~~
Explain Internet of Things.
~~~
## Basic Prompt
~~~
Explain the Internet of Things (IoT) to an ECE student.
Start with a simple definition. Explain sensors,
connectivity, processing, and actuators. Describe the
working process step by step and provide two real-world
examples. Use simple technical language.
~~~
# Comparison
| Parameter           | Naïve Prompt | Basic Prompt |
| ------------------- | ------------ | ------------ |
| Quality             | Good         | Very High    |
| Accuracy            | Good         | High         |
| Depth               | Moderate     | Detailed     |
| Technical Relevance | General      | High         |
| Organization        | Moderate     | Excellent    |
## Observation: 
The basic prompt produces an answer that is more appropriate for the specified audience and technical context.
# 4. Prompt Templating Techniques
A prompt template is a predefined structure containing fixed instructions and dynamic information. It allows the same prompt structure to be reused for different inputs.
<img width="1400" height="764" alt="image" src="https://github.com/user-attachments/assets/238a97ef-49c9-48c4-86f2-0452a0bde1be" />
## 4.1 Static Templates
A static template contains fixed instructions with little or no customization.
Example
~~~
Generate a maintenance report.
~~~
## 4.2 Parameterized Templates
Parameterized templates contain placeholders that can be replaced with dynamic information.
Example
~~~
Equipment: {equipment_name}
Equipment ID: {equipment_id}
Fault: {fault_description}
Date: {detection_date}
~~~
## 4.3 Conditional Templates
Conditional templates change their instructions based on a particular condition.
Example
~~~
If severity is High:
Generate a detailed report with safety warnings.

If severity is Low:
Generate a brief maintenance summary.
~~~
## 4.4 Chained Templates
Chained templates divide a complex task into multiple smaller tasks.
Example
~~~
Main Report
      ↓
Root Cause Analysis
      ↓
Downtime Estimation
      ↓
Maintenance Recommendation
      ↓
Final Report
~~~
# 5. Command Pattern
The Command Pattern is a software design pattern that converts a request into an object. This allows the sender of a request to be separated from the component that performs the request.
In the proposed AI system:
Client → Configures the report
Invoker → Maintenance management system
Command → Report generation request
Receiver → AI/LLM model
<img width="666" height="564" alt="image" src="https://github.com/user-attachments/assets/a6512587-3c2e-4126-8946-0c81f0353b18" />
# 6. Components of Command Pattern
| Component         | Description                           |
| ----------------- | ------------------------------------- |
| Command Interface | Defines the `execute()` operation     |
| Concrete Command  | Implements report-generation logic    |
| Invoker           | Sends the report-generation request   |
| Receiver          | AI/LLM that generates the response    |
| Client            | Configures templates and machine data |
# 7. Integration of Prompt Templates with Command Pattern
Prompt templates and the Command Pattern can be combined to create a modular AI-based maintenance reporting system.
<img width="1432" height="692" alt="image" src="https://github.com/user-attachments/assets/d422bff1-6f81-4149-9dc5-8c388089afa4" />
# 8. Workflow
The system works according to the following steps:
The maintenance manager requests a report.

The system receives equipment information.

An appropriate prompt template is selected.

Machine data is inserted into the template.

A command object is created.

The command sends the prompt to the AI model.

The AI model analyzes the information.

A structured maintenance report is generated.

The report is stored or displayed on a dashboard.
# 9. Example Implementation in Python
## Command Interface
~~~
class Command:
    def execute(self):
        raise NotImplementedError
~~~
## Concrete Command
~~~
class GenerateMaintenanceReport(Command):

    def __init__(self, template, data, llm):
        self.template = template
        self.data = data
        self.llm = llm

    def execute(self):
        filled_prompt = self.template.format(**self.data)
        return self.llm.generate(filled_prompt)
~~~
## Receiver – Simulated AI Model
~~~
class LLMModel:

    def generate(self, prompt):
        return f"""
[Generated Report]

{prompt}

Root Cause: Bearing wear.
Action: Replace spindle bearing and inspect
the lubrication system.
"""
~~~
# 10. Example Usage
~~~
template = """
Generate a maintenance report for {equipment_name}
(ID: {equipment_id}).

Fault: {fault_description}
Date: {detection_date}
"""

data = {
    "equipment_name": "CNC Lathe",
    "equipment_id": "MCH-102",
    "fault_description": "Spindle overheating",
    "detection_date": "2025-09-04"
}

llm = LLMModel()

command = GenerateMaintenanceReport(
    template,
    data,
    llm
)

report = command.execute()

print(report)
~~~
# 11. Sample Output
~~~
[Generated Report]

Generate a maintenance report for CNC Lathe
(ID: MCH-102).

Fault: Spindle overheating.
Date: 2025-09-04.

Root Cause: Bearing wear.

Action:
Replace spindle bearing and inspect the
lubrication system.
~~~
<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/517d2aae-9bfb-405e-9074-f33c435fbfd0" />

# 12. Overall Comparison

| Test Scenario         | Naïve Prompt        | Basic Prompt            | Overall Result |
| --------------------- | ------------------- | ----------------------- | -------------- |
| Creative Story        | General             | Structured and creative | Basic better   |
| Factual Question      | Correct but general | Detailed and focused    | Basic better   |
| Summarization         | Broad               | Concise and relevant    | Basic better   |
| Advice                | General suggestions | Step-by-step guidance   | Basic better   |
| Technical Explanation | General             | Audience-specific       | Basic better   |
# 13. Analysis
The experiment shows that the clarity and structure of a prompt directly influence the quality of the generated response.

Naïve prompts are useful when the task is simple and the expected answer is straightforward. However, they may produce responses that are broad, less organized, or inconsistent.

Basic prompts provide additional information such as:

Context
Role or audience
Specific task
Expected output
Length
Constraints
Required information

Therefore, basic prompts generally produce responses with better quality, accuracy, relevance, organization, and depth.

However, a detailed prompt is not always necessary. For simple factual questions, a naïve prompt may provide an equally satisfactory result.
# 14. Future Enhancements
<img width="512" height="341" alt="image" src="https://github.com/user-attachments/assets/497b618d-04eb-489b-af33-52746d8e73c3" />
Future versions of the system can include:

Integration with IoT sensors.
Real-time machine monitoring.
Predictive maintenance using machine learning.
Multi-language report generation.
Automatic graphs and charts.
# 15. Conclusion
This experiment demonstrates the importance of effective prompting in obtaining high-quality AI-generated responses. The comparison between naïve and basic prompts shows that clear and refined prompts generally provide more relevant, accurate, structured, and detailed results.
The integration of Prompt Templating Techniques with the Command Pattern further provides a modular approach for developing AI-based applications such as automated maintenance report generation.
Thus, effective prompt design combined with software engineering principles can improve the consistency, efficiency, scalability, and usefulness of AI systems.
# RESULT: The prompt for the above said problem executed successfully
