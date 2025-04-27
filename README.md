🧾 Knowledge LLM for Invoices - QA
----------------------------------
This project focuses on building a Question Answering system using Knowledge Graphs for invoice data. It combines structured schema design, language model fine-tuning, and Cypher query generation to enable natural language interaction with invoice documents.
💡 Key Components
---------------------------------
🔗 Knowledge Graph Creation

    Defines the invoice ontology (e.g., vendors, amounts, dates, items).

    Uses Neo4j to construct a graph database representing the structured invoice data.

🧠 Text-to-Cypher LLM
--------------------------------
    Fine-tunes the Qwen2-1.5B language model for translating natural language questions into Cypher queries.

    Evaluates model performance using BLEU and ROUGE scores.

💬 Question Answering
-------------------------------
    Allows users to ask natural questions like:

        “Which invoices are due this month?”

        “Show me vendors with the highest total amount.”

    Converts them to Cypher queries to extract data from the knowledge graph.
