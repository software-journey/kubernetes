# Episode 8: Sealed Cargo Manifests — ConfigMaps and Secrets 🔐

Configuration should not be baked into images. ConfigMaps and Secrets are Kubernetes’ way to deliver config safely at runtime.

**[📖 Read the full article on Dev.to](https://dev.to/the-software-s-journey/welcome-to-container-harbour-ep08-####)**

- **Cover image**: `https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-08.png`

## 🎯 What You’ll Learn

- When to use **ConfigMaps** vs **Secrets**
- How Pods consume configuration (env vars and mounted files)
- The “golden rule”: keep sensitive and environment-specific config out of images

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `configmap.yaml`
- `secret.yaml`
- `deployment.yaml` (consuming both)

## 📚 Additional Resources

- [ConfigMaps](https://kubernetes.io/docs/concepts/configuration/configmap/)
- [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)
