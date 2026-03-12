# Episode 10: ID Badges and Security Guards — RBAC 🪪

RBAC is how you prevent “everyone is cluster-admin” disasters. Least privilege is the goal; reduced blast radius is the reward.

- **Source article (Markdown)**: `https://github.com/vanHeemstraPublications/dev-to/blob/main/articles/container-harbour-ep10.md`
- **Cover image**: `https://raw.githubusercontent.com/vanHeemstraPublications/dev-to/main/images/welcome-to-container-harbour-episode-10.png`

## 🎯 What You’ll Learn

- What RBAC is: **who** can do **what** to **which resources**, **where**
- The basic building blocks: Roles, ClusterRoles, RoleBindings, ClusterRoleBindings
- Why limiting permissions limits mistakes and security incidents

## 📁 Files in This Episode

- **`README.md`**: This guide and links to the article

## 🚀 Quick Start

If you add manifests for this episode, consider:

- `role.yaml` / `rolebinding.yaml` for namespace-scoped access
- `clusterrole.yaml` / `clusterrolebinding.yaml` for cluster-scoped access

## 📚 Additional Resources

- [Using RBAC Authorization](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
