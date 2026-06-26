# devops-playground-no-ai
As a DevOps engineer, I am convinced that AI is a very powerful tool, that we should use. Anyhow I am also convinced, that as humanity we need to keep up and have deep knowledge within the things we craft. Hence I am using this repository as my personal DevOps playground, developed fully without AI to learn and just build

## Repository Structure

The repository structure is following a mono repository approach to keep things as easy as possible for the start.
### .github
The .github folder utilizes GitHub Actions as my CI/CD tool. It stores workflows and dependabot config for a start.

### ansible
Ansible may be used to bootstrap VMs in the Cloud or my local Raspberry PIs. As I want to collect experience with Kubernetes administration on premise, it will very likely be used for the Raspberry PIs mostly.

### argo
I want to use ArgoCD for my Helm deployments. I have not used it so far, so I do not know, if I need a separate folder for it. But in the first draft, I will keep it as a placeholder

### applications
The applications folder holds the source code of any microservice, webapps or more that I may build. I like to code in Golang as well a lot and think a DevOps playground is only interesting when actively developing in it. 

### terraform
The terraform folder, holds all terraform resources that I will use to create resources at specific Cloud Providers or within my cluster.

### tests
The tests folder should be used for tests that are covering more than one application. Application specific tests should be part of the respective appications folder.

