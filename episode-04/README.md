# Episode 4: The Harbourmaster's Tower — The Control Plane ☕

The control plane is the harbourmaster’s tower: API server, scheduler, controllers, and etcd working together to keep desired state and actual state aligned.

- **Source article (Markdown)**: `https://github.com/vanHeemstraPublications/dev-to/blob/main/articles/container-harbour-ep04.md`
- **Cover image**: `https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-04.png`

## 🎯 What You’ll Learn

- The core control plane components and what each one does
- Why the **API server** is the front door for “everything”
- Why **etcd** matters (single source of truth)
- How scheduling + reconciliation happens at a high level

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

This episode is primarily conceptual. A handy exploration command set:

- `kubectl cluster-info`
- `kubectl get componentstatuses` (older clusters) / control plane health endpoints (newer setups)

## 📚 Additional Resources

- [Control Plane Components](https://kubernetes.io/docs/concepts/architecture/#control-plane-components)
