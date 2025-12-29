# Task-A: Detect Cycle in Linked List (Floyd’s Tortoise & Hare)
### Problem

Detect whether a linked list contains a cycle and return the starting node of the cycle (if present).

# Approach

We use Floyd’s Tortoise & Hare algorithm:

Use two pointers — slow and fast

If they meet ➝ cycle exists

Reset slow to head and move both pointers until they meet again (cycle start)

# Task-B: Calling Gemini API (Generate Text)
### Goal

Send a prompt to Google Gemini model using REST API and display the response.

# Requirements

Install dependencies: pip install requests python-dotenv
## code here

# Task-C: Sentence Similarity using Sentence-Transformers
# Goal

Find the sentence that is most relevant to a user query using semantic similarity.

# Concept

SentenceTransformer → converts sentences into embeddings

cos_sim() → calculates cosine similarity between vectors

Higher similarity score → sentences are more related.
