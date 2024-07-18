VCC Assignment

Below is the Image of the Assignment:
 ![image](https://github.com/user-attachments/assets/2f35ce70-ae31-46aa-91bb-d51a9ad95c1d)


Below are the steps followed for Assignment completion:

•	Download and Install Docker desktop (Using Windows machine)
•	Create a dummy Flask Application. 
![image](https://github.com/user-attachments/assets/b75adb4b-7979-470d-8506-b4765b8ca9cf)

•	Once the Application is  created create a requirement.txt file containing all the Python libraries we need to Install. In our case, we only required Flask.
![image](https://github.com/user-attachments/assets/ed7e19a4-0719-4160-9208-7dd2e597731b)


 

•	Next we have to create a Dockerfile - A Dockerfile is a simple text file that contains a list of commands that the Docker client calls while creating an image. It's a simple way to automate the image creation process. The best part is that the commands you write in a Dockerfile are almost identical to their equivalent Linux commands.  
![image](https://github.com/user-attachments/assets/0fa2553d-2e2c-4c17-900a-4c92a97df08c)

Here I am using Python version 3.11 and the name of my Flask application file is dummy_app.py. We have mentioned this. Also, in my Python Flask APP, the application is running on port 5000. So, I have exposed it on dockerfile.

•	Next, we have to build a docker image using docker build command as per screenshot:  
![image](https://github.com/user-attachments/assets/70d2ec0d-9c74-44fd-bb84-51cc805cbfd6)

•	Once the Docker Image is built , test the image by running it using docker run command:  
![image](https://github.com/user-attachments/assets/42a07b4b-d9d4-4865-94a5-891ff38dcd02)

•	Now we clicked on the url mentioned in above screenshot result:



Here we are able to view the Flask App on the URL. 
![image](https://github.com/user-attachments/assets/2f6bd84f-74d5-4731-bfe8-44b334a58b9c)

Once we visited the URL , there is an entry created on the terminal for our App access

![image](https://github.com/user-attachments/assets/0c700744-7cca-4165-8ea7-98495f089fc4)
 

•	Now for publishing the docker image on dockerhub we use docker push command. Below image shows the published docker image on DockerHub.
![image](https://github.com/user-attachments/assets/0bac5113-ba97-43f7-9233-53b9b3f76640)

 ![image](https://github.com/user-attachments/assets/ab1b0ccd-b46e-4686-b00d-a17842f2782e)

 

•	We can pull this image from dockerHub using the Docker Pull command: 
![image](https://github.com/user-attachments/assets/98a1daf7-d8bc-4f15-9953-24e4b0f72b57)




