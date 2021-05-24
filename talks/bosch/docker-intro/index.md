---
marp: true

title: Docker Intro

paginate: false
_paginate: false

theme: default
style: |
  section {
    color: #555;
    text-align: left;
    font-size: 30px;
  }

  h1 {
      font-size: 60px;
  }

  h5 {
    font-size: 20px;
    color: grey;
    bottom: 20px;
    left: 20px;
    position: absolute;
  }

  h5 a {
    color: lightblue;
  }

---

# ![bg left:40% height:90px](https://www.docker.com/sites/default/files/d8/2019-07/horizontal-logo-monochromatic-white.png) Intro

<style scoped>
h2 {
    font-size: 30px;
    color: grey;
}
</style>
## some slides, much demo

##### Warning: Highly opinionated, best taken with a hint of humour

---

# Agenda

- What Docker is? Containers vs. VM
- Demos
  - Creating a Docker container (buildkit - buildx)
  - Docker Compose
  - Docker with GUI apps
  - Docker as Development Environment
    - SSH
    - Direct
  - ContainerSSH - https://containerssh.io/

- Docker in My Life
---

<!-- # What Docker is?  -->

![bg](https://www.backblaze.com/blog/wp-content/uploads/2018/06/whats-the-diff-container-vs-vm.jpg)

##### source: [BLACKBLAZE](https://www.backblaze.com/blog/vm-vs-containers/)




---

# Demo
## Creating a Docker container

![bg right fit](https://miro.medium.com/max/3600/0*CP98BIIBgMG2K3u5.png)

##### source: [Medium - Rocky Chen](https://medium.com/swlh/understand-dockerfile-dd11746ed183)

---

# Demo
## Docker Compose

![Docker Compose bg right 50%](https://github.com/docker/compose/raw/master/logo.png?raw=true)

--- 

# Demo
## Docker with GUI

![bg right size: 75%](https://miro.medium.com/max/1200/1*-a2_AsOLk5v4GjhdtLSGTw.png)

##### source: [Medium - Saravanan Sundaramoorthy](https://medium.com/@SaravSun/running-gui-applications-inside-docker-containers-83d65c0db110)

--- 

# Demo
## Docker DevEnv SSH

![bg right 40%](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/1024px-Visual_Studio_Code_1.35_icon.svg.png)
![bg right 30%](https://lh3.googleusercontent.com/pH5F_x-w_KCLIL-LgXX7EGpJMHKfUshKIQkxaqppd6MfxON-8IyCqi91t0RW9M3qzQ)
![bg right 50%](https://www.docker.com/sites/default/files/d8/styles/role_icon/public/2019-07/vertical-logo-monochromatic.png?itok=erja9lKc)

---

# Demo
## Docker DevEnv - Direct

![bg right:30% vertical](https://androidforums.com/attachments/blank-png.13613/)
![bg right 30%](https://plugins.jetbrains.com/assets/icons/jetbrains.png)
![bg right 30%](https://www.docker.com/sites/default/files/d8/styles/role_icon/public/2019-07/vertical-logo-monochromatic.png?itok=erja9lKc)

--- 

# Demo
## ContainerSSH - https://containerssh.io/

![bg right size: 75%](https://containerssh.io/images/hero-header.svg)

---

<style scoped>
  h1 {
    position: absolute;
    top: 50px;
  }
</style>

# Docker in My Life

- End (~90%) of dependency hell
- All my projects are developed in a container native fashion
- Saved a serious amount of time and headache
- Better traceability
- Helped try out new libs/tech/solutions
