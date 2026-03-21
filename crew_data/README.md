# crew_data

Place your source documents for the RAG pipeline in this folder.

Supported file types in the notebook:
- `.pdf`
- `.txt`
- `.md`

Examples:
- course notes
- company reports
- research papers
- project documentation

The notebook loads every supported file it finds here, chunks the content, creates embeddings, and builds a FAISS vector index for retrieval.
