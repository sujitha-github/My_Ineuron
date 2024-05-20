### 15 basic docker commands with explanations and screenshot.

<!-- docker version  -->
<details><summary><b>  1. docker -v </b></summary>  
  
```
    - This command is used to know the version of the docker
```  
![docker_version](https://user-images.githubusercontent.com/114586341/194752237-431906c4-e100-4b26-ab59-e433cd8388d0.png)
</details>

<!-- docker container  -->
<details><summary><b>  2. docker ps </b></summary>  
  
```
    - This command is used to list down all docker container(s)
```  
![docker_ps](https://user-images.githubusercontent.com/114586341/194752244-49a49be2-bf4e-4e8f-b428-58e164d32a0d.png)
</details>

<!-- docker images  -->
<details><summary><b>  3. docker images </b></summary>  
  
```
    - This command is used to list down all docker images
```  
![docker_images](https://user-images.githubusercontent.com/114586341/194752241-02087f5a-87fc-496b-b7d6-7fea109093e8.png)
</details>

<!-- docker build  -->
<details><summary><b>  4. docker build </b></summary>  
  
```
    - Format : docker build -t <image_name:tag> .
    - This command is used to build the docker image with tag.
```  
![docker_build](https://user-images.githubusercontent.com/114586341/194752238-be124f05-ed37-488a-a951-fc212159c8e8.png)
</details>

<!-- docker run  -->
<details><summary><b>  5. docker run </b></summary>  
  
```
    - Format : docker run -d -p <hostport:containerport> <image_name:tag>
    - This command is used to run the docker image  as container
```  
![docker_run](https://user-images.githubusercontent.com/114586341/194752233-314635c7-e85c-4a07-ba38-463eb4dfd51e.png)
</details>

<!-- docker pull  -->
<details><summary><b>  6. docker pull </b></summary>  
  
```
    - Format : docker pull <image_name>
    - This command is used to pull docker image from docker hub
```  
![docker_pull](https://user-images.githubusercontent.com/114586341/194752245-2cc80cf8-f5e6-4187-8ddb-0551847830ec.png)
</details>

<!-- docker push  -->
<details><summary><b>  7. docker push </b></summary>  
  
```
    - Format : docker push <image_name:tag>
    - This command is used to push the local docker image to docker hub
```  
![docker_push](https://user-images.githubusercontent.com/114586341/194752246-9ccfcb5f-9dd5-494f-ba5d-ae5e27249c6f.png)
</details>


<!-- docker port  -->
<details><summary><b>  8. docker port </b></summary>  
  
```
    - Format : docker port <container_name>
    - This command is used to list the ports linked with the container
```  
![docker_port](https://user-images.githubusercontent.com/114586341/194752243-48827efe-c410-44d4-848f-6f867887e094.png)
</details>

<!-- docker rmi  -->
<details><summary><b>  9. docker rmi </b></summary>  
  
```
    - Format : docker port <image_name>
    - This command is used to remove the docker image
```  
![docker_rmi](https://user-images.githubusercontent.com/114586341/194752232-e78ea3f1-0d24-4bb1-a059-5d25e6e224bf.png)
</details>


<!-- docker rename  -->
<details><summary><b>  10. docker rename </b></summary>  
  
```
    - Format : docker port <oldname> <newname>
    - This command is used to rename the container name.
```  
![docker_rename](https://user-images.githubusercontent.com/114586341/194752230-b18ca689-8b5b-4d48-a25d-ba02224bca6f.png)
</details>

<!-- docker start  -->
<details><summary><b>  11. docker start </b></summary>  
  
```
    - Format : docker start <container_name>
    - This command is used to start the container.
```  
![docker_start](https://user-images.githubusercontent.com/114586341/194752234-5c3a78fb-a4e3-4a7d-b459-ffa7857ef1a5.png)
</details>

<!-- docker stop  -->
<details><summary><b>  12. docker stop </b></summary>  
  
```
    - Format : docker stop <container_name>
    - This command is used to start the container.
```  
![docker_stop](https://user-images.githubusercontent.com/114586341/194752235-193b5e9d-1af6-442d-bb8b-0984b4ad4807.png)
</details>

<!-- docker commit  -->
<details><summary><b>  13. docker stop </b></summary>  
  
```
    - Format : docker commit <commands> <container_ID> <image_name>
    - This command is used to create a new docker image with chages made in container.
```  
![docker_commit](https://user-images.githubusercontent.com/114586341/194752239-7a55851e-15e6-459a-a893-2881bc38df68.png)
</details>

<!-- docker inspect  -->
<details><summary><b>  14. docker stop </b></summary>  
  
```
    - Format : docker inspect <commands> <container_ID>
    - This command is used to inspect the values passed to docker container via dockerfile.
```  
![docker_inspect](https://user-images.githubusercontent.com/114586341/194752242-4ea076f1-9c60-45fd-9c2d-82f10bc618b9.png)
</details>

<!-- docker history  -->
<details><summary><b>  15. docker history </b></summary>  
  
```
    - Format : docker history <commands> <image_id>
    - This command is used to inspect the history of the image.
```  
![docker_history](https://user-images.githubusercontent.com/114586341/194752240-b8833dbe-9431-4744-b7d3-ff7e6d4b7661.png)
</details>