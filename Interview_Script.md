# Interview Script

Thank you for participating in this interview study. We are researching how individual AI Agent developers understand, practise, and face challenges related to privacy and security during the development process. Today’s conversation will be divided into four parts: your understanding of privacy and security, your practices in actual development, the challenges you face, and your expectations and suggestions regarding platforms and regulations. We will record the entire interview, and the recording will only be used for research analysis and will not be made public. If needed, a transcript of the recording can be provided to you. During the interview, you are welcome to ask questions or share any thoughts at any time. If you have no questions, I will begin recording now.

*[start recording]*

## Part 1. General understanding/definition

1. How do you define AI Agent?
  - What are its components? How does it operate?

2. In the design and operation of your AI Agent, what privacy or security issues might be involved? （Please provide specific examples.）

3. How do you define user privacy?
  - What constitutes user privacy? To what extent should user data be utilized to ensure privacy protection?
  - Which categories of user data are you particularly concerned about?

4. Mental Model (guide the interviewee to draw diagrams or write explanations)
  - What user data does your AI agent collect?
  - When your AI agent interacts with users or their environment (e.g., perceiving data, acquiring information), how do you understand where the data flows first and what happens to it within your agent system or the platform you use (e.g., local storage, cloud, passed to an LLM, transformed)?
  - In your understanding, when an AI agent receives input information or perceives the environment (such as text input, cameras, searches), how is this data processed?
  - If the agent performs certain actions (such as sending emails, fetching information, controlling devices), do you understand how this data interacts with external services? Where is this data stored when the AI agent interacts with users and the environment? How does the platform handle this data?
      - Do you think this data will be transmitted to APIs like OpenAI? Do you use APIs like OpenAI yourself?
      - Do you think you will use external knowledge bases or RAG functionality to assist the agent? What user information might be involved?
      - Do you think there will be calls to other third-party APIs (e.g., for drawing functions, email functions, etc.)? What user information might be involved?

5. Do you understand how underlying platforms(e.g., OpenAI, a cloud provider, an agent framework) might use the data generated from agent interactions?(Hint: model training, system improvements, analytics, etc.)

6. What is your understanding of an Agent's "memory" or "knowledge base"? How is this information stored, accessed, and who can access it? (For example, fine-tuning data, persistent conversation history, custom instructions)

7. How did you establish these understandings? Where do they come from? Are they from documents, news, training, others' experiences, or your own speculation?

## Part 2. Development practices and tools

1. When developing AI agents, what stages are typically involved?

2. At which stages are privacy and security issues considered?

3. What specific tools are used for consideration and mitigation?

4. Have any legal and regulatory requirements been considered?

5. From the user's perspective, what risks might they perceive?

6. How would you communicate privacy issues to users, inform them of potential privacy risks, and what considerations would you take into account?

## Part 3. Probe/security scenarios

1. If your AI agent performs actions (e.g., sending an email, controlling a smart device, making a purchase), how do you envision the data flowing between your agent and those external services?

2. Data Leakage and Misuse Risks
    - Do you think your agent might engage in excessive data collection? For instance, many agents may request extensive data permissions to provide personalized services.
    - What kind of user profiles do you think your agent might create, and could these pose privacy risks to users? Many agents might build detailed user profiles and infer private information that users have not explicitly disclosed.
    - Do you think your agent might experience data leaks or share data with third parties?

3. System Security and Malicious Attacks
    - Do you think your agent might be vulnerable to prompt injection attacks? For example, some agents could be manipulated through carefully crafted malicious inputs to induce or hijack their behavior.
    - Do you think your agent might face data poisoning issues? For instance, attackers could contaminate the training data of the AI agent.
    - Do you think your agent might be susceptible to privacy theft attacks? For example, attackers might extract memorized sensitive information from the AI's training data.
    - Do you think your agent might encounter issues of misuse or unauthorized access?

## Part 4. Expectation

###From platform's perspective 

1. What specific tools, features, or guidelines do you wish AI agent development platforms (such as OpenAI or other frameworks) would provide to help you build safer and more privacy-focused agents? (e.g., built-in security scanning, privacy dashboards, standardized consent authorization processes)
  
2. Do you think current platforms offer sufficient support for individual developers in understanding and implementing privacy and security best practices for agents? What are the shortcomings?  

3. How can platforms better clarify the division of responsibilities between themselves and individual AI agent developers regarding privacy and security?  

4. What role do you believe platforms should play in supporting individual developers or their agents? How can this role be made most effective?

###From law's perspective
  
1. What role do you believe legal factors can play, what are the current shortcomings, and what kind of support is needed?

###From tool's perspective
 
1. What specific tools do you believe are needed, what roles can these tools play, and what kind of support do you need them to provide to you?

###From others' perspective
  
1. What other types of support do you believe you still need?

*[End of interview, thank you for participation, recording ends here…]*
