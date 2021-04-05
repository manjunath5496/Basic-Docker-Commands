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
