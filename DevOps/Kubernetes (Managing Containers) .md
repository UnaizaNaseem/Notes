<h1 align="center">Kuberneters</h1>
Kubernetes is a container orchestrating tool that in simple words means managing containers.

<p align="center">
<img src="https://github.com/UnaizaNaseem/Notes/assets/73931604/f97154f4-c48e-4db0-a13e-fa7496e1611e">
</p>

<h1 align="center">What is the need for container orchestrating? </h1>

<p align="center">
<img src="https://github.com/UnaizaNaseem/Notes/assets/73931604/d855d5c2-ca53-4570-88eb-df127a5624df">
</p>
When multiple services run inside containers, there arises a need to scale them. 
Scaling containers is hard as it increases the cost to maintain services, and the complexity to run them side by side. This is where Container Orchestration Engine comes in.

<h1 align="center"> Kubernetes Features </h1>
- Automated Scheduling: Kubernetes schedules containers on cluster nodes based on their needs, ensuring availability.
- Self-Healing Capabilities: Kubernetes replaces unresponsive containers and reschedules them when nodes fail, ensuring application reliability.
- Automated Rollouts & Rollback: Kubernetes manages application changes and can easily revert them if issues arise, minimizing disruptions.
- Horizontal Scaling & Load Balancing: Kubernetes scales the application up or down as needed, distributing the workload efficiently for optimal performance.

<h1 align="center"> Kubernetes Architecture </h1>
it consists of mainly two parts:
- Master nodes: It is responsible for the management of the whole cluster. it is an entry point for all administrative tasks. More than one master node can exist in a cluster.

<p align="center">
<img src="https://github.com/UnaizaNaseem/Notes/assets/73931604/57252e66-a2c0-46cc-98a0-cd1ae3f0e236"></p>
- Worker/Slave nodes: These nodes consist of necessary services to manage the networking between the containers, communicate with the master node, and assign resources to the scheduled containers.
<p align="center">
<img src="https://github.com/UnaizaNaseem/Notes/assets/73931604/0245fca4-9dc8-448e-9574-b21b2bb60929">
</p>

  - Kubelet: Kubelet gets the configuration of a Pod from the API server and ensures that the described containers are up and running.
  - Kube-proxy: Kube-proxy acts as a network proxy and a load balancer for a service on a single worker node

<h1 align="center"> Simple how to use Kubernetes </h1>

- Choose a method to install Kubernetes.
- Create a file in YAML format that describes your application's settings, including the number of containers, networking details, and other specifications.
- Use the Kubernetes CL tool called "kubectl" to create a deployment based on the configuration file.
- This deployment will handle the lifecycle of the application.
- To handle increased demand or optimize resource utilization, the number of replicas deployment configurations can be adjusted by using the "kubectl scale" command to scale up or down.
- changes to the configuration file or container image can be applied using the "kubectl apply" command.
- Kubernetes allows you to easily roll back to the previous version.
