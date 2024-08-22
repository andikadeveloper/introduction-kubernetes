---
class: text-center
highlighter: shiki
drawings:
  persist: false
---

# Introduction to Kubernetes

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

# Container
<img src="/img/container.png" class="h-100">
---

# Docker
<v-clicks>

- <img src="/img/docker-logo.png" class="h-80">
- Container Manager/Container Runtime
- Build, Run, and Share Containerized Applications
- Practice running a container
</v-clicks>

---

# Kubernetes (Container Orchestration)
<v-switch>
  <template #1>
    <img src="/img/orchestration-music.png" class="h-100">
  </template>
  <template #2>
    <ul>
      <li>High Availability</li>
      <li>Auto Scaling</li>
      <li>Manage container</li>
    </ul>
  </template>
</v-switch>

---

# Flow
Ref: [Kubernetes](https://kubernetes.io/docs/concepts/overview/components)
<img src="/img/simple-kubernetes-flow.png">

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
- Ingress

---

# Flow
<img src="/img/kubernetes-object.png" class="h-100">

---

# Practice

- Deploy a nginx application
- Using Pods, Services, and Deployments

---

# Practice deploy real project
<img src="/img/deployed-project.png" class="h-100">

---

# Practice deploy real project

<v-clicks>

<ol>
  <li>
  Clone the repo:
  <a href="https://github.com/andikadeveloper/excalidraw">Here</a>
  </li>
  <li>Build a containerized application</li>
  <li>Create kubernetes yaml file</li>
  <li>Apply yaml file to Kubernetes Cluster</li>
  <li>Expose the application to the internet</li>
  <li>
    Edit etc hosts
    <ul>
      <li>
      Linux/MacOS:
      <br>
      <i>sudo vim /etc/hosts</i>
      </li>
      <li>
      Windows:
      <a href="https://en.wikiversity.org/wiki/Hosts_file/Edit">Link</a>
      </li>
    </ul>
  </li>
  <li>
  Enable Ingress:
  <br>
  <i>minikube addons enable ingress</i>
  </li>
  <li>Add and apply Ingress yaml file</li>
  <li>
  Make the application accessible using minikube:
  <br>
  <i>minikube tunnel</i>
  </li>
</ol>

</v-clicks>

---
class: text-center
layout: center
---

# Thanks
[@andikadeveloper](https://github.com/andikadeveloper)
