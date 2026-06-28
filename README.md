# Finding Similar Items with Locality-Sensitive Hashing (LSH)
### Project 1 for Algorithms for Massive Data (2025/26)

* **Dataset:** Cornell University arXiv Paper Abstracts (5.35 GB Metadata)
* **Algorithm:** Self-implemented Pipeline from Scratch (Text Shingling, Min-Hashing, and LSH)
* **Environment:** Developed in VS Code / Executed on Google Colab

---

### 📌 Project Executive Summary
This project implements a highly scalable duplicate and similarity detection engine for academic papers without relying on high-level blackbox machine learning APIs. 

By restructuring raw natural language into mathematical sets (**Hash Shingling**), compressing high-dimensional spaces via universal hash collections (**Min-Hashing**), and partitioning signatures into localized bins (**LSH**), the system breaks the quadratic $O(N^2)$ computational bottleneck. It effectively maps the runtime complexity down to a near-linear $O(N)$ pipeline, demonstrating true industrial scalability on massive textual datasets.
