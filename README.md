# Basic Docker Commands

<p>&nbsp;</p>
<table style="width: 772px;">
<tbody>
<tr>
<td style="width: 403px;">
<p>docker --version</p>
</td>
<td style="width: 353px;">
<p>get the installed docker version</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker pull hello-world</p>
</td>
<td style="width: 353px;">
<p>download the image "<strong>hello-world</strong>" from the docker repository (<strong>hub.docker.com</strong>)</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker images</p>
</td>
<td style="width: 353px;">
<p>list all the images that are locally stored with the docker engine</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker run hello-world</p>
</td>
<td style="width: 353px;">
<p>create a container from the image "<strong>hello-world</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p><strong>docker container ls -a</strong></p>
</td>
<td style="width: 353px;">
<p>list all containers</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p><strong>docker container ls -a -s</strong></p>
</td>
<td style="width: 353px;">
<p>list the size for all containers</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker rmi 515d5e66f68a</p>
</td>
<td style="width: 353px;">
<p>remove the docker image "<strong>hello-seattle</strong>" with image id "<strong>515d5e66f68a</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker rm d9bf06498bb2</p>
<p>&nbsp;</p>
</td>
<td style="width: 353px;">
<p>remove the docker container with container id "<strong>d9bf06498bb2</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker history hello-world</p>
</td>
<td style="width: 353px;">
<p>display the history of the image "<strong>hello-world</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker info</p>
</td>
<td style="width: 353px;">
<p>get detailed information about docker installed on the system including the kernel version, number of containers and images, etc.</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker volume create</p>
</td>
<td style="width: 353px;">
<p>create a volume which docker container will use to store data</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker volume ls</p>
</td>
<td style="width: 353px;">
<p>list all the volumes known to Docker</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker logs c70201336fd8</p>
</td>
<td style="width: 353px;">
<p>display the logs of the docker container with contained id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker search hadoop</p>
</td>
<td style="width: 353px;">
<p>search for &nbsp;docker image "<strong>hadoop</strong>" on dockerhub</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker network ls</p>
</td>
<td style="width: 353px;">
<p>list all docker networks</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker login</p>
</td>
<td style="width: 353px;">
<p>login into docker repository (<strong>hub.docker.com</strong>)</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker logout</p>
</td>
<td style="width: 353px;">
<p>logout from docker repository (<strong>hub.docker.com</strong>)</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker start c70201336fd8</p>
</td>
<td style="width: 353px;">
<p>start the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker stop c70201336fd8</p>
</td>
<td style="width: 353px;">
<p>stop the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker restart c70201336fd8</p>
<p>&nbsp;</p>
</td>
<td style="width: 353px;">
<p>restart the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker inspect c70201336fd8</p>
</td>
<td style="width: 353px;">
<p>get&nbsp; detailed information&nbsp; about the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker stats c70201336fd8</p>
</td>
<td style="width: 353px;">
<p>get the statistics of the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker image ls</p>
</td>
<td style="width: 353px;">
<p>List all images that are locally stored with the docker engine.</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker system prune</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
</td>
<td style="width: 353px;">
<p>delete all unused containers, unused networks, and dangling images</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>systemctl status docker</p>
</td>
<td style="width: 353px;">
<p>check the Docker service</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>systemctl start docker</p>
</td>
<td style="width: 353px;">
<p>start the Docker service</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker image prune</p>
</td>
<td style="width: 353px;">
<p>remove unused images</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker save hello-world &gt; hello-world.tar</p>
<p>&nbsp;</p>
</td>
<td style="width: 353px;">
<p>save the image "<strong>hello-world</strong>" to a tar archive</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker load &lt; hello-world.tar</p>
</td>
<td style="width: 353px;">
<p>load the image "<strong>hello-world</strong>" from the saved tar file</p>
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker export a27999b71e62 &gt; hello-world.tar</p>
<p>&nbsp;</p>
</td>
<td style="width: 353px;">
<p>export the docker container with container id " <strong>a27999b71e62</strong>" as a tar archive</p>
</td>
</tr>
<tr>
<td style="width: 403px;">
<p>docker import hello-world.tar</p>
</td>
<td style="width: 353px;">
<p>import the contents from hello-world.tar</p>
</td>
</tr>
</tbody>
</table>
</br>
<h2> Papers </h2>

<ul>

                             

 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(1).pdf" style="text-decoration:none;">Comparative Analysis on Docker and Virtual Machine in Cloud Computing</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(2).pdf" style="text-decoration:none;">An Introduction to Docker and Analysis of its Performance</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(3).pdf" style="text-decoration:none;">An introduction to Docker for reproducible research, with examples from the R environment</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(4).pdf" style="text-decoration:none;">A Comparative Study of Containers and Virtual Machines in Big Data Environment</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(5).pdf" style="text-decoration:none;">Docker Toolkit for Data Scientists – How to Start Doing Data Science in Minutes!</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(6).pdf" style="text-decoration:none;">2019 Container
Adoption Survey</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(7).pdf" style="text-decoration:none;">Design patterns for container-based distributed systems</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(8).pdf" style="text-decoration:none;"> The impact of Docker containers on the
performance of genomic pipelines </a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(9).pdf" style="text-decoration:none;">An Introduction to Docker and Analysis of its Performance</a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(10).pdf" style="text-decoration:none;">Building a Secure Software Supply Chain using Docker </a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(11).pdf" style="text-decoration:none;">Oracle Database Docker Containers on HPE 3PAR Storage</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(12).pdf" style="text-decoration:none;">In Search of the Ideal Storage Configuration for Docker Containers</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(13).pdf" style="text-decoration:none;">Load Balancing using Docker and Kubernetes: A Comparative Study</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(14).pdf" style="text-decoration:none;">Using R via Rocker - A Brief Introduction to Docker for R</a></li>
                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(15).pdf" style="text-decoration:none;">Bolt: Towards a Scalable Docker Registry via Hyperconvergence</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(16).pdf" style="text-decoration:none;">Containerized Docker Application Lifecycle with Microsoft Tools and Platform</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(17).pdf" style="text-decoration:none;">An Updated Performance Comparison of
Virtual Machines and Linux Containers</a></li>   
  
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(18).pdf" style="text-decoration:none;">Distributed Systems of Microservices Using Docker and Serfnode</a></li> 

  
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(19).pdf" style="text-decoration:none;">Learning Docker</a></li> 

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(20).pdf" style="text-decoration:none;">Performance Of Enterprise Web Applications In Docker Containers On Vmware Vsphere 6.5</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(21).pdf" style="text-decoration:none;">A comparison between
serverless and Docker container deployments</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(22).pdf" style="text-decoration:none;">SQL Server 2019 Containers on Linux: 
Software Development Use Cases Using Dell EMC Infrastructure</a></li> 
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(23).pdf" style="text-decoration:none;">Docker - The Future of Virtualization</a></li> 
 

   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(24).pdf" style="text-decoration:none;">A Survey on Docker Container and its Use Cases</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(25).pdf" style="text-decoration:none;">My VM is Lighter (and Safer) than your Container</a></li>                              
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(26).pdf" style="text-decoration:none;">Docker ecosystem - Vulnerability Analysis</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(27).pdf" style="text-decoration:none;">Docker: Lightweight Linux Containers for Consistent Development and Deployment</a></li>
   
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(28).pdf" style="text-decoration:none;">Deploying an application using Docker and Kubernetes</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(29).pdf" style="text-decoration:none;">Performance Analysis of Containerized Applications on Local and Remote Storage </a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(30).pdf" style="text-decoration:none;">Understanding and Hardening
Linux Containers</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(31).pdf" style="text-decoration:none;">Docker Networking and
Service Discovery</a></li> 
    <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(32).pdf" style="text-decoration:none;">Real-Time Containers: A Survey</a></li> 

   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(33).pdf" style="text-decoration:none;">Docker and Kubernetes:
Changing the OpenText Documentum deployment model</a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(34).pdf" style="text-decoration:none;">A Study of Security Vulnerabilities on Docker Hub</a></li> 
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(35).pdf" style="text-decoration:none;">Model-Driven Management of Docker Containers</a></li> 

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(36).pdf" style="text-decoration:none;">DockerPedia: a Knowledge Graph of Docker Images</a></li> 
 
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(37).pdf" style="text-decoration:none;">GUIdock: Using Docker Containers with a
Common Graphics User Interface to Address the Reproducibility of Research</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(38).pdf" style="text-decoration:none;">Powering
Microservices with Docker</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(39).pdf" style="text-decoration:none;">The Docker Book</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(40).pdf" style="text-decoration:none;">An Attacker Looks at Docker:
Approaching Multi-Container Applications</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(41).pdf" style="text-decoration:none;">Virtualization Using Docker Containers: For Reproducible Environments and Containerized Applications</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(42).pdf" style="text-decoration:none;">Oracle WebLogic Server on Docker Containers</a></li>
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(43).pdf" style="text-decoration:none;">Application Hosting on the
Cisco Catalyst 9000 Series Switches</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(44).pdf" style="text-decoration:none;">Managing Applications in Docker
Containers</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(45).pdf" style="text-decoration:none;">Docker and the Three
Ways of DevOps</a></li>  
   
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(46).pdf" style="text-decoration:none;">Introduction to
Container Security</a></li> 
                             
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(47).pdf" style="text-decoration:none;">Introduction to
Container Security: Understanding the isolation properties of Docker</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(48).pdf" style="text-decoration:none;">Modern Application
Architecture for the Enterprise: Delivering agility, portability and control with Docker Containers as a Service (CaaS)</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(49).pdf" style="text-decoration:none;">Understanding the Security Risks of Docker Hub</a></li>
                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(50).pdf" style="text-decoration:none;">Docker - Beginner Biologist 1</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(51).pdf" style="text-decoration:none;">docker CLI and Dockerfile Cheat Sheet</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(52).pdf" style="text-decoration:none;">Value-Based Allocation of Docker Containers</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(53).pdf" style="text-decoration:none;">Introduction to Docker</a></li>
 
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(54).pdf" style="text-decoration:none;">The next step in
server virtualization: How containers are changing the cloud and application landscape </a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(55).pdf" style="text-decoration:none;">An Introduction to Rocker: Docker
Containers for R</a></li>
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(56).pdf" style="text-decoration:none;">Running Docker* Containers on Intel® Xeon Phi™ Processors </a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(57).pdf" style="text-decoration:none;">Efficient Service Handoff Across Edge Servers via Docker Container Migration</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(58).pdf" style="text-decoration:none;">Fast Docker container deployment
in Fog computing infrastructures</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(59).pdf" style="text-decoration:none;">CIS Docker Community Edition Benchmark</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(60).pdf" style="text-decoration:none;">When Tcl meets Docker</a></li>



</ul>






