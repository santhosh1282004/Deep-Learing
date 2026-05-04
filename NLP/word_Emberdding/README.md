# Word Embeddings in NLP

This folder contains implementations and concepts related to **Word Embeddings**, a fundamental technique in Natural Language Processing (NLP) used to convert text into numerical representations.

---

## What is Word Embedding?

Word Embedding is a technique that represents words as **dense vectors in a continuous vector space**, where words with similar meanings are placed closer together.

Unlike traditional methods like one-hot encoding, embeddings capture **semantic meaning and relationships between words**.

Example:
king → [0.25, 0.10, 0.78, ...]  
queen → [0.27, 0.12, 0.75, ...]

Words like *king* and *queen* will have similar vector representations.

---

## Why Do We Need Word Embeddings?

- Machines cannot understand raw text → need numerical representation  
- Captures **semantic similarity** between words  
- Reduces dimensionality compared to one-hot encoding  
- Improves performance in NLP tasks  

Word embeddings help models understand **context, meaning, and relationships** instead of treating words independently.

---

## Types of Word Embedding Techniques

### 🔹 1. Frequency-Based Methods

#### Bag of Words (BoW)
- Counts word occurrences  
- Simple but ignores context  

#### TF-IDF
- Weighs words based on importance  
- Useful for search and ranking  

 Limitations:
- No semantic meaning  
- Sparse vectors  

---

### 🔹 2. Prediction-Based Methods

These methods use neural networks to learn embeddings.

#### Word2Vec
- Predicts words based on context  
- Architectures:
  - CBOW (predict word from context)  
  - Skip-gram (predict context from word)  
- Captures semantic relationships  

#### GloVe (Global Vectors)
- Uses global word co-occurrence statistics  
- Combines statistical + neural approaches  

#### FastText
- Uses character n-grams  
- Handles rare and unknown words effectively  

---

### 🔹 3. Contextual Embeddings (Advanced)

#### ELMo
- Generates embeddings based on context  
- Same word → different meanings  

#### BERT
- Bidirectional context understanding  
- Produces highly accurate embeddings  
- Widely used in modern NLP systems  

Example:
"bank" in  
- river bank  
- money bank  
→ different vector meanings  

---

## How Word Embeddings Work

1. Convert text into tokens  
2. Define a context window  
3. Train a model to predict context or target word  
4. Learn vector representations  

Words appearing in similar contexts get **similar vectors**.

---

## Key Characteristics

- Dense vectors (low dimensional)  
- Capture semantic relationships  
- Enable similarity calculations  
- Improve generalization  

---

## Applications

- Sentiment Analysis  
- Text Classification  
- Machine Translation  
- Chatbots  
- Search Engines  
- Recommendation Systems  

---

## What This Folder Contains

- Implementation of word embedding techniques  
- Vectorization examples  
- Practical notebooks  
- Visualization of word relationships  

---

## Key Takeaways

- Word embeddings convert text into meaningful vectors  
- Similar words have similar representations  
- Prediction-based methods outperform traditional methods  
- Contextual embeddings are state-of-the-art  
