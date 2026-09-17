
# AI Weather Assistant using LangGraph

## Introduction

AI Weather Assistant is a simple multi-step AI agent workflow built using LangGraph.

## Objective

- Build a multi-step AI agent workflow
- Understand LangGraph nodes, edges and state
- Demonstrate tool calling
- Provide a clear weather summary

## Technologies Used

- Python
- LangGraph
- Large Language Model (LLM)
- Weather API / Weather Tool

## Workflow

User Input
↓
Weather Tool
↓
Store Result in State
↓
Summarize Result
↓
Final Response

## LangGraph Components

### State
Stores information such as the user's city and weather result.

### Nodes
Perform tasks such as calling the weather tool and summarizing the result.

### Edges
Control the flow from one node to another.

### Weather Tool
Retrieves weather information for the requested city.

### LLM
Generates a natural-language response.

## Working

1. User enters a city name.
2. Agent sends the request to the weather tool.
3. Weather result is stored in state.
4. Result is passed to the summarization node.
5. LLM creates a weather summary.
6. Final response is shown to the user.

## Conclusion

This project demonstrates LangGraph concepts including state, nodes, edges and tool calling.
