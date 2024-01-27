# prod-ready-template-server
An basic CRUD application with observability, CI/CD, etc


## Todo List

#### Infrastructure
- [ ] Configure Terraform for AWS lightsail
- [ ] Configure k3s on node
  - [ ] Ingress setup
  - [ ] limit image storage
- [ ] Networking/firewall all fixed
- [ ] Deploy sample HTTP application
- [ ] default metrics/observability configured - limit log storage


#### Application
- [ ] Setup simple REST Webserver code
- [ ] Setup local artifact build/containerization
- [ ] Setup Github Actions using self-hosted server
- [ ] Configure CI/CD to build docker image
- [ ] Configure CI/CD to 