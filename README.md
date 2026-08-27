# Hey, I'm Lehel Dsilva

Third-year Computer Engineering student at Fr. Conceicao Rodrigues College of Engineering, Mumbai.
Deeply interested in **ML systems** — from theory to implementation, spanning classical algorithms to neural architectures.

---

##  Technical Interests

- Machine Learning — Supervised, Unsupervised, Reinforcement Learning, Recommender Systems, Neural Networks
- Backend Engineering — APIs, databases, system design
- Competitive Programming — DSA in C++

---

##  Stack

![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

---

## Projects

### [Codebase Intelligence](https://github.com/Lehel721/Codebase-Intelligence-Project)
Ask natural language questions about any public GitHub repository without cloning it. Built a graph-augmented RAG pipeline that fetches code via GitHub API, parses structure using AST and Tree-sitter across 6 languages, builds call graphs with NetworkX, and detects architectural anomalies using Isolation Forest. Evaluated on LangChain Repository (2,384 files), a graph augmented retrieval achieved +16% improvement over baseline semantic search on cross-file dependency questions.

`Python` `RAG` `ChromaDB` `NetworkX` `Tree-sitter` `Isolation Forest` `Claude API`

### [wiki-rank-search](https://github.com/Lehel721/search-rank)
Two-stage semantic search engine over 100k Wikipedia passages. Built a qrels-first corpus pipeline guaranteeing full label coverage from Google's Natural Questions dataset (via BEIR), FAISS dense retrieval with hard negative mining, and a LightGBM LambdaRank reranker trained on 21,461 labeled pairs. Evaluated with a proper train/test split by query, achieving an MRR of 0.90 on held-out queries and 0.81 on the subset where raw retrieval alone missed the correct passage, validated on Google Colab after local hardware constraints required optimizing the pipeline for memory efficiency.

`Python` `FAISS` `LightGBM` `fastembed` `scikit-learn` 

##  Reach Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lehel-dsilva9511/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:leheldsilva2006@gmail.com)
