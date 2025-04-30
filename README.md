# Exno.4-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222230152
### Aim:
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 2 with Comparative Analysis Prompt, Comparative Analysis Prompt and Prompt Size Limitations

### Explanation - Any one use case from Unit 5 and generate the report for that with the unit 2 Prompt type
Procedure:
1.	Define the Scenario and Use Case:
Scenario:
The manufacturing industry is looking to reduce manual monitoring and increase efficiency through automation. The system will utilize IoT devices and embedded controllers to automate equipment, monitor performance, and enable predictive maintenance. The goal is to streamline the production process, minimize downtime, and enhance energy efficiency.
Target Audience:
Manufacturing companies, specifically in sectors like automotive, electronics, and food processing, where automation can significantly improve productivity.


Main Objectives:

•	Improve production efficiency by 30%.
•	Minimize machinery downtime with predictive maintenance.
•	Enable real-time monitoring and remote control of manufacturing systems.
•	Reduce energy consumption by optimizing processes.
 
2.	Identify Prompt Patterns for Each Design Aspect:
Idea Generation Prompts:

•	Prompt: “What features can be incorporated into the automation system to optimize production and reduce downtime?” Generated Ideas:
•	Sensors for real-time monitoring of equipment performance.
•	Predictive maintenance alerts to anticipate equipment failures.
•	Energy usage optimization by automating the switching of machines on/off based on demand.
•	Cloud-based dashboards for remote monitoring and control of machinery.

Persona and Context Prompts:

•	Prompt: “What should the user interface and control system convey to the operators and managers?” Generated Context:
•	The user interface should be intuitive and provide real-time data on machine performance, energy usage, and alerts.
•	The system should convey reliability and ease of use, with minimal training required for operators.

## 1. Direct Instruction Prompts:
Objective: Guide the chatbot to respond concisely to customer inquiries.

Prompt Pattern:
“When a customer asks for the status of their order, reply with: ‘Your order is currently being processed and will be delivered by [date].’”

Chatbot Example Response:

Chatbot: “Your order is currently being processed and will be delivered by [date].”

## 2. Contextual Prompting:
Objective: Incorporate specific context based on the user's previous interaction to provide more tailored responses.

Prompt Pattern:
“If the customer previously mentioned that they haven’t received their order, say, ‘I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.’”

Chatbot Example Response:

Chatbot: “I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.”

## 3. Persona-Based Prompting:
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.

Prompt Pattern:
“Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as ‘Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!’”

Chatbot Example Response:

Chatbot: “Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!”

## 4. Few-Shot Prompting:
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.

Prompt Pattern:
“Here are some examples of how to handle technical questions:
‘My phone isn’t charging.’ → ‘Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.’
‘The screen is flickering.’ → ‘It sounds like a display issue. Have you tried restarting the device?’
Now, respond to: ‘My app keeps crashing.’”

Chatbot Example Response:

Chatbot: “It sounds like an app issue. Have you tried restarting the app or updating to the latest version?”

## 5. Chain of Thought Prompting:
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.

Prompt Pattern:
*“When a customer reports their laptop overheating, guide them through the following steps:

Ask if they are using the laptop on a soft surface.

Suggest moving the laptop to a flat, hard surface for better airflow.

Ask if they’ve cleaned the vents recently.

Recommend restarting the device to see if the issue persists. Now, solve: ‘My laptop fan is making a loud noise.’”*

Chatbot Example Response:

Chatbot: “Let’s start by checking a few things:

Are you using the laptop on a soft surface like a bed or couch? If so, try using it on a hard, flat surface.

Have you cleaned the vents recently? Dust can accumulate and cause the fan to work harder.

Try restarting the laptop to see if the noise persists. If it does, the fan may need cleaning or replacement.”

## 6. Instruction with Constraints:
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).

Prompt Pattern:
“Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, ‘Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.’”

Chatbot Example Response:

Chatbot: “Your order is on the way and should arrive by [date]. Let me know if you need anything else!”

## 7. Reflective Prompting:
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.

Prompt Pattern:
“When a customer asks for help, first reflect their question back to them. For example, if they ask ‘How can I reset my password?’ respond with ‘You're asking how to reset your password, correct? Here’s how you can do it.’”

Chatbot Example Response:

Chatbot: “You're asking how to reset your password, correct? Here’s how you can do it: Go to the login page, click 'Forgot password', and follow the instructions sent to your email.”



# Result: 
Thus the Prompts were exected succcessfully.

