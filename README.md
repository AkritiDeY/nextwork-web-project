::::::::::: 🚀 7-Day DevOps Challenge – Full CI/CD Journey on AWS :::::::::::

Welcome to my 7-Day DevOps Challenge project, built with guidance from NextWork. This challenge is designed to simulate a real-world DevOps workflow using AWS services, focusing on building, automating, and deploying a web application end-to-end.

✅ Note: Day 6 was optional, and hence skipped.

📅 Challenge Summary
Day	Task Overview
1	Set up a web server using EC2 and Apache
2	Package the app for deployment
3	Set up IAM roles and CodeDeploy
4	Launch infrastructure using CloudFormation
5	Connect GitHub with AWS CodePipeline
6	Optional – Troubleshooting Pipeline
7	Build a full CI/CD pipeline using CodePipeline, CodeBuild & CodeDeploy

🌐 Day-by-Day Breakdown
📍 Day 1: Launching a Web Server on EC2
      Provisioned an EC2 instance on AWS.
      Installed and configured Apache to serve a basic web app.
      Deployed the initial version of the web app manually.
✅ Outcome: Web server successfully hosted and accessible via public IP.

📍 Day 2: Preparing the App for Deployment
      Packaged the web application into a .zip file.
      Created an appspec.yml to define deployment hooks.
      Added a scripts folder with before_install.sh and after_install.sh scripts.
✅ Outcome: Application ready for CodeDeploy with all required assets and instructions.

📍 Day 3: Set Up IAM Roles and CodeDeploy
      Created IAM roles for EC2 and CodeDeploy with least-privilege permissions.
      Installed the CodeDeploy agent on the EC2 instance.
      Created a CodeDeploy application and deployment group.
✅ Outcome: EC2 instance now supports automated deployments using CodeDeploy.

📍 Day 4: Launching Infrastructure via CloudFormation
      Created a CloudFormation template to automate provisioning:
      EC2 instance
      Security Groups
      IAM roles
      Parameterized key values (e.g., instance type, key pair).
✅ Outcome: Reproducible infrastructure deployment using infrastructure-as-code.

📍 Day 5: Automate Code Delivery via GitHub and CodePipeline
      Connected GitHub repository with CodePipeline.
      Set up pipeline stages: Source, Build, and Deploy.
      Used CodeBuild to compile and package the app.
✅ Outcome: Changes pushed to GitHub now trigger an automated pipeline.

📍 Day 6: (Optional – Skipped)
      Focused on troubleshooting and enhancements.
      This day was optional and was skipped.
      
📍 Day 7: Full CI/CD Pipeline Test 🚀
      Final test of the pipeline:
      Made code changes in GitHub
      Verified that CodePipeline auto-triggered
      Checked build and deploy success in AWS Console
      Confirmed updated application live on EC2 public DNS
      ✅ Outcome: A fully automated, tested CI/CD pipeline is live and production-ready!

🛠️ Tools & Services Used
    Amazon EC2 – Hosting the web application
    Amazon S3 – Storing build artifacts
    AWS IAM – Managing secure access using roles
    AWS CodeDeploy – Automating deployments to EC2
    AWS CodeBuild – Building and packaging the code
    AWS CodePipeline – Orchestrating the CI/CD workflow
    AWS CloudFormation – Provisioning infrastructure as code
    GitHub – Storing source code and triggering pipeline events
    Bash Scripts – Automating pre/post install steps

📌 Key Concepts Learned
    CI/CD fundamentals using AWS-native tools
    Infrastructure as Code (IaC) using CloudFormation
    GitOps-style deployments from GitHub
    Artifact packaging and delivery
    Role-based access control using IAM
    Debugging and reconnecting pipeline components
    End-to-end automation and observability in DevOps

⏱️ Time Taken
    This entire challenge took approximately 14–15 hours across 6 days of active learning.
    The most challenging parts included:
    Reconnecting services after EC2 public IP changed
    Configuring IAM roles with precise permissions
    Debugging deployment lifecycle errors
    The most rewarding experience was watching GitHub commits go live on a running web app without a single manual deployment step. 🛠️➡️🌐

🧪 Final Test – Live Deployment
    Code change pushed to GitHub ✔️
    Pipeline triggered ✔️
    Build succeeded ✔️
    Deploy succeeded ✔️
    Web app live with new changes on EC2 ✔️

✅ CI/CD Pipeline is confirmed working end-to-end!

📄 Project Outcome
    By the end of this 7-day challenge:
    I built and tested a complete CI/CD solution using AWS tools.
    Learned real-world deployment strategies and best practices.
    Improved confidence in handling DevOps-style application delivery.
    Published a fully working pipeline for portfolio visibility.

🙏 Acknowledgement
  Thanks to @NextWork for their incredible hands-on resources and mentorship during this challenge.

🏷️ Hashtags
#AWS #DevOps #7DayChallenge #CICD #CodePipeline #CodeDeploy #CodeBuild #CloudFormation #GitHub #NextWorkChallenge #CloudEngineer

