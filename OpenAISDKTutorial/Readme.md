# OpenAI Library Tutorial

Step-by-step instructions for using the OpenAI Library.

## Prerequisite

Deploy the OpenAI Service on Azure.

## Configuration

Copy `appsettings.json.example` to `appsettings.json` and fill in the required settings.

## Simple Conversation

Understand the fundamentals of the `ChatCompletionAPI`. The LLM is stateless, so you always need to send a request with all contexts.

1. Start the project.
2. Enjoy the conversation with the LLM. Your input becomes the `User Prompt`. Modify the `System Prompt` as needed.
3. Debug the system and see the payload of the `Request` and `Response` in the [`ConversationExecutor`](OpenAISDKTutorial/ConversationExecutor.cs).
4. Update the System Prompt. For example: When I ask for help to write something, you will reply with a document that contains at least one joke or playful comment in every paragraph.
5. Read about [`Prompt Engineering`](https://platform.openai.com/docs/guides/prompt-engineering) and experiment with different patterns. 

## Objective 
- Understand the code base
- Play around with the options such as temperature and top p 
- Try and keep the conversation going and ask for past reference

