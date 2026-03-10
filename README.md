# devops-capstone-project

This capstone project focuses on building and delivering a fully functional Customer Accounts microservice while applying modern DevOps and Agile practices. Throughout the course, the project is developed incrementally using multiple sprints, integrating planning, development, testing, security, and deployment automation.

The project begins with Agile planning, where a GitHub repository and Kanban board are created to manage the workflow. User stories are written and organized into a product backlog, followed by sprint planning with estimated story points and sprint backlogs.

During the development phase, the microservice is implemented using Python Flask and Test-Driven Development (TDD). Tests are written first for core RESTful operations such as create, read, update, delete, and list, ensuring the service meets a minimum of 95% test coverage. Development work is managed through feature branches, pull requests, and Kanban board updates.

The project then incorporates Continuous Integration (CI) using GitHub Actions. Automated workflows perform linting with Flake8, run tests, and verify code coverage. Security best practices are added using tools such as Flask-Talisman for security headers and Flask-CORS for cross-origin resource policies.

Next, the application is containerized with Docker and deployed to a Kubernetes/OpenShift cluster. A PostgreSQL database service is configured, and deployment is managed through Kubernetes YAML manifests.

Finally, the project introduces Continuous Delivery (CD) using a Tekton pipeline, which automates linting, testing, container image building, and deployment to Kubernetes whenever changes are made.

By the end of the capstone, the project demonstrates the complete lifecycle of a microservice using Agile development, TDD, CI/CD pipelines, containerization, and cloud-native deployment.
