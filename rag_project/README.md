# Pokémon TCG Rules RAG System

A local Retrieval-Augmented Generation (RAG) system built to query official competitive Pokémon Trading Card Game (TCG) rules, turn structures, card restrictions, and status conditions. 

The pipeline embeds custom markdown documentation into ChromaDB using `all-MiniLM-L6-v2` vectors, scores semantic relevance via cosine similarity, retrieves top-k grounded context chunks, and enforces strict boundary-aware refusals on out-of-domain and ungrounded near-miss questions.