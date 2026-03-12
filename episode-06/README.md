# Episode 6: The Harbour Gates — Services and How Traffic Flows In 🚦

Pods come and go; IPs change. Services are the stable harbour gate that traffic can reliably flow through.

**[📖 Read the full article on Dev.to](https://dev.to/the-software-s-journey/welcome-to-container-harbour-ep06-####)**

- **Cover image**: `https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-06.png`

## 🎯 What You’ll Learn

- Why Pod IPs are **not** a stable way to reach an app
- How a **Service** selects Pods via labels and provides stable addressing
- The basics of load balancing traffic across multiple Pods

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `deployment.yaml` + `service.yaml`
- `kubectl apply -f deployment.yaml -f service.yaml`
- `kubectl get svc`

## 📚 Additional Resources

- [Services](https://kubernetes.io/docs/concepts/services-networking/service/)
