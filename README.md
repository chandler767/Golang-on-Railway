# How to deploy a Golang app on [Railway](https://railway.app)
This is a simple tutorial showing how to host a basic Golang web app using Railway. Follow this tutorial to learn how to:

- Create a new project in Railway.
- Deploy a golang 'hello world' web app from GitHub to Railway.
- Configure variables for your app.
- Generate a domain for your app.
- Next steps with Railway.

<img src="https://github.com/chandler767/Golang-on-Railway/blob/main/tutorial-images/i6.PNG?raw=true" max-width="375"/>

## What is Railway?
[Railway.app](https://railway.app) is a Platform as a Service (PaaS), presenting a comprehensive environment for constructing and deploying applications.

With Railway App, the heavy lifting is taken care of, requiring only your code input. This cutting-edge technology breaks free from project constraints as its cloud backend accommodates both modest and extensive operations. Recognizing the unique demands of each project, Railway equips you with technologies that extend your application's capabilities through customizable extensions.

## Why use Railway to deploy a Golang App?

* Simplified Deployment Process: Railway App streamlines the deployment process for your Golang application. With Railway App, you only need to provide your code, and the platform takes care of the intricate deployment steps, such as setting up servers, managing dependencies, and configuring environments. This means you can focus more on coding and less on deployment complexities.
* Versatile Technology: Railway App's innovative technology is versatile and adaptable to a wide range of project types. Whether you're working on a small personal project or a large-scale business application, Railway App's cloud backend is equipped to handle the demands of both scenarios, ensuring your application runs smoothly regardless of its scale.
* Seamless Transition from Existing Repositories: One of Railway App's strengths is its ability to seamlessly integrate with your existing repositories. You can continue working on projects that are already in progress without needing to make significant changes to your development workflow. This convenience can save time and effort during the transition to the new platform.
* Reduced Maintenance Overhead: Railway App's managed environment reduces the burden of maintenance and operational tasks. You can rely on the platform to handle updates, scaling, and security measures, freeing you from routine maintenance duties and allowing you to focus on enhancing your application.

## Deploying Go to Railway

1. Fork this repo to your GitHub account. You'll link your cloned repo to your Railway account. 
2. Go to [https://railway.app](https://railway.app) and click "Start a New Project".
3. Click "Deploy from a GitHub repo".
4. (If needed) Login with GitHub and grant access to view your repos. Click "Deploy from a GitHub repo" again after signing in.
<img src="https://github.com/chandler767/Golang-on-Railway/blob/main/tutorial-images/i1.PNG?raw=true" max-width="375"/>
5. Select the repo you just forked. "Golang-on-Railway"
<img src="https://github.com/chandler767/Golang-on-Railway/blob/main/tutorial-images/i2.PNG?raw=true" max-width="375"/>
6. Click "Add variables".
7. Add a variable with the VARIABLE_NAME value set to "NAME". Set VALUE of the "NAME" variable to be "WORLD" or set it to your name. This will later be used to display your name when you make a request to the application. See main.go for more info.
<img src="https://github.com/chandler767/Golang-on-Railway/blob/main/tutorial-images/i3.PNG?raw=true" max-width="375"/>
8. Go to the "Settings" tab. Scroll down to "Domains" and click "Generate Domain". This is also where you can configure a custom domain later.
<img src="https://github.com/chandler767/Golang-on-Railway/blob/main/tutorial-images/i4.PNG?raw=true" max-width="375"/>
9. Click on the generated domain. You should see your Go app running.
<img src="https://github.com/chandler767/Golang-on-Railway/blob/main/tutorial-images/i5.PNG?raw=true" max-width="375"/>


