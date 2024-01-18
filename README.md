# CircleCI-Docker Tutorial Repository 🚀

[![CircleCI](https://dl.circleci.com/status-badge/img/circleci/F8dURJPtnQRe7nWNRJJUAy/WPnyukitzk5iL2YD5Ux7vG/tree/main.svg?style=svg&circle-token=97876933f35700a218bd4cd71ebfd00ae572de79)](https://dl.circleci.com/status-badge/redirect/circleci/F8dURJPtnQRe7nWNRJJUAy/WPnyukitzk5iL2YD5Ux7vG/tree/main)

Welcome to this repository where we dive into the world of Continuous Integration/Continuous Deployment (CI/CD) using CircleCI and Docker! 🐳 This repository is a beginner-friendly guide designed for those starting their journey in CI/CD and Docker. It's a great resource for learning, exploring, and contributing!

### About the Application 📝

This repository contains a simple Flask web application. The main functionality of this app is to display a welcoming message "Welcome to my Flask App" on the home page. The application is straightforward, making it an excellent candidate for learning basic CI/CD and containerization concepts.

### Repository Structure 📂

The repository includes the following key files:

- `Dockerfile`: Defines the Docker container for the Flask app.
- `main.py`: The Flask application's main file.
- `test_main.py`: Contains tests for the Flask app.
- `requirements.txt`: Lists the necessary Python packages.

### Getting Started 🌟

To get started with this project, you'll need a basic understanding of Python, Flask, Docker, and CI/CD principles. Here are the steps to follow:

- **Fork and Clone**: Fork this repository and clone it to your local machine.
- **Docker Setup**: Make sure you have Docker installed on your system. If not, download it from the [Docker website](https://www.docker.com/).
- **CircleCI Account**: You'll need a CircleCI account, which you can set up [here](https://circleci.com/).
- **DockerHub Account**: DockerHub is required to store Docker images. [Sign up](https://hub.docker.com/signup) if you haven't already.

### Usage and Contribution 🛠️

Feel free to use this repository as a starting point for your CI/CD and Docker learning journey! Contributions are highly encouraged. If you have enhancements, bug fixes, or improvements, please submit a pull request. Your contributions will help make this a valuable resource for the community!

### Setting Up CI/CD Pipeline 🔄

1. **Environment Variables**: Set your DockerHub username and password as environment variables (`DOCKER_USERNAME` and `DOCKER_PASSWORD`) in your CircleCI project settings.
2. **Customize and Test**: Modify the application as needed and write tests.
3. **Push Your Changes**: Commit and push your changes to trigger the CircleCI pipeline.
4. **Check Pipeline Results**: Monitor the build results in CircleCI and ensure everything passes.

### Activating the CircleCI CI/CD Pipeline 🔄

After setting up your CircleCI CI/CD Pipeline, it's time to get it up and running! Follow these steps to activate your pipeline:

#### Step 1: Log in to CircleCI 🖥️

- **Access CircleCI**: Log in to your CircleCI account using your GitHub credentials. You can do this through your web browser.

#### Step 2: Set Up Your Project in CircleCI 🛠️

- **Find Your Project**: Go to the Projects tab on the left panel in CircleCI.
- **Activate Pipeline**: Click on the Set Up Project button next to your project. This action will activate the CircleCI pipeline for your project.

#### Step 3: Monitor Your Pipeline 📊

- **Dashboard Check**: Head back to the Dashboard tab. Here, you should see a "Success" status, indicating that your pipeline ran smoothly and the image has been pushed to Docker Hub.
- **View Pipeline Details**: Click on the build to see the detailed steps executed by CircleCI during the pipeline run.

#### Step 4: Verify on Docker Hub 🐳

- **Docker Hub Verification**: Finally, visit your Docker Hub repository. You should see the image that was pushed through the CircleCI pipeline.

By following these steps, you can effectively activate and monitor your CircleCI pipeline, ensuring a smooth CI/CD process for your Flask application.

### Learning Resources 📚

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Docker Get Started Guide](https://www.docker.com/get-started)
- [CircleCI Documentation](https://circleci.com/docs/)

### Contributing 🤝

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Support 💬

If you have any questions or need help, don't hesitate to reach out. Let's learn and grow together in this exciting world of CI/CD and Docker!

Happy Coding! 🎉
