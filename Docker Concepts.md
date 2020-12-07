#### What is docker ?
- platform for developers/sysadmins to **build**, **run**, and **share** applications with [[Containers|containers]] -> it's used to deploy app and called *containerization*
#### Why containerization is incresingly popular ?
it's because:
- **flexible**: even the most complex app can be containerized
- **lightwieght**: leverage and share the host kernel -> much more efficient in terms of system resources than virtual machines
- **portable**: can build locally, deploy to the cloud, and run anywhere
- **loosly coupled**: highly self sufficient & encapsulated > allowing to replace or upgrade one without disrupting others
- **scalable**: increase and automatically distribute it's replicas across datacenter
- **secure**: apply aggresive constrainsts & isolations ->(to) process without any configuration required ont the part of the user 
#### About image and containers
- [[Image]] 
- [[Containers]]
#### Containers and virtual machines
[[Containers]] :
- runs *natively* on linux
- shares kernel of the host machines with other containers
- runs a discrete process, taking no more memory than any other executable -> lightweight
![](https://docs.docker.com/images/Container%402x.png)

**virtual machine** (VM):
- runs a full blown "guest" operating system with virtual access to host resources throught a hypervisor.
- generally, incur a lot of overhead beyond what is consumed by your application logic
![](https://docs.docker.com/images/VM%402x.png)

source: https://docs.docker.com/get-started/