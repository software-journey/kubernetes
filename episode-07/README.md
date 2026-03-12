# Episode 7: The Customs Office — Ingress and Smart Traffic Routing 🛃

Ingress is the “one gate” that can route external HTTP(S) traffic to the right internal Services—without spinning up 17 load balancers.

**[📖 Read the full article on Dev.to](https://dev.to/the-software-s-journey/welcome-to-container-harbour-ep7-kjd)**

<image src="https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-07.png">

## 🎯 What You’ll Learn

- Why Ingress exists (consolidate external entry points)
- How host/path routing rules map to Services
- Where TLS termination and “smart routing” fits in

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `service.yaml`
- `ingress.yaml`
- `kubectl apply -f service.yaml -f ingress.yaml`

## 📚 Additional Resources

- [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)
