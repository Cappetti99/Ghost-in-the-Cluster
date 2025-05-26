# Ghost in the Cluster

This project explores and compares different clustering algorithms — **Hierarchical Clustering** and **Spectral Clustering** — applied to a real-world dataset. The primary goal is to evaluate the effectiveness of each method and understand how clustering structure emerges from the data.

We used **PyCaret**, a low-code machine learning library, to streamline the process of unsupervised learning. It helped automate preprocessing, cluster creation, and visualization of the results.

## Key Highlights
- **Hierarchical Clustering** struggled to identify the underlying structure of the data.
- **Spectral Clustering**, despite initial challenges, performed well after adapting the data to a graph representation.
- The dataset was well-documented, aiding reproducibility and analysis.
- The project emphasized hands-on evaluation of clustering techniques rather than theoretical benchmarking.

> ⚠️ Note: The absence of a `requirements.txt` file originally led to package conflicts and slow startup — an important lesson in project setup and reproducibility.

## Setup

To run the notebook, we recommend using Python 3.10. First, create a virtual environment (optional but recommended), then install the dependencies:

```bash
pip install -r requirements.txt
