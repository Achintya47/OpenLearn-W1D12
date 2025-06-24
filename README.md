# OpenLearn-W1D12
Hierarchical Clustering and Dendrograms
# 🔗 Hierarchical Clustering & Dendrograms – Hands-On

Welcome to the companion notebook for my blog post on **Hierarchical Clustering**.  
This notebook takes you step-by-step through the logic, implementation, and visualization of clustering using **dendrograms** and **distance matrices** — all with clean code and real examples.

---

## 📌 What You'll Learn

- ✅ What is **Hierarchical Clustering**
- ✅ How to compute a **Proximity (Distance) Matrix** using `pdist`
- ✅ How to build a **Linkage Matrix** using `linkage`
- ✅ How to draw a **Dendrogram** and interpret merge levels
- ✅ How to **cut the dendrogram** to form desired number of clusters
- ✅ How to switch between different **distance metrics** (Euclidean, Manhattan, Cosine)
- ✅ BONUS: A simple student marks example to **visualize clustering manually**

---

## 🧪 Hands-On Techniques Covered

| Concept | Library | Function |
|--------|---------|----------|
| Distance Matrix | `scipy.spatial.distance` | `pdist`, `squareform` |
| Clustering | `scipy.cluster.hierarchy` | `linkage`, `fcluster` |
| Visualization | `matplotlib.pyplot` | `dendrogram`, `plt.figure()` |

---

## 📘 Contents

```python
1. Load a simple dataset (Wine dataset and student marks)
2. Compute distance matrix (Euclidean, Manhattan, Cosine)
3. Apply hierarchical clustering (Ward, Single, Complete)
4. Visualize dendrograms
5. Cut dendrograms at specific thresholds
6. Interpret linkage and proximity matrices
