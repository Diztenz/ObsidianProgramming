* What is docker
	* What a container is and what problems it solves.
		* A way to package application with all the necessary dependencies and configurations.
		* Package is portable easily shared and moved around
		* Makes development and deployment process more efficient.
				* Where do containers live?
				* in containier repository
				* private repositories.
				* Docker hub hub.docker.com
			* before container.
				* you would have to intall binary's of all services and run them on the local environment.
				* Multiple steps of installations.  More chances of something going wrong. This can be pretty tedius depending on how large your process is.

			* with containers
				* own isolated environment
				* packaged with all needed configuration
				* download step is one docker command.
				* regardless of system you are on the process for starting the command will be the same.
				* run same app with 2 different versions without having conflict.
				* Developers and Operations work together to package the application in a container.
				* No environmental configuration needed on server - except Docker Runtime.
			* What is a Container Technically?
				* Layers of images 
				* Mostly Linux Base images, because small in size.
				* application image.
				* on top of that all that you will have configuration data.
					* when downloading on command line you can see all the different layers dowloading that go onto the docker stacked inside the container.
					*  
	* Container Repository
	* Develop Application
	* Deploy application
	
* Docker vs. Virtual Machine
* Docker Installation
* Main Commands
* Debugging a Container
* Developing with Containers
* Docker Compose - Running Multiple Services
* Dockerfile - Building own Docker Image
* Private Docker Repository (AWS)
* Deploying the containerized App
* Volumes - Persisting Data
* Volumes Demo


Demo Project


For commit purpose only
