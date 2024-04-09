## Breast Cancer Posts and Comments Analysis

### Project Overview
This project delves into analyzing discussions, questions, and concerns about breast cancer on Reddit. By systematically examining these conversations, our goal is to unearth key themes, areas of public interest, common inquiries, and prevalent misconceptions. The insights gained aim to assist healthcare professionals in refining their communication and educational strategies, thereby enhancing patient care and shared decision-making processes in the context of breast cancer.

### Introduction
Leveraging social media platforms, especially Reddit, this study focuses on understanding public discourse surrounding breast cancer. The analysis sheds light on the emotional and practical challenges individuals face, guiding healthcare professionals to better address these needs.

### Data Description
Our dataset integrates two distinct sources: Reddit questions and their associated comments, utilizing IDs for cohesive merging. This integration resulted in 65,553 rows of data, encapsulating titles, questions, comments, scores, and controversiality metrics.

### Technologies and Methodologies Used
- Data Preprocessing: Text cleansing, tokenization, lemmatization, and stop words removal.
- Vectorization: TF-IDF and Word2Vec for text vectorization.
- Clustering Algorithms: K-Means clustering, evaluated using silhouette score.
- Keyword Extraction: KeyBERT, YAKE, and RAKE packages for identifying significant words.
- Topic Modeling: Latent Dirichlet Allocation (LDA) and BERT for uncovering prevailing themes.
- Emotion Analysis: Utilizing labeled Twitter data, DistilBERT for sentence embeddings, followed by K-Means clustering, SVM, and Naive Bayes models.
- Chatbot Development: Implemented using cosine similarity, TfidfVectorizer, and BERT Topic modeling, focused on assisting with queries related to breast cancer.

### Key Findings
- Data Modeling: TF-IDF vectorization outperformed Word2Vec, as indicated by a higher silhouette score (0.0033 vs. 0.09327), suggesting better clustering quality.
- Topic Modeling: Both LDA and BERTopic analyses identified key themes and topics within the discussions, providing insights into the concerns and interests of individuals discussing breast cancer on Reddit.
- Emotion Analysis: The integration of emotion analysis through pre-trained models and clustering revealed complex emotional nuances in the discussions, further guiding the refinement of communication strategies.
- Chatbot Implementation: Our Q & A chatbot, developed to facilitate better understanding of breast cancer-related queries, demonstrated the potential of AI in enhancing health communication.

### Challenges and Solutions
- Vectorization Selection: The decision to utilize TF-IDF over Word2Vec was made to enhance topic differentiation and computational efficiency, particularly important for social media text analysis.
- Emotion Analysis Data: Shifted to using labeled Twitter data for emotion analysis to more accurately capture the emotional depth within comments.
- Computational Constraints: Addressed computational time challenges by optimizing comment quality and leveraging high-capacity processors.

### Ethics and Privacy
Acknowledging the sensitivity of data, our project adheres to ethical research practices, emphasizing data privacy and the robust evaluation of model performance under diverse conditions.

### Conclusion
Our analysis offers valuable insights into the public discourse around breast cancer on Reddit. It underscores the importance of using social media analytics to bridge the knowledge gap between health professionals and the public, ultimately aiming to improve health communication and patient outcomes. Future directions include exploring advanced NLP models and AI tools to further enhance the effectiveness of health-related communication on social media platforms.
