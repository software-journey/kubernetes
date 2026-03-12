# Episode 15: Leaving Harbour Gracefully 🌅

The grand finale: rolling updates and zero-downtime deployments—change everything, break nothing.

**[📖 Read the full article on Dev.to](https://dev.to/the-software-s-journey/welcome-to-container-harbour-ep15-1p4c)**

<image src="https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-15.png">

## 🎯 What You’ll Learn

- How rolling updates work at a high level
- Why readiness checks + gradual rollout prevent downtime
- How to think about “deploy during peak traffic and nobody notices”

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `deployment.yaml` with update strategy and probes
- `kubectl rollout status deployment/<name>`
- `kubectl rollout undo deployment/<name>`

## 📚 Additional Resources

- [Rolling updates](https://kubernetes.io/docs/tutorials/kubernetes-basics/update/update-intro/)
