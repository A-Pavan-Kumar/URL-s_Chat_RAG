# RAG Chat with User-Provided URLs

**RAG Chat** is a Retrieval-Augmented-Generation (RAG) chat system that retrieves information from user-provided URLs and uses a **Large Language Model (LLM)** to generate accurate, context-aware answers to user questions.

---

## **Features**

- **User-Provided URLs**: Accepts multiple URLs from the user within the chat prompt.
- **Content Extraction**: Retrieves content from the given URLs using an API request component.
- **Chunking**: Splits the retrieved content into smaller chunks for efficient processing.
- **Vector Database Integration**: Stores content chunks in **Astra**, a high-performance vector database.
- **Query-Based Search**:
  - Converts user questions into embeddings.
  - Uses similarity scoring to fetch the most relevant information.
- **LLM-Powered Responses**: Uses **Gemini 1.5 Pro LLM** to generate detailed answers based on retrieved content.
- **Dynamic Prompting**: Builds contextual prompts by integrating retrieved information with user queries.
