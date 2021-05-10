# Ansible-Task-3-

What is Load Balancer ?
Load balancing is defined as the methodical and efficient distribution of network or application traffic across multiple servers in a server farm. Each load balancer sits between client devices and backend servers, receiving and then distributing incoming requests to any available server capable of fulfilling them.

![image](https://user-images.githubusercontent.com/73941735/117698385-51056c80-b1e1-11eb-9805-baa69d7fa2d3.png)




Create 5 ec2 Instances. 
1 — — Ansible Node (Controller Node) — t3.micro
1 — — LoadBalancer — t2.micro
3 — — Webserver — t2.micro
here i have used ansible to launch ec2 instances. code for launching ec2 instance using Ansible.


and configure the ansible and haproxy and lauch the playbook 
