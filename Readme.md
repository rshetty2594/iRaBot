# iRaBot
#### Social Butterfly - Engage a Community


Conversational AI systems are becoming an indispensable part of the human ecosystem. Well-known examples of conversational AI include Apple’s Siri, Amazon’s Alexa and Microsoft’s Cortana. The conversational chatbots have come a long way from their rule-based predecessors and almost every tech company today employs one or more chatty assistant.

A Conversation chatbot understands the context of the conversation and can handle any user goal gracefully and help accomplish it as best as possible. This doesn’t always mean that the bot will be able to answer all questions but it can handle the conversation well.

In this project, we are aiming at building a chatbot - iRaBot, to answer user queries about the AI Skunkworks projects. To achieve this, we are using an opensource chatbot tool, namely - Dialogflow (previously known as Api.ai) by Google.

## How to run the bot?!

If you would like to get a realtime experience of the bot, please join the channel at https://join.slack.com/t/irabot/shared_invite/enQtNjEyNzU4NTY2OTUxLTU4NTAxM2U1MjhmNjU1ZDYzMTE3MDlmZjE1ODM0ZTAxZjQzMjg1MDU1OGE4NWRjNTRjMzYxNmMxMGZkM2IyYjQ
You can interact with the bot named iRaBot placed on the sidebar.

Or, you can watch this quick video - 
https://drive.google.com/drive/folders/12mQKcSO6menY23ke_5Xcmgj3BwOeEswa?usp=sharing

## Why Dialogflow?

We compared a few opensource tools to build a chatbot before finalizing on Dialogflow.
Here are the metrics based on which we decided this model.

1) Alexa 
*Advantages :*
    Alexa is pretty straight forward to program and develop AI assistant applications with. 
    Applications can run on any platform. You have full control because you have to manage all of the interactions in code (context, session, required parameters, etc.)
*Disadvantages :*
    Every triggered intent requires a webhook call. 
    No development UI - you have to input your intent schema, utterances, slots and manage all of the relationships manually. 
    Relatively weak in terms of machine learning. Harder to develop with in comparison to **Dialogflow**

2) Dialogflow
*Advantages :*
    Smarter and can learn alternative phrases which can trigger intents and understand alternative entities.
    Allows you to manage context parameters through the UI. 
    Easily add entities by highlighting them in the sample utterances through the UI. 
    Allows you to mark entities/parameters as required so the platform manages retrieving the entity/parameter values from the user without having to go to your business logic. 
    
*Disadvantages :*
    Lack of diagnostic tools to measure the true positives, true negatives, false positives and false negatives related to intent and entity matching. 
    Wit.ai has a nice “Stories” feature which allows you to visually represent the conversation flows, business logic invocations, context variables, and branching logic.
    
3) Wit.ai
*Advantages :*
    Easier to develop applications using the developer UI. 
    Smarter and can learn alternative phrases which can trigger intents and alternative entities. Allows you to manage context parameters through the UI. 
    Easily add entities by highlighting them in the sample utterances through the UI.
*Disadvantages :*
    Does NOT have the required slot/parameter feature so you have to invoke business logic after every interaction which gathers slot/parameter information from the user to gather any missing information which was not spoken by the user. 
    Limited predefined reusable domains of global skills. 
    
When compared with the above three tools, Dialogflow gives the best of everything, as it is easier to implement, supports easy integration, the "stories" feature can be implemented by using RASA, and we need not invoke business logic each time.

## What is submitted in this file?
**Dialogflow zip file** to the Agent - iRaBot
**Readme.md file**
**Video** showing the working of the bot
**Portfolio** with detailed explanations 
Some **screenshots** for reference 

## References 
https://medium.com/@abraham.kang/understanding-the-differences-between-alexa-api-ai-wit-ai-and-luis-cortana-2404ece0977c
https://towardsdatascience.com/building-a-conversational-chatbot-for-slack-using-rasa-and-python-part-1-bca5cc75d32f
https://dialogflow.com/docs/getting-started












