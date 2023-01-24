# sagemaker-hosting-lab

# Lab access steps:

If you are using Event Engine follow all steps below. If you are using your own account start at [SageMaker Studio access](README.md#amazon-sagemaker-studio-access).

**In this lab we will get access to an EventEngine AWS Account that we will use in the following labs. Once we have access to the AWS Account we will access SageMaker Studio and download the necessary content we will be making use of.**

* Access EventEngine
* Access Amazon SageMaker Studio
* Download content from GitHub repository needed for the lab

# Event Engine AWS Account access

Go to: [Event Engine](https://dashboard.eventengine.run/login). You will be redirected to the page below.
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/event-engine-main.png)

Enter the event hash you have received from your instructor.
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/event-engine-hash.png)

Click on Email One-Time Password (OTP).
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/sign-in-with.png)

You are redirected to the following page:
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/enter-otp.png)

Enter your email address and click on Send passcode.
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/enter-email.png)

You are redirected to the following page:

![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/enter-otp-1.png)

Check your mailbox, copy-paste the one-time password and click on Sign in.

![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/otp-sent.png)

You are redirected to the Team Dashboard. Click on AWS Console.

![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/team-dashboard.png)

On the next screen, click on Open AWS Console.

![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/aws-console.png)

You are then redirected to the AWS Console.

# Amazon SageMaker Studio access

Amazon SageMaker Studio is a web-based, integrated development environment (IDE) for machine learning that lets you build, train, debug, deploy, and monitor your machine learning models. Studio provides all the tools you need to take your models from experimentation to production while boosting your productivity.

If the AWS Account has been provisioned by your AWS Instructor, follow the next steps to access the SageMaker Studio environment:

1. Open AWS console and switch to AWS region communicated by your instructor.
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/aws-console.png)

2. Under services search for Amazon SageMaker.
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/services-sagemaker.png)

3. Under Geting Started, click on **Studio**.
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/getting-started.png)

4. A SageMaker Studio environment should already be provisioned. Click on Open Studio (on the right side of the preprovisioned `sagemakeruser` username).
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/sagemaker-studio.pngg)

5. You will be redirected to a new web tab that looks like this:
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/sm-landing-page.png)

Great!! You have successfully launched a SageMaker Studio Notebook.

# Download content from GitHub repository needed for the labs

1. On the landing page, click on the System Terminal 
![](https://raw.githubusercontent.com/marckarp/sagemaker-hosting-lab/main/static/launch-terminal.png)

2. In the terminal, type the following commands:
```
git clone https://github.com/marckarp/sagemaker-hosting-lab.git
```
![](static/intro/clone-code.png)

3. After completion of step 2 you will have the **sagemaker-hosting-lab** folder created in left panel of the studio:


We will be making use of the Jupyter notebooks located in these folders in later labs.


Great!! You have successfully uploaded the content of the SageMaker Workshop and are all set!
