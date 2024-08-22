# Chunking-Strategy

Chunking optimizes how large documents or datasets are segmented into smaller, manageable pieces (chunks) for efficient retrieval and use in conjunction with LLMs.
Goals of Chunking in RAG Pipelines-
Optimize Retrieval: Chunks are the retrievable units; therefore, the strategy should optimize the ability to retrieve the most relevant chunks.
Maximize Contextual Coherence: Chunks should maintain enough contextual integrity to allow the model to generate coherent and accurate responses.
Handle Long Documents: Large documents are broken down into smaller parts that fit within token limits of LLMs during generation.
