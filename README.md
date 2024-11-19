
# GenAI

### **What is Generative AI?**  

Generative AI refers to AI systems that can create new data based on patterns learned from training samples. These models can generate a wide range of outputs, including images, text, audio, and videos.  

Key domains in Generative AI include:  
- **Generative Image Models**  
- **Generative Language Models**  

---

### **Why Are Generative Models Required?**  
Generative models are essential for several reasons:  
- **Understanding Complex Patterns** in data distributions.  
- **Content Generation** to automate creative tasks.  
- **Building Powerful Applications**, such as chatbots, virtual assistants, and design tools.  

---

### **Discriminative vs. Generative Models**  
**Discriminative Models** predict labels for given inputs (e.g., logistic regression, SVMs).  
**Generative Models** learn the underlying data distribution to create or simulate data.  
![Discriminative vs Generative Models](https://github.com/ParitKansal/photos/blob/main/Discriminative%20vs%20Generative%20Models.ppm)  

**Key Difference:**  
- Discriminative models focus on the boundary between classes.  
- Generative models learn the entire data distribution.  

---

### **What are LLMs?**  
**Large Language Models (LLMs)** are advanced deep learning models trained on extensive datasets to process, generate, and understand natural language.  

**Applications of LLMs:**  
- **Text-to-Text** generation (e.g., GPT).  
- **Text-to-Image** generation (e.g., DALL·E).  
- **Image-to-Text** generation (e.g., CLIP).  

---

### **End-to-End Generative AI Pipeline**  

The **Generative AI Pipeline** provides a systematic approach to build generative AI solutions, breaking the problem into manageable steps.  

- **Data Acquisition**  
  - **Sources:**  
    - Structured: CSV, XLSX  
    - Unstructured: Text, PDFs, DOCS  
    - Databases: SQL, NoSQL  
    - APIs, Web scraping, Internet datasets  
  - **No Data Scenario:**  
    - Generate synthetic data:  
      - Synonym replacement  
      - Data augmentation (e.g., flipping, noise addition)  
      - Backtranslation  
- **Data Preparation**  
  - **Cleanup:**  
    - Remove HTML tags, emojis, and correct spelling.  
  - **Basic Preprocessing:**  
    - Tokenization, stop word removal, stemming/lemmatization.  
    - Punctuation removal, case normalization, language detection.  
  - **Advanced Preprocessing:**  
    - POS tagging, dependency parsing, and coreference resolution.  
- **Feature Engineering**  
  - Text vectorization:  
    - TF-IDF, Bag of Words, Word2Vec/GloVe.  
    - Transformer-based embeddings (e.g., BERT, GPT).  
- **Modeling**  
  - Select models:  
    - Open-source (e.g., GPT, BERT).  
    - Proprietary (e.g., Gemini, Claude).  
- **Evaluation**  
  - Metrics: Accuracy, BLEU, ROUGE, Perplexity.  
  - Deployment-readiness testing.  
- **Deployment**  
  - Options: On-premise, cloud platforms, or APIs.  
- **Monitoring & Updates**  
  - Monitor model performance, adapt to new data, and mitigate drift.  
---  
#### **Complete word**
- **Corpus**: A collection of written or spoken texts.
- **Word**: A single word.
- **Vocabulary**: The set of unique words in a corpus.
- **Document**: A single entity of text, such as a paragraph, line, or file, within the corpus.

---

#### **Few milestone in large language model**
- **Gemini**: was developed by Google
- **GPT**: GPT stands for "Generative Pre-trained Transformer". The model was developed by OpenAl
- **XLM**: Cross-lingual Language Model Pretraining by Guillaume Lample, Alexis Conneau.
- **Llama**: It was created by Meta Al
- **Megatron**: Megatron is a large, powerful transformer developed by the Applied Deep Learnin Research team at NVIDIA
- **M2M-100**: multilingual encoder-decoder (seq-to-seq) model researchers at Facebook

![](https://github.com/ParitKansal/photos/blob/main/TypesOfTransformer.png)

---

**Other Open Source Models**
- Mistral
- Llama
- Gemini
- Falcon
- Claude
- MPT-30B
- Stablelm

**What can LLMs be used for?**
- Text Classification
- Text Generation
- Text Summarization
- Conversation Al like chatbot, Question Answering
- Speech recognition and Speech identification
- Spelling Corrector

---

**Transformers**

<a href="https://jalammar.github.io/illustrated-transformer/">
    <img src="https://github.com/ParitKansal/photos/blob/main/transformers.png" alt="Illustrated Transformer">
</a>

---

![](https://github.com/ParitKansal/photos/blob/main/Vector_Embeddings_1.png)
