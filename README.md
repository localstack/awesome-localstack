<p align="center">
  <img src="https://raw.githubusercontent.com/localstack/localstack/master/docs/localstack-readme-banner.svg" alt="LocalStack - A fully functional local cloud stack">
</p>
<p align="center">  
  <a href="https://localstack.cloud/slack">
  <img src="https://img.shields.io/badge/Slack-@localstack-purple.svg" alt="Slack">
  </a>
<a href="https://twitter.com/localstack">
  <img src="https://img.shields.io/badge/Twitter-@localstack-9cf.svg" alt="Twitter">
</a>
<a href="https://www.linkedin.com/company/localstack-cloud">
  <img src="https://img.shields.io/badge/LinkedIn-@localstack-darkblue.svg" alt="LinkedIn">
</a>
<a href="https://www.youtube.com/@localstack">
  <img src="https://img.shields.io/badge/YouTube-@localstack-red.svg" alt="YouTube">
</a>
<a href="https://discuss.localstack.cloud">
  <img src="https://img.shields.io/badge/Discuss-@localstack-white.svg" alt="Discuss">
</a>
</p>

# Awesome LocalStack [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of [LocalStack](https://localstack.cloud) integrations, tools, frameworks, and platforms.

If you want to contribute to this list, then please read the [contributing guidelines](CONTRIBUTING.md). Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

## User Interface

- [Web Application](https://app.localstack.cloud/): Web application to interact with LocalStack services, manage resources, and use advanced features.
- [Desktop Application](https://docs.localstack.cloud/user-guide/tools/localstack-desktop/): Desktop application to manage the container, view resources, and inspect logs.
- [Docker Desktop Extension](https://hub.docker.com/extensions/localstack/localstack-docker-desktop): Docker Desktop extension to manage the container and view logs.
- [Commandeer](https://getcommandeer.com/): Desktop application to manage LocalStack and test your applications locally with an IDE experience.
- [SQS Admin](https://github.com/PacoVK/sqs-admin): Local Web Application to manage SQS queues.

## Integrations

- [`arclocal`](https://docs.localstack.cloud/user-guide/integrations/architect/): Run Architect Infrastructure as Code framework with LocalStack.
- [`awslocal`](https://docs.localstack.cloud/user-guide/integrations/aws-cli/#localstack-aws-cli-awslocal): Run the AWS Command Line Interface (CLI) with LocalStack.
- [`cdklocal`](https://docs.localstack.cloud/user-guide/integrations/aws-cdk/): Run the AWS Cloud Development Kit Infrastructure as Code framework with LocalStack.
- [`chalice-local`](https://docs.localstack.cloud/user-guide/integrations/chalice/): Run the AWS Chalice serverless micro-framework with LocalStack.
- [`copilotlocal`](https://docs.localstack.cloud/user-guide/integrations/copilot/): Run the Copilot CLI to build AWS containerized applications with LocalStack.
- [`pulumilocal`](https://docs.localstack.cloud/user-guide/integrations/pulumi/#pulumilocal): Run the Pulumi Infrastructure as Code framework with LocalStack.
- [`samlocal`](https://docs.localstack.cloud/user-guide/integrations/aws-sam/): Run the Serverless Application Model Infrastructure as Code framework with LocalStack.
- [`serverless-localstack`](https://docs.localstack.cloud/user-guide/integrations/serverless-framework/): Run the Serverless Infrastructure as Code framework with LocalStack.
- [`tflocal`](https://docs.localstack.cloud/user-guide/integrations/terraform/#tflocal-wrapper-script): Run the Terraform/OpenTofu Infrastructure as Code framework with LocalStack.

## Frameworks

- [Quarkus](https://docs.localstack.cloud/user-guide/integrations/quarkus/): Run LocalStack in your Quarkus application.
- [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws): Run LocalStack in your Spring and Spring Boot applications.
- [Testcontainers](https://testcontainers.com/modules/localstack/): Run LocalStack in your integration tests with Testcontainers.

## Continuous Integration (CI) Systems

- [CircleCI](https://circleci.com/developer/orbs/orb/localstack/platform): Run LocalStack in your CircleCI workflows.
- [GitHub Actions](https://github.com/localstack/setup-localstack/): Run LocalStack in your GitHub Actions workflows.

## Docker images

- [`localstack/localstack`](https://hub.docker.com/r/localstack/localstack): LocalStack Community Edition Docker image.
- [`localstack/localstack-pro`](https://hub.docker.com/r/localstack/localstack-pro): LocalStack Pro Docker image.
- [`localstack/localstack:s3-latest`](https://hub.docker.com/r/localstack/localstack): LocalStack S3 Docker image.
- [`localstack/localstack-pro:latest-bigdata`](https://hub.docker.com/r/localstack/localstack-pro): LocalStack Pro with Big Data dependencies pre-installed.

## Client libraries

- [.NET Client](https://github.com/localstack-dotnet/localstack-dotnet-client): .NET client library for LocalStack.
- [Go Client](https://github.com/elgohr/go-localstack): Go client library for LocalStack.
- [Python Client](https://github.com/localstack/localstack-python-client): Python client library for LocalStack.

## Tools

- [Cloudlens](https://github.com/one2nc/cloudlens): k9s like CLI for analyzing and managing local AWS resources in LocalStack.
- [diapretty](https://github.com/silv-io/diapretty): LocalStack diagnosis pretty printer to create diagnostics reports via the diagnostics endpoint.
- [Former2](https://former2.com/): Generate infrastructure as code templates from existing resources in your locally running LocalStack instance.
- [Leapp](https://docs.leapp.cloud/latest/configuring-session/configure-localstack/): Create LocalStack sessions in Leapp to connect to the cloud emulator.
- [VS Code Extension](https://github.com/localstack/localstack-vscode-extension): Visual Studio (VS) Code extension to deploy and manage Lambda functions on LocalStack.
- [LocalSurf](https://docs.localstack.cloud/user-guide/tools/localsurf/): Browser plugin to redirect AWS service calls to LocalStack.

## Platforms

- [Gitpod](https://github.com/whummer/localstack-gitpod-demo): Run LocalStack in Gitpod, a cloud-based IDE.
- [Helm Charts](https://github.com/localstack/helm-charts): Helm charts to deploy LocalStack on Kubernetes.
- [OpenShift](https://docs.localstack.cloud/user-guide/integrations/openshift/): Run LocalStack in OpenShift, a Kubernetes distribution.

## Extensions

- [Authress](https://pypi.org/project/localstack-extension-authress/): LocalStack extension to run the Authress server locally.
- [Diagnosis Viewer](https://pypi.org/project/localstack-extension-diagnosis-viewer/): LocalStack extension to view the diagnosis report.
- [httpbin](https://pypi.org/project/localstack-extension-httpbin/): LocalStack extension to run the httpbin service.
- [Mailhog](https://pypi.org/project/localstack-extension-mailhog/): LocalStack extension to run the Mailhog service.
- [Miniflare](https://pypi.org/project/localstack-extension-miniflare/): LocalStack extension to run Miniflare, a serverless Cloudflare worker emulator.
- [Stripe](https://pypi.org/project/localstack-extension-stripe/): LocalStack extension to run a stateful Stripe service mock.

[//]: # (!! Do not place anything under content - this part is periodically recreated to update list from existing resources.)

## Content

### Tutorials 

- ["How To: Collaborative AWS local development with LocalStack’s Cloud Pods"](https://docs.localstack.cloud/tutorials/cloud-pods-collaborative-debugging)
- ["Deploying containers on Elastic Container Service (ECS) clusters using Elastic Container Registry (ECR) and AWS Fargate, with LocalStack"](https://docs.localstack.cloud/tutorials/ecs-ecr-container-app)
- ["Setting up Elastic Load Balancing (ELB) Application Load Balancers using LocalStack, deployed via the Serverless framework"](https://docs.localstack.cloud/tutorials/elb-load-balancing)
- ["Creating ephemeral application previews with LocalStack and GitHub Actions"](https://docs.localstack.cloud/tutorials/ephemeral-application-previews)
- ["Chaos Engineering: Running Experiments with Fault Injection Service"](https://docs.localstack.cloud/tutorials/fault-injection-service-experiments)
- ["End-to-End Testing in Gitlab CI with Testcontainers and LocalStack: Understanding Runners and Docker in Docker"](https://docs.localstack.cloud/tutorials/gitlab_ci_testcontainers)
- ["Building a Java Notification app using AWS Java SDK, Simple Email Service (SES), and CloudFormation"](https://docs.localstack.cloud/tutorials/java-notification-app)
- ["Deploying Lambda container image locally with Elastic Container Registry (ECR) using LocalStack"](https://docs.localstack.cloud/tutorials/lambda-ecr-container-images)
- ["Replicating cloud resources locally with LocalStack's AWS Replicator extension"](https://docs.localstack.cloud/tutorials/replicate-aws-resources-localstack-extension)
- ["Creating reproducible machine learning applications using Cloud Pods for persistent state snapshots"](https://docs.localstack.cloud/tutorials/reproducible-machine-learning-cloud-pods)
- ["Chaos Engineering: Route53 Failover with FIS"](https://docs.localstack.cloud/tutorials/route53-failover-with-fis)
- ["Host a static website locally using Simple Storage Service (S3) and Terraform with LocalStack"](https://docs.localstack.cloud/tutorials/s3-static-website-terraform)
- ["Schema Evolution with Glue Schema Registry and Managed Streaming for Kafka (MSK) using LocalStack"](https://docs.localstack.cloud/tutorials/schema-evolution-glue-msk)
- ["Chaos Engineering: Simulating outages in your application stack"](https://docs.localstack.cloud/tutorials/simulating-outages-in-your-application-stack)

### Videos
#### "LocalStack 101"

- ["Course Overview"](https://docs.localstack.cloud/)
- ["What is LocalStack"](https://docs.localstack.cloud//academy/localstack-101/what-is-localstack/)
- ["Why LocalStack"](https://docs.localstack.cloud//academy/localstack-101/why-localstack/)
- ["Getting started"](https://docs.localstack.cloud//academy/localstack-101/getting-started/)
- ["Web App and Resource Browser"](https://docs.localstack.cloud//academy/localstack-101/web-app-resource-browser/)
- ["Full Project Demo"](https://docs.localstack.cloud//academy/localstack-101/full-project-demo/)
- ["Cloud Pods and Collaborative Work"](https://docs.localstack.cloud//academy/localstack-101/cloud-pods/)
#### "Development & Deployment with LocalStack"

- ["Course Overview"](https://docs.localstack.cloud/)
- ["Deploy a full fledged containerised application using LocalStack"](https://docs.localstack.cloud//academy/localstack-deployment/deploy-app-ls/)
- ["LocalStack Integrations - Infrastructure-as-Code and CI tools "](https://docs.localstack.cloud//academy/localstack-deployment/ls-integrations/)
- ["Creating infrastructure with Terraform locally"](https://docs.localstack.cloud//academy/localstack-deployment/infra-terraform/)
- ["Creating infra with CloudFormation locally"](https://docs.localstack.cloud//academy/localstack-deployment/infra-cloudformation/)
- ["Security Testing with IAM Policy Stream"](https://docs.localstack.cloud//academy/localstack-deployment/iam-policy-stream/)
- ["Setup GitHub Action workflow that starts up LocalStack and deploys the infrastructure"](https://docs.localstack.cloud//academy/localstack-deployment/github-action-ls)
- ["Cloud pods - Team Collaboration"](https://docs.localstack.cloud//academy/localstack-deployment/cloud-pods)

### Blog Posts 

- ["LocalStack: 30k stars, 40M pulls - and just getting started! 🚀"](https://blog.localstack.cloud/2021-05-06-localstack-40k-stars)
- ["Test Monitoring for LocalStack Apps"](https://blog.localstack.cloud/2021-09-16-test-monitoring-for-localstack-apps)
- ["Introducing LocalStack Cockpit"](https://blog.localstack.cloud/2022-02-07-localstack-cockpit)
- [Hot Swapping Python Lambda Functions using LocalStack](https://blog.localstack.cloud/2022-03-07-hot-swapping-python-lambda-functions-using-localstack)
- [Develop and Test Real-time Data Pipelines with LocalStack](https://blog.localstack.cloud/2022-04-04-develop-and-test-data-analytics-pipelines-on-localstack)
- [LocalStack — 40K stars, 90M pulls and an engaged community!](https://blog.localstack.cloud/2022-04-22-localstack-40k-stars-90m-pulls-and-an-engaged-community)
- [Debug Lambda functions from your IDE using LocalStack](https://blog.localstack.cloud/2022-05-09-debug-your-lamda-functions-from-your-ide-using-localstack)
- [Monitor your failing Lambdas with CloudWatch and LocalStack](https://blog.localstack.cloud/2022-05-25-cloudwatch-metric-alarms)
- [Announcing LocalStack Discussion Pages](https://blog.localstack.cloud/2022-06-08-announcing-localstack-discussion-pages)
- [Announcing LocalStack 1.0 General Availability!](https://blog.localstack.cloud/2022-07-13-announcing-localstack-v1-general-availability)
- [LocalStack and AWS Parity Explained](https://blog.localstack.cloud/2022-08-04-parity-explained)
- [Cloud Pods - Enabling state sharing and team collaboration for local cloud development](https://blog.localstack.cloud/2022-08-26-cloud-pods)
- [Announcing LocalStack Extensions](https://blog.localstack.cloud/2022-09-12-announcing-localstack-extensions)
- [LocalStack x Gitpod - Run cloud applications with LocalStack and Gitpod](https://blog.localstack.cloud/2022-09-26-localstack-x-gitpod-run-cloud-applications-with-localstack-and-gitpod)
- [Contribute to Open Source With LocalStack & Hacktoberfest](https://blog.localstack.cloud/2022-10-01-contribute-to-open-source-with-localstack-hacktoberfest)
- [Introducing LocalStack Docker Extension for Docker Desktop](https://blog.localstack.cloud/2023-01-13-introducing-localstack-extension-for-docker-desktop)
- [Announcing LocalStack 2.0 General Availability!](https://blog.localstack.cloud/2023-03-29-announcing-localstack-2.0-general-availability)
- [KnowBe4 redefines their local cloud development & testing using LocalStack](https://blog.localstack.cloud/2023-04-24-case-study-knowbe4)
- [Develop your Cloudflare Workers + AWS apps locally with LocalStack & Miniflare](https://blog.localstack.cloud/2023-06-26-develop-your-cloudflare-workers-aws-apps-locally-with-localstack-miniflare)
- [Xiatech accelerates their development workflows on cloud using LocalStack!](https://blog.localstack.cloud/2023-07-05-case-study-xiatech)
- [LocalStack has joined AWS Marketplace to streamline local cloud development & testing!](https://blog.localstack.cloud/2023-09-07-localstack-has-joined-aws-marketplace-to-streamline-local-cloud-development-testing)
- [OpenFABR leverages LocalStack for local Infrastructure as Code development and validation](https://blog.localstack.cloud/2023-09-25-case-study-openfabr)
- [Introducing LocalStack Desktop Application for local cloud development & testing](https://blog.localstack.cloud/2023-11-09-introducing-localstack-desktop-application-for-local-cloud-development-testing)
- [Join LocalStack at AWS re:Invent 2023](https://blog.localstack.cloud/2023-11-09-join-localstack-at-aws-reinvent-2023)
- [Announcing LocalStack 3.0 General Availability!](https://blog.localstack.cloud/2023-11-16-announcing-localstack-30-general-availability)
- [AWS re:Invent - Ten Things You Need to Know About LocalStack](https://blog.localstack.cloud/2023-11-27-ten-things-you-need-to-know-about-localstack)
- ["One Click Local Development: Announcing Leapp's LocalStack Integration"](https://blog.localstack.cloud/2023-12-18-one-click-local-development-announcing-leapps-localstack-integration)
- [Celebrating 50,000 GitHub Stars for LocalStack!](https://blog.localstack.cloud/2024-01-03-celebrating-50k-github-stars-localstack)
- [Neurolytics enhances the efficiency and agility of its cloud-based development with LocalStack](https://blog.localstack.cloud/2024-01-25-localstack-neurolyticsai)
- [Add Authentication & Authorization to LocalStack with the Authress extension](https://blog.localstack.cloud/2024-02-07-add-authentication-authorization-to-localstack-with-the-authress-extension)
- [Mastering AWS Infrastructure Testing with LocalStack Cloud Pods - on localhost, CI and Testcontainers](https://blog.localstack.cloud/2024-02-20-cloud-pods-local-to-ci-and-testcontainers)
- [How we are making connecting to LocalStack easier](https://blog.localstack.cloud/2024-03-04-making-connecting-to-localstack-easier)
- [Renaming the Pro Tier](https://blog.localstack.cloud/2024-03-22-pro-starter-rename)
- [CartonCloud utilizes LocalStack for transforming development efficiency and agility!](https://blog.localstack.cloud/2024-03-28-localstack-cartoncloud)
- [Exploring S3 Mocking Tools — A Comparative Analysis of S3Mock, MinIO, and LocalStack](https://blog.localstack.cloud/2024-04-08-exploring-s3-mocking-tools-a-comparative-analysis-of-s3mock-minio-and-localstack)
- [Ephemeral Environments with LocalStack & Shipyard](https://blog.localstack.cloud/2024-04-22-ephemeral-environments-with-localstack-shipyard)
- [Building LocalStack with LocalStack](https://blog.localstack.cloud/2024-05-08-building-localstack-with-localstack)
- ["Introducing LocalStack for Snowflake: The new emulator to build & test data pipelines locally"](https://blog.localstack.cloud/2024-05-22-introducing-localstack-for-snowflake)
- [](https://blog.localstack.cloud/tags)

