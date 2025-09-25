This project shows how to build a TNT-LLM application using GPT-4o and LangGraph. It implements a two-phase system:

Taxonomy generation: the model generates and refines a structured taxonomy (clusters, categories) from a set of documents

Text classification: the taxonomy is used to label a larger corpus; then a lightweight classifier (e.g. logistic regression) is trained on those labels for scalable inference
