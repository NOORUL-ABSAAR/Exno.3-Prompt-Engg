# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:   29/08/2025                                                                         
### REGISTER NUMBER : 212223210011
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  1. Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
2. Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
3. Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
4. Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"
5. Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"
6. Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
7. Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
Result: The various types of Prompts are executed successfully.


Perfect 👍 I’ll generate **Experiment 3: Scenario-Based Report Development Utilizing Diverse Prompting Techniques (Case Study 1)** in two clear **separate steps**:

1. **Straightforward Prompts with Tabular Format Prompting**
2. **Straightforward Prompts with Preceding Question Prompting**

This way, you can directly copy it into your GitHub repo (README or report file).
I’ll structure it cleanly with headings, tables, and consistent formatting.

---

# **Experiment 3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques**

### **Case Study 1: Straightforward Prompts**

---

## **Step 1: Tabular Format Prompting**

| **Scenario**                                     | **Prompt**                                                                                                                | **AI Response (Tabular Format)**                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Self-Driving Cars Safety at Intersections** | “How can self-driving cars prioritize safety when navigating crowded intersections? Present in a tabular format.”         | <table><tr><th>Factor</th><th>Safety Strategy</th><th>Outcome</th></tr><tr><td>Pedestrian Detection</td><td>AI-powered vision sensors detect crossing pedestrians</td><td>Reduced accident risk</td></tr><tr><td>Vehicle-to-Vehicle Communication</td><td>Exchange speed & location data</td><td>Prevent collisions</td></tr><tr><td>Traffic Signal Integration</td><td>Adaptive response to real-time signals</td><td>Smoother, safer navigation</td></tr></table> |
| **2. Food Menu Nutritional Chart**               | “Generate a menu nutritional chart with dish name, ingredients, calories, protein, fat, allergen info in tabular format.” | <table><tr><th>Dish Name</th><th>Ingredients</th><th>Calories</th><th>Protein (g)</th><th>Fat (g)</th><th>Allergen Info</th></tr><tr><td>Grilled Chicken Salad</td><td>Chicken, lettuce, tomato, olive oil</td><td>350</td><td>30</td><td>10</td><td>None</td></tr><tr><td>Veggie Pasta</td><td>Wheat pasta, spinach, cheese</td><td>420</td><td>15</td><td>12</td><td>Gluten, Dairy</td></tr></table>                                                              |
| **3. Personal Finance Mobile App**               | “Design a mobile app for personal finance management in tabular format.”                                                  | <table><tr><th>Feature</th><th>Description</th><th>User Benefit</th></tr><tr><td>Expense Tracker</td><td>Logs daily spending</td><td>Better budgeting</td></tr><tr><td>Bill Reminders</td><td>Alerts for upcoming bills</td><td>Prevents late fees</td></tr><tr><td>Investment Dashboard</td><td>Tracks stocks, crypto, mutual funds</td><td>Informed investing</td></tr></table>                                                                                   |
| **4. Telemedicine Scheduling Optimization**      | “How can telemedicine platforms optimize patient-doctor appointment scheduling to reduce wait times? Use tabular format.” | <table><tr><th>Method</th><th>Implementation</th><th>Impact</th></tr><tr><td>AI Scheduling</td><td>Auto-assigns based on doctor availability</td><td>Minimized idle time</td></tr><tr><td>Queue Prediction</td><td>Uses patient history to predict visit length</td><td>Balanced scheduling</td></tr><tr><td>Priority Slots</td><td>Emergency cases flagged</td><td>Faster critical care</td></tr></table>                                                          |
| **5. Smart Sensors for Water Leakage**           | “How can smart sensors detect and prevent water leakage in urban pipelines? Present in tabular format.”                   | <table><tr><th>Sensor Type</th><th>Function</th><th>Prevention Action</th></tr><tr><td>Pressure Sensors</td><td>Detect unusual drops</td><td>Trigger maintenance alerts</td></tr><tr><td>Acoustic Sensors</td><td>Identify leak sounds</td><td>Pinpoint location</td></tr><tr><td>IoT Connectivity</td><td>Send real-time data</td><td>Remote monitoring</td></tr></table>                                                                                          |

---

## **Step 2: Preceding Question Prompting**

| **Scenario**                                   | **Preceding Questions**                                                                                                                                                                                                          | **Final Prompt**                                                                                                                  | **AI Response**                                                                                                                                                                   |
| ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **6. AI Chatbot for Student Academic Support** | - What are common student queries?<br>- Which academic subjects need more help?<br>- Should the chatbot be text-only or voice-enabled?<br>- How should it escalate difficult questions?                                          | “Design an AI chatbot for student academic support considering FAQs, subject coverage, interaction mode, and escalation process.” | The chatbot supports FAQs (exam dates, schedules), subject help (math, programming, science), text + voice modes, and escalates complex queries to human tutors.                  |
| **7. Product Launch Strategy**                 | - Who are the target customers?<br>- Who are the main competitors?<br>- What is the budget allocation?<br>- Which marketing channels should be prioritized?                                                                      | “Create a product launch strategy considering customers, competitors, budget, and channels.”                                      | A digital-first strategy focusing on young professionals, highlighting competitive pricing, allocating 40% budget to social media ads, and using influencers for rapid awareness. |
| **8. Climate Change Awareness Campaign**       | - Who is the target audience?<br>- Which cultural factors affect messaging?<br>- What channels are effective (TV, social media, community events)?<br>- Should the campaign use local language?                                  | “Develop a climate change awareness campaign tailored to audience, culture, and communication channels.”                          | Campaign uses social media & school programs for youth, local cultural references, multilingual posters, and storytelling videos.                                                 |
| **9. AI-Powered Personalized News Aggregator** | - Who is the user base (students, professionals, general public)?<br>- What sources should be prioritized?<br>- How should personalization work (keywords, categories, AI-curated)?<br>- Should fake news detection be included? | “Design an AI-powered personalized news aggregator considering audience, sources, personalization, and misinformation filtering.” | App curates news by interest tags, offers fact-check alerts, prioritizes credible publishers, and has adjustable user profiles.                                                   |
| **10. Smart Wearable for Fitness Tracking**    | - What health metrics should be tracked?<br>- Should the device sync with smartphones?<br>- How should data privacy be handled?<br>- What unique features differentiate it?                                                      | “Design a smart wearable for fitness tracking considering metrics, connectivity, privacy, and unique features.”                   | Device tracks HR, steps, SpO2, syncs with phones, uses encrypted storage, and adds AI-based posture correction alerts.                                                            |

---




# Result: Thus the Prompts were exected succcessfully .

