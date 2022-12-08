## Advanced Cloud DevOps project 3:
# Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

## CI/CD Pipeline Diagram
![pipeline diagrams.](udapeople-pipeline.png)
___
### Project specifications

- A text file named `urls.txt` including:
  | Specifications | Proof | Meets specifications |
  |---|---|---|
  | Public Url to GitHub repository (not private) | [URL01](https://github.com/fadyio/Advanced-Cloud-DevOps-project-3) | ✓ |
  | Public URL for your S3 Bucket (aka, your green candidate front-end) | [URL02]() |  |
  | Public URL for your CloudFront distribution (aka, your blue production front-end) | [URL03]() |  |
  | Public URLs to deployed application back-end in EC2 | [URL04]() |  |
  | Public URL to your Prometheus Server | [URL05]() |  |

- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions.
  | Specifications | Proof | Meets specification |
  |---|---|---|
  | Job failed because of compile errors. | [SCREENSHOT01](Screenshots/SCREENSHOT01.png) | ✓ |
  | Job failed because of unit tests. | [SCREENSHOT02](Screenshots/SCREENSHOT02.png) | ✓ |
  | Job that failed because of vulnerable packages. | [SCREENSHOT03](Screenshot/SCREENSHOT03.png) | ✓ |
  | An alert from one of your failed builds. | [SCREENSHOT04](Screenshots/SCREENSHOT04.png) |  |
  | Appropriate job failure for infrastructure creation. | [SCREENSHOT05](Screenshots/SCREENSHOT05.png) |  |
  | Appropriate job failure for the smoke test job. | [SCREENSHOT06](Screenshots/SCREENSHOT06.png) |  |
  | Successful rollback after a failed smoke test. | [SCREENSHOT07](Screenshots/SCREENSHOT07.png) |  |
  | Successful promotion job. | [SCREENSHOT08](Screenshots/SCREENSHOT08.png) |  |
  | Successful cleanup job. | [SCREENSHOT09](Screenshots/SCREENSHOT09.png) |  |
  | Only deploy on pushed to `master` branch. | [SCREENSHOT10](Screenshots/SCREENSHOT10.png) |  |
  | Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage.   | [node free memory](Screenshots/SCREENSHOT11_memory.png), [node CPU usage](Screenshots/SCREENSHOT11_cpu.png), [node disk usage](Screenshots/SCREENSHOT11_disk.png).</sup> |  |
  | Provide a screenshot of an alert that was sent by Prometheus. | [SCREENSHOT12](Screenshots/SCREENSHOT12.png) |  |

- Your presentation should be in PDF format and named [presentation.pdf](presentation.pdf). ✓
___
### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
