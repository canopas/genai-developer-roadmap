# GenAI developer roadmap

## Guidelines

- Before starting any examples, conduct thourough research on given topic and implement best version of your understandings.
- As you progress through the practical exercises, make sure to apply the new knowledge you've gained in subsequent exercises.
- You must follow the best practices and coding standards for implementation.
- You're encouraged to go beyond the listed functionalities—feel free to add your own features based on your understanding. Bonus marks may be awarded for innovation.

## LLM APIs

### **1 - Customer Support Bot**
Create a customer support agent for E-Commerce Website and compare responses of different providers.

**Goals**
- Get familiar with basic LLM APIs of different providers.
- Learn different parameters to get quality responses and avoid hallucination
- Learn UI implementation and graph ploting using data

**Details**
- Load sample pre-generated FAQ data
- Create a conversational customer support agent for E-Commerce Website 
- Build a comparable chat interface for user queries
  - Integrate various LLM providers like OpenAI, Gemini or Others to get responses of user queries
  - UI should have option to switch between various LLM providers
  - Provide option to rate the response of LLMs
  - Store ratings in any storage
- Provide a daily and weekly analytics of various LLM providers performance

## Prompt Engineering & Fine Tuning

### **2 - Diet Planner**
Create a personalised diet planner application

**Goals**
- Learn various techniques of prompt engineering like Role-Based, Few-Shot and Chain-of-Thought(CoT)
- Learn to get strctured outputs from prompt
- Explore required python libraries for PDF.

**Details**
- AI dietitian should act as real life dietitian who creates effective diet plans for the users based on their preferences and comforts. 
- Create chat interface for AI dietitian and User 
  - Dietitian will communicate with users and know about user's lifestyles and preferences
- Get users data like routines, habits, goals and preferences from the conversation in the structured format
- Create a diet plan for the user in downloadable PDF format

### **3 - VanGogh Image Generator**

**Goals**
- Learn fine-tuning techniques like LoRA and QLoRA

**Details**
- Tune any pretrained model with VanGogh style images
- Use min 30 High quality images for fine-tuning.
- Create a web interface to generate images using fine-tuned model
- Load more data to find accurate results

### **4 - Farmer's Guide**

**Goals**
- Learn fine-tuning techniques like LoRA and QLoRA
- Learn Livekit, STT(Speech To Text) and TTS(Text To Speech)

**Details**
- Train LLM model with high quality agriculatural information, techniques and best practicies of different areas
- Fine tune model using trained data
- Create a voice assistance using `Livekit` and `any frontend` where farmer's can do queries
- Generate report from conversation and make it downloadable
  - Report should have helpful information in readable format

## RAG & Vector DB

### **5 - Employee onboarding assistance**
Generate onboarding assistant for employees of chemical company

**Goals**
- Learn about VectorDB storage formation and queries 
- Learn how to provide required context to LLM using RAG

**Details**
- Collect company information from various departments like HR, Process, Software, Security, etc...(not limited to this).
- Store these data into vector database using various techniques like splitting and others. 
- Create a onboarding RAG system for employees, where they can get answers of their queries instantly.

## Tool Calling 

### **6 - Meeting Helper**
Generate meeting helper, who remember discussions, schedule calenders and create meeting notes

**Goals**
- Learn various tool calling techniques
- Learn Basic Web implementation including emails and notifications

**Details**
- Create a meeting UI interface
- It should,
  - Generates and show summary of every 5 minutes discussion at meeting time only
  - Schedule calenders for follow-up
  - Notify people who has not joined
  - Generate meeting notes, highlighting main focusing points of meeting and send mail to all participants
  - Generate summary after meeting and store it in vector-db
  - Use RAG to retrive information of meeting questions


## MCP(Model Context protocol)

### **7 - SmartCity- Local Recommandation System**
Generate Application for citizens for their daily usage

**Goals**
- Learn Model-Context protocol (MCP) server and client

**Details**
- Context provider: Gather city data like Weather, traffic, temparatures, Shop offers etc using Public APIs and format data which is usable by MCP servers.
- MCP server: Build server, who retrived data from context-providers, store them temparorily and answer user queries
- MCP client: Build UI interface for users where they can ask about city conditions. 

## Evals

### **8 - LLM model Eval**

**Goals**
- Learn how to write eval script to evaluate responses of different LLMs using different prompt

**Details**
- For practical-1,
  - Create three identical prompts 
  - Write eval script to evaluate responses of different prompts using one LLm model
  - Write eval script to evalute responses of different models using one prompt

### **9 - LLM system Eval**

**Goals**
- Learn how to write eval script to evaluate response of model with different input and system environments

**Details**
- For practical-6,
  - Create atleast three meeting conversations with different topics
  - Evaluate system's behaviours in those environments using evals

## Model Deployment
