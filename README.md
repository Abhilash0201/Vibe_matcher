Vibe Matcher is an AI-driven mini recommendation system that connects user “vibe” queries (like “energetic urban chic” or “relaxed beach style”) with semantically similar fashion products. The system leverages OpenAI’s text embeddings to represent product descriptions and user inputs as high-dimensional vectors, then computes cosine similarity to identify the top-matching items.

This prototype demonstrates the core of modern recommendation engines — contextual understanding through embeddings rather than keyword matching. Built using Python, Pandas, scikit-learn, and OpenAI API, the system can be extended with vector databases (like Pinecone or FAISS) for scalability.

Key Features:

Generates semantic embeddings using text-embedding-3-small

Computes cosine similarity to match user vibes with products

Displays top-3 ranked products with similarity scores

Logs query latency and basic evaluation metrics

Handles edge cases (e.g., low similarity → fallback message)

Use Case at Nexora:
AI-powered personalization like this enables Nexora to craft smarter shopping experiences — letting customers discover fashion items that feel right for their mood, lifestyle, or style identity.

Tech Stack:
Python · Pandas · OpenAI API · scikit-learn · Matplotlib
