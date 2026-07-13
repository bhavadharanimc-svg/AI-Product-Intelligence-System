# AI Product Intelligence System using CLIP Embeddings

## Overview

This project extends a base AI Product Intelligence System by implementing three additional features using OpenAI's CLIP (Contrastive Language–Image Pre-training) embeddings. The system leverages multimodal representations to improve product discovery, catalog management, and semantic search in an e-commerce setting.

The project was developed as part of an AlgoUniversity assignment and demonstrates the practical application of computer vision, embedding-based retrieval, clustering, and natural language search.

---

## Features

### Recommendation Engine

A recommendation system that suggests complementary products instead of visually identical items. It combines predefined category mappings with cosine similarity between CLIP image embeddings to recommend products that are visually compatible with the selected item.

### Unique Catalog (Duplicate Detection)

A duplicate detection pipeline built using Agglomerative Clustering on CLIP image embeddings. Products belonging to the same cluster are treated as potential duplicates, enabling the creation of a cleaner and more organized product catalog.

### Reverse Product Search

A semantic search system that converts user text queries into CLIP text embeddings and compares them directly with image embeddings. This allows users to retrieve relevant products using natural language descriptions.

---

## Technologies Used

- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- OpenAI CLIP
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Pillow

---

## Project Workflow

1. Load the product dataset.
2. Generate CLIP image embeddings.
3. Normalize the embeddings.
4. Build similarity-based retrieval.
5. Recommend complementary products.
6. Detect duplicate products using Agglomerative Clustering.
7. Perform reverse product search using CLIP text embeddings.

---

## Project Structure

```
AI-Product-Intelligence-System/
│
├── AI_Product_Intelligence_System.ipynb
├── README.md
├── report.pdf
├── requirements.txt
└── screenshots/
    ├── dataset.png
    ├── recommendation.png
    ├── duplicate_detection.png
    ├── duplicate_group.png
    ├── reverse_search_1.png
    └── reverse_search_2.png
```

---

## Results

The implemented extensions successfully improve the functionality of the Product Intelligence System.

- Recommendation Engine for complementary product suggestions.
- Duplicate detection through embedding-based clustering.
- Natural language product retrieval using CLIP's shared embedding space.

Example outputs are available in the `screenshots` directory.

---

## Future Improvements

- Integrate user purchase history for personalized recommendations.
- Evaluate density-based clustering algorithms such as DBSCAN.
- Replace exhaustive similarity search with FAISS for improved scalability.
- Fine-tune CLIP on domain-specific fashion datasets.
- Develop an interactive web interface using Streamlit.

---

## Learning Outcomes

This project provided practical experience with:

- Multimodal AI using CLIP
- Image and text embeddings
- Cosine similarity
- Recommendation systems
- Agglomerative Clustering
- Semantic image retrieval
- Product intelligence for e-commerce

---

## Acknowledgement

This project was completed as part of an assignment for **AlgoUniversity**, focusing on extending an AI Product Intelligence System with practical applications of CLIP embeddings.

---

## License

This repository is intended for educational and learning purposes.
