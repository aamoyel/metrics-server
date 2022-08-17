# Metrics Server w/ kustomize
<div id="top"></div>

<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>
</br>



<!-- ABOUT THE PROJECT -->
## About The Project

This project allows you to deploy [Metrics Server](https://github.com/kubernetes-sigs/metrics-server) on Kubernetes with Kustomize binary.

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With
* [Kubernetes](https://kubernetes.io/)
* [Kustomize](https://kustomize.io/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
You need to have :
* Kubernetes cluster
* Kustomize binary

### Installation
1. Clone the repo :
   ```sh
   git clone https://github.com/aamoyel/metrics-server.git && cd metrics-server
   ```
3. Deploy the project on your cluster
   ```sh
   kustomize build . | kubectl apply -f -
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Alan Amoyel - [@AlanAmoyel](https://twitter.com/AlanAmoyel)

Project Link: [https://github.com/aamoyel/metrics-server](https://github.com/aamoyel/metrics-server)

<p align="right">(<a href="#top">back to top</a>)</p>
