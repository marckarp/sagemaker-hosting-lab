# sagemaker-hosting-lab

# Event Engine

**In this lab we will get access to an EventEngine AWS Account that we will use in the following labs. Once we have access to the AWS Account we will access SageMaker Studio and download the necessary content we will be making use of.**

* Access EventEngine
* Access Amazon SageMaker Studio
* Download content from GitHub repository needed for the lab

# Event Engine AWS Account access

Go to: [Event Engine](https://dashboard.eventengine.run/login). You will be redirected to the page below.
![](static/intro/event-engine-main.png)

Enter the event hash you have received from your instructor.
![](static/intro/event-engine-hash.png)

Click on Email One-Time Password (OTP).
![](static/intro/sign-in-with.png)

You are redirected to the following page:
![](static/intro/enter-otp.png)

Enter your email address and click on Send passcode.
![](static/intro/enter-email.png)

You are redirected to the following page:

![](static/intro/enter-otp-1.png)

Check your mailbox, copy-paste the one-time password and click on Sign in.

![](static/intro/otp-sent.png)

You are redirected to the Team Dashboard. Click on AWS Console.

![](static/intro/team-dashboard.png)

On the next screen, click on Open AWS Console.

![](static/intro/open-console.png)

You are then redirected to the AWS Console.

# Amazon SageMaker Studio access

Amazon SageMaker Studio is a web-based, integrated development environment (IDE) for machine learning that lets you build, train, debug, deploy, and monitor your machine learning models. Studio provides all the tools you need to take your models from experimentation to production while boosting your productivity.

If the AWS Account has been provisioned by your AWS Instructor, follow the next steps to access the SageMaker Studio environment:

1. Open AWS console and switch to AWS region communicated by your instructor.
![](static/intro/aws-console.png)

2. Under services search for Amazon SageMaker.
![](static/intro/services-sagemaker.png)

3. Under Geting Started, click on **Control Panel**.
![](static/intro/getting-started.png)

4. A SageMaker Studio environment should already be provisioned. Click on Open Studio (on the right side of the preprovisioned sagemakeruser username).
![](static/intro/sagemaker-studio.png)

5. You will be redirected to a new web tab that looks like this:
![](static/intro/sm-landing-page.png)

Great!! You have successfully launched a SageMaker Studio Notebook.

# Download content from GitHub repository needed for the labs

1. On the landing page, click on the System Terminal 
![](static/intro/launch-terminal.png)

2. In the terminal, type the following commands:
```
git clone https://github.com/marckarp/sagemaker-hosting-lab.git
```
![](static/intro/clone-code.png)

3. After completion of step 2 you will have the **sagemaker-hosting** folder created in left panel of the studio:


We will be making use of the Jupyter notebooks located in these folders in later labs.


Great!! You have successfully uploaded the content of the SageMaker Workshop and are all set!
