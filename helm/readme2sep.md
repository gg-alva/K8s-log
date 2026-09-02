# Daily Learning: Deploying Prometheus & Grafana with Helm

Today sep 2, Started with the uderstanding of the obserrvability concepts and I continued my **observability and monitoring learning** by getting hands-on with **Prometheus and Grafana** in a Kubernetes environment.

### Prometheus Installation

I installed **Prometheus using a Helm Chart** and configured it within a dedicated Kubernetes **monitoring namespace**.

This helped me understand how Helm simplifies the deployment of monitoring components and how applications can be organized into separate namespaces.

### Grafana Installation

I also deployed **Grafana using Helm** alongside Prometheus.

Grafana provides a visualization layer for monitoring data, allowing metrics collected by Prometheus to be presented through **dashboards, graphs, and panels**.

### Hands-on Kubernetes Configuration

During the setup, I practiced:

* Creating and working with a dedicated `monitoring` namespace.
* Adding and using Helm repositories.
* Installing Prometheus through a Helm Chart.
* Installing Grafana through a Helm Chart.
* Checking Helm releases and Kubernetes resources.
* Understanding how monitoring components are deployed as Kubernetes workloads.
* Exploring how Grafana can use Prometheus as a metrics data source.
