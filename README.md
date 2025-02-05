## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Instructions

* [Selling CI/CD](instructions/0-selling-cicd.md)
* [Getting Started](instructions/1-getting-started.md)
* [Deploying Working, Trustworthy Software](instructions/2-deploying-trustworthy-code.md)
* [Configuration Management](instructions/3-configuration-management.md)
* [Turn Errors into Sirens](instructions/4-turn-errors-into-sirens.md)

### Project Submission

For your submission, please submit the following:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01](https://github.com/SammyBloom/cdond-c3-projectstarter.git)
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) - URL [URL02](http://udapeople-956847e.s3-website-us-east-1.amazonaws.com) and screenshot  [URL02_SCREENSHOT](submission\screenshots\URL02.png)
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03](submission\screenshots\URL03_SCREENSHOT.png) and [URL03-1](submission\screenshots\URL03_SCREENSHOT1.png)

  Evidence of Employee Added [Evidence](screenshots\Evidence-of-Adding-Employee.png)
  1. Public URLs to deployed application back-end in EC2 [URL04](submission\screenshots\URL04_SCREENSHOT.png)
  1. Public URL to your Prometheus Server [URL05](submission\screenshots\URL05_SCREENSHOT.png), [PrometheusMonitoringItself](submission\screenshots\Prometheus-monitoring-itself.png)
- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01](submission\screenshots\SCREENSHOT01.png)
  1. Job failed because of unit tests. [SCREENSHOT02](submission\screenshots\SCREENSHOT02.png)
  1. Job that failed because of vulnerable packages. [SCREENSHOT03](submission\screenshots\SCREENSHOT03.png)
  1. An alert from one of your failed builds. [SCREENSHOT04](submission\screenshots\SCREENSHOT04.png)
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05](submission\screenshots\SCREENSHOT05.png)
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06](submission\screenshots\SCREENSHOT06.png)
  1. Successful rollback after a failed smoke test. [SCREENSHOT07](submission\screenshots\SCREENSHOT07.png)  
  1. Successful promotion job. [SCREENSHOT08](submission\screenshots\SCREENSHOT08.png)
  1. Successful cleanup job. [SCREENSHOT09](submission\screenshots\SCREENSHOT09.png) and [SCREENSHOT09-1](submission\screenshots\SCREENSHOT09-1.png)
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10](submission\screenshots\SCREENSHOT10.png)
  1. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11](submission\screenshots\SCREENSHOT11.png), [AvailableDiskSpace](submission\screenshots\Node-Disk-Usage.png) and [CPUusage](submission\screenshots\Node-CPU-Usage.png).
  1. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12](submission\screenshots\SCREENSHOT12.png)

- Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder. 

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements. 

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
