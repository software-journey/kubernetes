# Episode 11: The Health Inspector Visits 🩺

“Running” isn’t enough. Probes tell Kubernetes whether your app is alive and whether it’s actually ready to receive traffic.

**[📖 Read the full article on Dev.to](https://dev.to/the-software-s-journey/welcome-to-container-harbour-ep11-5d5h)**

<image src="https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-11.png">

## 🎯 What You’ll Learn

- The difference between **liveness** and **readiness**
- How probes prevent Services from routing traffic to “technically running” but broken Pods
- How kubelet uses probe results to restart unhealthy containers

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `deployment.yaml` with `livenessProbe` and `readinessProbe`
- `kubectl describe pod <name>` to see probe events

## 📚 Additional Resources

- [Configure Liveness, Readiness and Startup Probes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/)
