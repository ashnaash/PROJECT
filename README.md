# GitOps Workflow using ArgoCD on Kubernetes

## Objective
Implement GitOps by syncing Kubernetes deployment states directly from a Git repository.

## Tools Used
- **K3s / Minikube** – Lightweight Kubernetes cluster
- **ArgoCD (Free)** – GitOps continuous delivery tool
- **GitHub** – Version control and GitOps repo
- **Docker** – Containerization platform

---

## Mini Guide

### 1. Deploy ArgoCD on Kubernetes
- Install ArgoCD in your Kubernetes cluster.
- Expose the ArgoCD server for accessing the UI.

### 2. Push Deployment Manifests to Git
- Create a GitHub repository.
- Add Kubernetes manifests (YAML files) for your application.
- Push changes to the repository.

### 3. Configure ArgoCD to Sync with Git
- Connect ArgoCD to your GitHub repository.
- Enable **auto-sync** so changes in Git trigger deployments automatically.

### 4. Update via Git Commits
- Modify deployment manifests in Git.
- Commit and push the changes.
- ArgoCD detects changes and updates the Kubernetes cluster accordingly.

---

## Deliverables
- ✅ GitHub repository with manifest files  
- ✅ ArgoCD screenshots showing sync in action  
- ✅ Video/notes explaining GitOps flow  
- ✅ Resume line:  
  *"Implemented GitOps pipeline using ArgoCD and Kubernetes"*

---

## Resume Bullet
