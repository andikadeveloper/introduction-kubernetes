---
class: text-center
highlighter: shiki
drawings:
  persist: false
---

# Introduction to Kubernetes

@andikadeveloper

---

# Deploying an Application
(Ref: [Container Evolution](https://kubernetes.io/docs/concepts/overview))
<v-switch>
  <template #1>
    1. Traditional Deployment
    <img src="/img/traditional-deployment.png" class="h-120">
  </template>
  <template #2>
    2. Virtualized deployment
    <img src="/img/virtualized-deployment.png" class="h-120">
  </template>
  <template #3>
    3. Container deployment
    <img src="/img/container-deployment.png" class="h-120">
  </template>
</v-switch>

---

# Docker
<v-clicks>

- Container Manager/Container Runtime
- Build, Run, and Share Containerized Applications
- <img src="/img/docker-logo.png" class="h-80">
- Practice running a container
</v-clicks>

---

# Kubernetes (Container Orchestration)
<v-switch>
  <template #1>
    <img src="/img/orchestration-music.png" class="h-100">
  </template>
  <template #2>
    Automating:

    - deployment
    - scale
    - and manage containerized applications
  </template>
  <template #3>
    Tools: Kubernetes
  </template>
</v-switch>

---

# Flow
(Explained on meeting with scribble)
<br>
Ref: [Kubernetes](https://kubernetes.io/docs/concepts/overview/components)

---

# minikube
(Ref: [minikube](https://minikube.sigs.k8s.io/docs/))
<v-clicks>

- Local Kubernetes Cluster
- Learning and Development

</v-clicks>

---

# kubectl
(Ref: [kubectl](https://kubernetes.io/docs/reference/kubectl/))

<v-clicks>

- CLI for Kubernetes
- Interact with Kubernetes Cluster
</v-clicks>

---

# Kubernetes Objects
(Ref: [Kubernetes Objects](https://kubernetes.io/docs/concepts/overview/working-with-objects/kubernetes-objects/))

- Pods
- Services
- Deployments

---

# Practice

- Deploy a nginx application
- Using Pods, Services, and Deployments

---

# Flow Pods, Services, and Deployments
(Explained on meeting with scribble)

---

# Practice Real Case
- Deploy a containerized application
- Build a Docker image
- Deploy to Kubernetes Cluster
- Expose the application to the internet
- Link Repo:

---
class: text-center
layout: center
---

# Thanks
@andikadeveloper
