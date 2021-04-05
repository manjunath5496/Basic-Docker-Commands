# Basic Docker Commands

<table style="width: 864px;">
<tbody>
<tr>
<td style="width: 516px;">
<p>docker --version</p>
</td>
<td style="width: 332px;">
<p>get the installed docker version</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker pull hello-world</p>
</td>
<td style="width: 332px;">
<p>download the image "<strong>hello-world</strong>" from the docker repository (<strong>hub.docker.com</strong>)</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker images</p>
</td>
<td style="width: 332px;">
<p>list all the images that are locally stored with the docker engine</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker run hello-world</p>
</td>
<td style="width: 332px;">
<p>create a container from the image "<strong>hello-world</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p><strong>docker container ls -a</strong></p>
</td>
<td style="width: 332px;">
<p>list all containers</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p><strong>docker container ls -a -s</strong></p>
</td>
<td style="width: 332px;">
<p>list the size for all containers</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker rmi 515d5e66f68a</p>
</td>
<td style="width: 332px;">
<p>remove the docker image "<strong>hello-seattle</strong>" with image id "<strong>515d5e66f68a</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker rm d9bf06498bb2</p>
<p>&nbsp;</p>
</td>
<td style="width: 332px;">
<p>remove the docker container with container id "<strong>d9bf06498bb2</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker history hello-world</p>
</td>
<td style="width: 332px;">
<p>display the history of the image "<strong>hello-world</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker info</p>
</td>
<td style="width: 332px;">
<p>get detailed information about docker installed on the system including the kernel version, number of containers and images, etc.</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker volume create</p>
</td>
<td style="width: 332px;">
<p>create a volume which docker container will use to store data</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker volume ls</p>
</td>
<td style="width: 332px;">
<p>list all the volumes known to Docker</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker logs c70201336fd8</p>
</td>
<td style="width: 332px;">
<p>display the logs of the docker container with contained id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker search hadoop</p>
</td>
<td style="width: 332px;">
<p>search for &nbsp;docker image "<strong>hadoop</strong>" on dockerhub</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker network ls</p>
</td>
<td style="width: 332px;">
<p>list all docker networks</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker login</p>
</td>
<td style="width: 332px;">
<p>login into docker repository (<strong>hub.docker.com</strong>)</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker logout</p>
</td>
<td style="width: 332px;">
<p>logout from docker repository (<strong>hub.docker.com</strong>)</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker start c70201336fd8</p>
</td>
<td style="width: 332px;">
<p>start the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker stop c70201336fd8</p>
</td>
<td style="width: 332px;">
<p>stop the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker restart c70201336fd8</p>
<p>&nbsp;</p>
</td>
<td style="width: 332px;">
<p>restart the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker inspect c70201336fd8</p>
</td>
<td style="width: 332px;">
<p>get&nbsp; detailed information&nbsp; about the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker stats c70201336fd8</p>
</td>
<td style="width: 332px;">
<p>get the statistics of the docker container with container id "<strong>c70201336fd8</strong>"</p>
</td>
</tr>
<tr>
<td style="width: 516px;">
<p>docker image ls</p>
</td>
<td style="width: 332px;">
<p>List all images that are locally stored with the docker engine.</p>
</td>
</tr>
</tbody>
</table>
