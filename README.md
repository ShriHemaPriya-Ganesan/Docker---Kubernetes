🚀 **My Experience with Docker and Kubernetes**

Guestbook Project - A simple web application using Docker and Kubernetes as part of the IBM Skills Developer platform. This hands-on project helped me understand containerization and orchestration concepts.

:star: **Key Accomplishments**

•	Created **Docker images** for the application to package it into containers.

•	Using Kubernetes, deployed and managed these containers with **_kubectl_** commands.

•	Implemented Single web page where users can input text and submit it. 

•	Set up Kubernetes **Deployments** and Pods to run the application effectively.


:chart_with_upwards_trend: **Advanced Features**

•	Applied dynamic **Horizontal Pod Scaling** to ensure the application could handle varying workloads efficiently.

•	Practiced updating the application seamlessly and reverting changes when necessary, using **Rolling Updates and Rollbacks**.


📸 **Screenshots of my implementation in the IBM Skills Developer IDE**

1. Created a Docker image for a Guestbook application written in Go. It employs a multi-stage build process to optimize the final image size and improve security. Docker build command:  _- docker build . -t       us.icr.io/$MY_NAMESPACE/guestbook:v1_.
   ![image](https://github.com/user-attachments/assets/27036b6d-7cee-4743-8aec-516531ed4e16)

2. Pushed the Docker image into the IBM cloud container registry using _docker push us.icr.io/$MY_NAMESPACE/guestbook:v1_ and verified.
   ![image](https://github.com/user-attachments/assets/8c7b070d-5ed3-4964-b1e5-e248bbebd499)

3. Successfully deployed the application.
   ![image](https://github.com/user-attachments/assets/c4f88a2f-29fd-491d-b84e-0171b276398e)

4. Implemented Horizontal Pod Autoscaling to automatically adjust the number of application instances based on demand.
   ![image](https://github.com/user-attachments/assets/f3eef067-f5b6-41e0-9f50-9760faf2a781)

5. Observed the increase in the number of replicas which shows that the application has been autoscaled.
   ![image](https://github.com/user-attachments/assets/5376a1f4-686b-4720-92c3-11d2aa7aabff)

6. Prepared a second revision of the application by updating the Dockerfile and initiated a rollout to deploy the changes.
   ![image](https://github.com/user-attachments/assets/da381f87-5d7e-44e0-82d5-9f85a1ff73bf)
 
