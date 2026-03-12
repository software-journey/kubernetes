# Episode 9: The Long-Term Warehouse — Persistent Volumes and Storage 🏭

Pods are ephemeral freight containers. Databases aren’t. Persistent storage is the warehouse your data can live in even when Pods come and go.

**[📖 Read the full article on Dev.to](https://dev.to/the-software-s-journey/welcome-to-container-harbour-ep09-####)**

- **Cover image**: `https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-09.png`

## 🎯 What You’ll Learn

- Why Pod filesystems are ephemeral (and why that’s intentional)
- The relationship between **PVCs** (claims) and **PVs** (the actual storage)
- How storage stays attached across Pod restarts/replacements

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `pvc.yaml`
- `deployment-or-statefulset.yaml` that mounts the claim

## 📚 Additional Resources

- [Persistent Volumes](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)
