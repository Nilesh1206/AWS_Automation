# AWS Automation with Ansible

### What is Ansible ?
   * ```Ansible``` is a software tool that provides simple but powerful automation for cross-platform computer support. 
   * It is primarily intended for IT professionals, who use it for application deployment, updates on workstations and servers, cloud provisioning, configuration management, intra-service orchestration, and nearly anything a systems administrator does on a weekly or daily basis.

### How Ansible Works?
   In Ansible, there are two categories of computers: the control node and managed nodes. The control node is a computer that runs Ansible. There must be at least one control node, although a backup control node may also exist. A managed node is any device being managed by the control node.

Ansible works by connecting to nodes (clients, servers, or whatever you're configuring) on a network, and then sending a small program called an Ansible module to that node. Ansible executes these modules over ```SSH``` and removes them when finished. The only requirement for this interaction is that your Ansible control node has login access to the managed nodes. SSH keys are the most common way to provide access, but other forms of authentication are also supported.


### Aws With Ansible
   * When we deploy an application into AWS, we will soon realize that the cloud is much more than a collection of servers in someone else's data center. 
   * We now have a fleet of services available to we to rapidly deploy and scale applications. However, if we continue to manage AWS like just a group of servers, we won’t see the full benefit of our migration to the cloud. 
   * Ansible automation can help us manage your AWS environment like a fleet of services instead of a collection of servers.


<a href="https://www.linkedin.com/pulse/task3-ansible-deploying-load-balancer-webservers-aws-nilesh-gopale/" target="_blank">Click here for futher explanation </a>

### Contributor
   * <a href="https://github.com/Nilesh1206">Nilesh Gopale</a>
