# Episode 5: Forklift Operators Who Never Sleep 🔁

Manually managing Pods is chaos. Deployments and ReplicaSets are the forklift crew that keeps the right number of Pods running.

- **Source article (Markdown)**: `https://github.com/vanHeemstraPublications/dev-to/blob/main/articles/container-harbour-ep05.md`
- **Cover image**: `https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-05.png`

## 🎯 What You’ll Learn

- What a **ReplicaSet** does (keep \(N\) Pods alive)
- What a **Deployment** adds on top (rollouts, updates, history)
- How controllers keep the “desired number of containers at the quay” true over time

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `deployment.yaml`
- `kubectl apply -f deployment.yaml`
- `kubectl rollout status deployment/<name>`

## 📚 Additional Resources

- [Deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
