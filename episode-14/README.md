# Episode 14: Reserved Berths for Divas — StatefulSets 🎭

Stateful workloads need stable identity and stable storage. StatefulSets provide the reserved berths your “diva” databases demand.

- **Source article (Markdown)**: `https://github.com/vanHeemstraPublications/dev-to/blob/main/articles/container-harbour-ep14.md`
- **Cover image**: `https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-14.png`

## 🎯 What You’ll Learn

- Why a database often can’t behave like a normal Deployment
- What StatefulSets guarantee: stable names, ordered rollout, stable storage via claims
- How headless Services fit into addressing StatefulSet Pods

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `headless-service.yaml`
- `statefulset.yaml`
- `pvc-template.yaml` (if you break it out)

## 📚 Additional Resources

- [StatefulSets](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/)
