# OpenAI Library Tutorial

Step-by-step instructions for using the OpenAI Library.

## Prerequisite

Deploy the OpenAI Service on Azure.

## Configuration

Copy `appsettings.json.example` to `appsettings.json` and fill in the required settings.

## 2_History

The history feature was not implemented. The LLM doesn't remember the history, so you need to provide it with the history information.
Implement the history feature and observe its functionality.
Debug the ConversationExecutor to see how it behaves.
Interact with the chat and verify if it retains the history.

## Tips
1. Use `SessionManager.cs` in `ConversationExecutor.cs`
2. Bonus: Implement clear history functionality
