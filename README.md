This is basic deployment of a flask web app.
1. creating Flask web app
2. creating Docker image
3. Containerize Docker image

   ![image](https://github.com/user-attachments/assets/6f1085e7-03ed-40a6-918c-ad0379f9f8fa)

   
Steps to containerize and deploy your project using Docker Hub and Google Cloud:
1. Create a Dockerfile (which you've already done)
Ensure your Dockerfile is in the root of your project directory and defines the Python and Flask environment needed to run your app.
2. Sign in to Docker Hub
You already signed in to Docker Hub via GitHub. Now, you need to log in via the command line.
Find your Docker Hub username: Go to Docker Hub, click on your profile icon, and find your username there.
Password: Since you signed up via GitHub, Docker might not have an immediate password for you. You can reset it by going to "Account Settings" -> "Security" -> "Reset password," and then set one.

Summary of the Workflow
Creating a Flask App:

Purpose: Develop a simple web application using Flask, a lightweight web framework for Python.
Use: This serves as the foundation for your project and demonstrates your ability to create web applications.
Dockerizing the Application:

Purpose: Create a Dockerfile to package your Flask app along with its dependencies into a Docker image.
Use: Dockerization ensures that your application runs consistently across different environments by encapsulating it in a container.
Pushing Docker Image to Docker Hub:

Purpose: Upload the Docker image to Docker Hub, a cloud-based registry for Docker images.
Use: This allows easy access and sharing of your image, making it possible to deploy your application from any location without building the image again.
Deploying to Render:

Purpose: Use Render to host your application by pulling the Docker image from Docker Hub.
Use: This provides a platform to run your application in the cloud, allowing it to be accessible via a URL. Render automates scaling, availability, and other infrastructure concerns.
Setting Up GitHub Actions:

Purpose: Automate the build, test, and deployment processes by defining workflows in your GitHub repository.
Use: GitHub Actions allows you to trigger automated deployments whenever you push code changes to your repository, enhancing your development workflow and ensuring that your latest code is always live.
Overall Benefits
Consistency: Ensures that your application behaves the same way in development, testing, and production environments.
Efficiency: Automates the deployment process, saving time and reducing manual errors.
Scalability: Makes it easier to scale your application as needed without worrying about the underlying infrastructure.
Collaboration: Facilitates team collaboration by allowing multiple developers to contribute to the codebase while maintaining consistent deployment practices.
Learning: Provides hands-on experience with modern development practices, including containerization, cloud deployment, and CI/CD (Continuous Integration/Continuous Deployment).

![image](https://github.com/user-attachments/assets/07aba00a-94bf-4855-9b5e-113d14d5d265)
