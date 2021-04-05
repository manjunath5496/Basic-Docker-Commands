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
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(11).pdf" style="text-decoration:none;">A Concurrency-Optimal Binary Search Tree</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(12).pdf" style="text-decoration:none;">Alpenhorn: Bootstrapping Secure Communication without Leaking Metadata</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(13).pdf" style="text-decoration:none;">Amber: Decoupling User Data from Web Applications</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(14).pdf" style="text-decoration:none;">Quboid: A Workstation for Safer Web Interaction</a></li>
                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(15).pdf" style="text-decoration:none;">Argosy: Verifying Layered Storage Systems with
Recovery Refinement</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(16).pdf" style="text-decoration:none;">LRC: Dependency-Aware Cache Management
for Data Analytics Clusters</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(17).pdf" style="text-decoration:none;">Make Least Privilege a Right (Not a Privilege)</a></li>   
  
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(18).pdf" style="text-decoration:none;">Labels and Event Processes
in the Asbestos Operating System</a></li> 

  
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(19).pdf" style="text-decoration:none;">Privacy-Preserving Browser-Side Scripting With BFlow</a></li> 

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(20).pdf" style="text-decoration:none;">The benefits and costs of writing a
POSIX kernel in a high-level language</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(21).pdf" style="text-decoration:none;">The Benefits and Costs of Writing a POSIX Kernel in a High-Level Language</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(22).pdf" style="text-decoration:none;">LLVM: A Compilation Framework for
Lifelong Program Analysis and Transformation</a></li> 
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(23).pdf" style="text-decoration:none;">The Benefits and Costs of Writing a POSIX
Kernel in a High-Level Language [Cody Cutler]</a></li> 
 

   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(24).pdf" style="text-decoration:none;">Separating Web Applications from User Data Storage with BSTORE</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(25).pdf" style="text-decoration:none;">A Methodical Study of Web Crawler</a></li>                              
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(26).pdf" style="text-decoration:none;">Certifying a File System Using
Crash Hoare Logic: Correctness in the Presence of Crashes</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(27).pdf" style="text-decoration:none;">A Differential Approach to
Undefined Behavior Detection</a></li>
   
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(28).pdf" style="text-decoration:none;">Reducing Pause Times with Clustered Collection</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(29).pdf" style="text-decoration:none;">Reducing Pause Times With Clustered Collection [Cody Cutler] </a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(30).pdf" style="text-decoration:none;">Certifying Program Execution with Secure Processors</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(31).pdf" style="text-decoration:none;">Providing a Shared File System in the Hare
POSIX Multikernel</a></li> 
    <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(32).pdf" style="text-decoration:none;">Linux kernel vulnerabilities:
State-of-the-art defenses and open problems</a></li> 

   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(33).pdf" style="text-decoration:none;">Robust and Efficient Data Management for a Distributed Hash Table</a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(34).pdf" style="text-decoration:none;">Choosing Internet Paths with High Bulk Transfer Capacity</a></li> 
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(35).pdf" style="text-decoration:none;">Melody: A Distributed Music-Sharing System</a></li> 

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(36).pdf" style="text-decoration:none;">A Keyword-Set Search System for Peer-to-Peer
Networks</a></li> 
 
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(37).pdf" style="text-decoration:none;">Herodotus: A Peer-to-PeerWeb Archival System</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(38).pdf" style="text-decoration:none;">A case study of server selection</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(39).pdf" style="text-decoration:none;">The Scalable Commutativity Rule:
Designing Scalable Software for Multicore Processors</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(40).pdf" style="text-decoration:none;">Programming language optimizations for modular router configurations</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(41).pdf" style="text-decoration:none;">Fast Bug Finding in Lock-Free Data Structures with
CB-DPOR</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(42).pdf" style="text-decoration:none;">Finding Linearization Violations in Lock-Free
Concurrent Data Structures</a></li>
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(43).pdf" style="text-decoration:none;">The Scalable Commutativity Rule:
Designing Scalable Software for Multicore Processors</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(44).pdf" style="text-decoration:none;">SCTP in Go</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(45).pdf" style="text-decoration:none;">Cloud Based Web Scraping for Big Data Applications</a></li>  
   
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(46).pdf" style="text-decoration:none;">Conclave: secure multi-party computation on big data</a></li> 
                             
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(47).pdf" style="text-decoration:none;">Corey: An Operating System for Many Cores</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(48).pdf" style="text-decoration:none;">CPHash: A Cache-Partitioned Hash Table</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(49).pdf" style="text-decoration:none;">Scaling Address-Space Operations on Linux with
TSX</a></li>
                              
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(50).pdf" style="text-decoration:none;">Why does cryptographic software fail?
A case study and open problems</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(51).pdf" style="text-decoration:none;">In Defense of Wireless Carrier Sense</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(52).pdf" style="text-decoration:none;">Verifying concurrent software using movers in CSPEC</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(53).pdf" style="text-decoration:none;">The Little Manual of
API Design</a></li>
 
<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(54).pdf" style="text-decoration:none;">Design and Applications of a Secure and Decentralized Distributed Hash Table </a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(55).pdf" style="text-decoration:none;">Recovering from intrusions in distributed systems with DARE</a></li>
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(56).pdf" style="text-decoration:none;">Verifying a high-performance crash-safe file system using a tree specification </a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(57).pdf" style="text-decoration:none;">No Silver Bullet — Essence and Accident in Software Engineering</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Basic-Docker-Commands/blob/master/d(58).pdf" style="text-decoration:none;">Proving confidentiality in a file system using DISKSEC</a></li>
    </ul>






