# 🧠 LLM-Powered PDF Knowledge Extraction: *Monopoly Edition*

Welcome to this experimental yet powerful project where we combine **Large Language Models (LLMs)** with **document understanding** to extract structured, insightful content from PDF files.  
In this notebook, we put the model to the test using the iconic *Monopoly Game Rulebook* as our document source.

---

## 🎯 Project Goal

To parse a complex, semi-structured PDF document and extract useful, queryable knowledge chunks with the help of an LLM — paving the way for searchable knowledge bases, assistants, or document intelligence apps.

---

## 🛠️ What This Notebook Does

- ✅ Loads a PDF (*Monopoly Guidebook*)
- ✅ Extracts text from each page
- ✅ Cleans and processes the content
- ✅ Breaks down the document into semantically meaningful sections
- ✅ Queries the LLM to extract structured, human-friendly information

### ✨ Example Outputs

```text
• What are the rules of property trading?
• What happens when a player lands in Jail?
• How is rent calculated?

## 📚 Use Case
This prototype sets the foundation for:
• AI-powered board game assistants
• Searchable document bots for rules, instructions, and guides
• Automating FAQ generation from manuals
• Fine-tuning domain-specific knowledge extraction models

## 💡 Future Enhancements
• 🔁 Integrate LangChain or LlamaIndex for retrieval
• 💬 Add chat UI using Gradio or Streamlit
• 🔍 Enable vector-based similarity search for QA
• 🎲 Extend to other games or policy manuals