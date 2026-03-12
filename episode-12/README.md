# Episode 12: Rush Hour at the Harbour — Autoscaling Under Pressure 📈

Autoscaling is how you handle traffic spikes without waking up at 3am: scale Pods, and (when needed) scale nodes.

**[📖 Read the full article on Dev.to](https://dev.to/the-software-s-journey/welcome-to-container-harbour-ep12-1cm0)**

<image src="https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-12.png">

## 🎯 What You’ll Learn

- What the **HPA** does (scale replicas based on metrics)
- How node capacity becomes the next bottleneck (and how cluster autoscaling helps)
- The mental model: demand signals → scaling decisions → more capacity

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `deployment.yaml` with resource requests/limits
- `hpa.yaml`

## 📚 Additional Resources

- [Horizontal Pod Autoscaling](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)
