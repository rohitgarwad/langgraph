# 🤖 Agentic AI with LangGraph

A comprehensive collection of examples and tutorials for building Agentic AI applications using **LangGraph**. This repository progresses from basic graph concepts to advanced agent architectures with memory, tool calling, and human-in-the-loop (HITL) workflows.

## 📚 Course Content

The project is structured into progressive modules:

| Module | Description | Key Concepts |
|:-------|:------------|:-------------|
| **1. Simple Graph** | `1_simple_graph.ipynb` | Basic nodes, edges, and graph compilation |
| **2. Conditional Graph** | `2_graph_with_condition.ipynb` | Conditional edges, routing logic |
| **3. Chatbot** | `3_chatbot.ipynb` | State management, conversation history |
| **4. Tool Calling** | `4_tool_call.ipynb` | Binding tools to LLMs, executing actions |
| **5. Tool Call Agent** | `5_tool_call_agent.ipynb` | ReAct pattern, reasoning + acting loop |
| **6. Memory** | `6_memory.ipynb` | Persistent state, checkpointers |
| **7. LangSmith** | `7_langsmith_tracing.ipynb` | Debugging, tracing, observability |
| **8. Human-in-the-loop** | `8_HITL.py` | Breakpoints, user approval flows |

## 🛠️ Setup Instructions

1. **Environment Setup**:
   - Rename `sample.env` to `.env`.
   - Add your API keys (GROQ_API_KEY, TAVILY_API_KEY, etc.).

2. **Installation** (using uv):
   ```bash
   uv sync
   ```

3. **Running the Code**:
   - For notebooks: Open in VS Code or PyCharm.
   - For scripts: `uv run python 8_HITL.py`

## 🔑 Key Features Demonstrated

- **State Management**: Managing conversation context across graph turns.
- **Routing**: dynamically deciding the next step based on LLM output.
- **Persistence**: Saving and resuming graph state using checkpointers.
- **Observability**: Using LangSmith to inspect agent reasoning chains.
