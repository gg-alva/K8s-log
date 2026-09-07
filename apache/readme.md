#  Daily Learning: Kubernetes Autoscaling, Configuration & Helm

Over the weekend and today, I continued my **Kubernetes learning**, focusing on autoscaling, configuration management, and Helm. Along with understanding the concepts, I also practiced them hands-on.

###  Horizontal Pod Autoscaler (HPA)

I learned about **HPA**, which allows Kubernetes to automatically adjust the number of Pod replicas based on resource utilization.

I understood how HPA can:

* Monitor resource utilization such as CPU and memory.
* Automatically increase the number of Pods when demand increases.
* Reduce the number of Pods when resource utilization decreases.
* Help applications handle changing workloads efficiently.

### Vertical Pod Autoscaler (VPA)

I also explored **VPA**, which focuses on managing the resource requirements of individual Pods.

I learned how VPA can adjust **CPU and memory requests and limits** based on the resource requirements of the workload, helping Pods receive appropriate resources.

###  ConfigMaps & Secrets

I learned about **ConfigMaps and Secrets**, which are used to manage application configuration separately from the application code.

* **ConfigMap** – Used to store non-sensitive configuration data and environment variables.
* **Secret** – Used to store sensitive information such as passwords, tokens, and credentials.

This helped me understand how Kubernetes applications can be configured without hardcoding configuration values directly into application images.

---

#  Helm

Today, I started learning **Helm**, the package manager for Kubernetes.

I installed and configured Helm and explored how it simplifies the process of deploying and managing applications in Kubernetes.

### Helm Charts

I learned about the **structure of Helm Charts** and how charts package the Kubernetes resources required to deploy an application.

I explored important components such as:

* `Chart.yaml`
* `values.yaml`
* `templates/`
* `charts/`
* Helm releases

Understanding this structure helped me see how Kubernetes manifest files can be organized into reusable and configurable application packages.

### Artifact Hub

I also explored **Artifact Hub**, which provides a platform for discovering and sharing Kubernetes packages and Helm Charts.

I used Artifact Hub to find a **MongoDB Helm Chart**, added the required repository, and deployed MongoDB into my Kubernetes environment.

I then practiced basic Helm commands to manage the deployment, including commands for:

* Adding Helm repositories
* Searching for charts
* Installing charts
* Listing releases
* Checking release status
* Upgrading releases
* Uninstalling releases