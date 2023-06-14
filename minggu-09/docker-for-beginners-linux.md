# Docker for Beginners - Linux

Laporan beserta gambar dibawah ini adalah hasil praktikum melalui [Docker for Beginners - Linux](https://training.play-with-docker.com/beginner-linux/), sehingga untuk materi dan penjelasan lebih detailnya dapat diakses melalui web tersebut.

### Task

- Task 0: Prerequisites 
- Task 1: Run some simple Docker containers 
- Task 2: Package and run a custom app using Docker 
- Task 3: Modify a Running Website

## Task 0: Prerequisites

You will need all of the following to complete this lab: 
- A clone of the lab’s GitHub repo. 
- A DockerID.

### Clone the Lab’s GitHub Repo

Use the following command to clone the lab’s repo from GitHub (you can click the command or manually type it). This will make a copy of the lab’s repo in a new sub-directory called ```linux_tweet_app```.
<div><img src="gambar/1.jpg"></div><br>

### Make sure you have a DockerID

If you do not have a DockerID (a free login used to access Docker Hub), please visit [Docker Hub](https://hub.docker.com/) and register for one. You will need this for later steps.

## Task 1: Run some simple Docker containers 

There are different ways to use containers. These include: 
1. To run a single task: This could be a shell script or a custom app. 
2. Interactively: This connects you to the container similar to the way you SSH into a remote server. 
3. In the background: For long-running services like websites and databases. 

In this section you’ll try each of those options and see how Docker manages the workload.

### Run a single task in an Alpine Linux container

<div><img src="gambar/2.jpg"></div>
<div><img src="gambar/3.jpg"></div>

### Run an interactive Ubuntu container
- Run the following commands in the container.
<div><img src="gambar/4.jpg"></div>
<div><img src="gambar/5.jpg"></div>
<div><img src="gambar/6.jpg"></div>

### Run a background MySQL container

<div><img src="gambar/r1.jpg"></div>
<div><img src="gambar/r2"></div>
<div><img src="gambar/r3"></div>
<div><img src="gambar/r4.jpg"></div>
<div><img src="gambar/r5.jpg"></div>
<div><img src="gambar/r6.jpg"></div>
<div><img src="gambar/r7.jpg"></div>

## Task 2: Package and run a custom app using Docker 

In this step you’ll learn how to package your own apps as Docker images using a [Dockerfile](https://docs.docker.com/engine/reference/builder/). 

The Dockerfile syntax is straightforward. In this task, we’re going to create a simple NGINX website from a Dockerfile.

### Build a simple website image

<div><img src="gambar/t1.jpg"></div>
<div><img src="gambar/t2"></div>
<div><img src="gambar/t3.jpg"></div>
<div><img src="gambar/t4.jpg"></div>
<div><img src="gambar/t4a.jpg"></div>
<div><img src="gambar/t8.jpg"></div>

## Task 3: Modify a Running Website

### Start our web app with a bind mount

<div><img src="gambar/index.jpg"></div>
<div><img src="gambar/t5.jpg"></div>
<div><img src="gambar/t6.jpg"></div>

### Modify the running website

<div><img src="gambar/screenshot-22.jpg"></div>
<div><img src="gambar/screenshot-23.jpg"></div>
<div><img src="gambar/screenshot-24.jpg"></div>
<div><img src="gambar/screenshot-25.jpg"></div>
<div><img src="gambar/screenshot-26.jpg"></div>
<div><img src="gambar/screenshot-27.jpg"></div>

### Update the image

<div><img src="gambar/newversion1.jpg"></div>
<div><img src="gambar/newversion2.jpg"></div>

### Test the new version

<div><img src="gambar/screenshot-30.jpg"></div>
<div><img src="gambar/screenshot-31.jpg"></div>
<div><img src="gambar/screenshot-32.jpg"></div>
<div><img src="gambar/screenshot-33.jpg"></div>

### Push your images to Docker Hub

Hasil pada dockerHub : 
<div><img src="gambar/hasil.jpg"></div>
