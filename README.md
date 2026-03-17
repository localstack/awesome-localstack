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
- [Local Admin](https://github.com/Mohammad-Bilal-Bhatti/local-admin): Open localstack Admin UI – Sneak peek your localstack resources with button clicks.

## Integrations

- [`arclocal`](https://docs.localstack.cloud/aws/integrations/app-frameworks/architect/): Run Architect Infrastructure as Code framework with LocalStack.
- [`awslocal`](https://docs.localstack.cloud/aws/integrations/aws-native-tools/aws-cli/#localstack-aws-cli-awslocal): Run the AWS Command Line Interface (CLI) with LocalStack.
- [AWS SDK for .NET](https://docs.localstack.cloud/aws/integrations/aws-sdks/net/): Run .NET applications against LocalStack using the AWS SDK for .NET.
- [AWS SDK for Go](https://docs.localstack.cloud/aws/integrations/aws-sdks/go/): Run Go applications against LocalStack using the AWS SDK for Go.
- [AWS SDK for Java](https://docs.localstack.cloud/aws/integrations/aws-sdks/java/): Run Java applications against LocalStack using the AWS SDK for Java.
- [AWS SDK for JavaScript](https://docs.localstack.cloud/aws/integrations/aws-sdks/javascript/): Run JavaScript/TypeScript applications against LocalStack using the AWS SDK for JavaScript.
- [AWS SDK for Python (Boto3)](https://docs.localstack.cloud/aws/integrations/aws-sdks/python-boto3/): Run Python applications against LocalStack using Boto3.
- [`cdklocal`](https://docs.localstack.cloud/aws/integrations/aws-native-tools/aws-cdk/): Run the AWS Cloud Development Kit Infrastructure as Code framework with LocalStack.
- [`chalice-local`](https://docs.localstack.cloud/aws/integrations/aws-native-tools/aws-chalice/): Run the AWS Chalice serverless micro-framework with LocalStack.
- [`copilotlocal`](https://docs.localstack.cloud/aws/integrations/aws-native-tools/aws-copilot-cli/): Run the Copilot CLI to build AWS containerized applications with LocalStack.
- [Crossplane](https://docs.localstack.cloud/aws/integrations/infrastructure-as-code/crossplane/): Run Crossplane control planes against LocalStack.
- [`pulumilocal`](https://docs.localstack.cloud/aws/integrations/infrastructure-as-code/pulumi/#pulumilocal): Run the Pulumi Infrastructure as Code framework with LocalStack.
- [`samlocal`](https://docs.localstack.cloud/aws/integrations/aws-native-tools/aws-sam/): Run the Serverless Application Model Infrastructure as Code framework with LocalStack.
- [`serverless-localstack`](https://docs.localstack.cloud/aws/integrations/app-frameworks/serverless-framework/): Run the Serverless Infrastructure as Code framework with LocalStack.
- [`tflocal`](https://docs.localstack.cloud/aws/integrations/infrastructure-as-code/terraform/#tflocal-wrapper-script): Run the Terraform/OpenTofu Infrastructure as Code framework with LocalStack.

## Frameworks

- [.NET Aspire](https://docs.localstack.cloud/aws/integrations/app-frameworks/aspire/): Integrate LocalStack with .NET Aspire cloud-native applications.
- [Quarkus](https://docs.localstack.cloud/aws/integrations/app-frameworks/quarkus/): Run LocalStack in your Quarkus application.
- [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws): Run LocalStack in your Spring and Spring Boot applications.
- [Testcontainers](https://testcontainers.com/modules/localstack/): Run LocalStack in your integration tests with Testcontainers.

## Continuous Integration (CI) Systems

- [CircleCI](https://circleci.com/developer/orbs/orb/localstack/platform): Run LocalStack in your CircleCI workflows.
- [GitHub Actions](https://github.com/localstack/setup-localstack/): Run LocalStack in your GitHub Actions workflows.

## Docker images

- [`localstack/localstack`](https://hub.docker.com/r/localstack/localstack): LocalStack Docker image for AWS emulation.
- [`localstack/snowflake`](https://hub.docker.com/r/localstack/snowflake): LocalStack Docker image for Snowflake emulation.
- [`localstack/localstack-azure-alpha`](https://hub.docker.com/r/localstack/localstack-azure-alpha): LocalStack Docker image for Azure emulation.

## Client libraries

- [LocalStack SDKs Overview](https://docs.localstack.cloud/aws/tooling/localstack-sdks/): Overview of LocalStack SDKs for programmatic access to LocalStack developer endpoints.
- [LocalStack SDK for Java](https://docs.localstack.cloud/aws/tooling/localstack-sdks/java-sdk/): Java SDK for Cloud Pods and Chaos API workflows.
- [LocalStack SDK for Python](https://docs.localstack.cloud/aws/tooling/localstack-sdks/python-sdk/): Python SDK for Cloud Pods, Chaos API, state management, and developer endpoints.
- [.NET Client](https://github.com/localstack-dotnet/localstack-dotnet-client): .NET client library for LocalStack.
- [Go Client](https://github.com/elgohr/go-localstack): Go client library for LocalStack.
- [Python Client](https://github.com/localstack/localstack-python-client): Python client library for LocalStack.

## Tools

- [AWS Replicator](https://docs.localstack.cloud/aws/tooling/aws-replicator/): Replicate cloud resources into your local LocalStack environment.
- [Cloudlens](https://github.com/one2nc/cloudlens): k9s like CLI for analyzing and managing local AWS resources in LocalStack.
- [diapretty](https://github.com/silv-io/diapretty): LocalStack diagnosis pretty printer to create diagnostics reports via the diagnostics endpoint.
- [DNS Server](https://docs.localstack.cloud/aws/tooling/dns-server/): DNS-based endpoint injection and local DNS tooling for LocalStack.
- [Event Studio](https://docs.localstack.cloud/aws/tooling/event-studio/): Record, trace, debug, and replay events exchanged between AWS services.
- [Former2](https://former2.com/): Generate infrastructure as code templates from existing resources in your locally running LocalStack instance.
- [Lambda Tools](https://docs.localstack.cloud/aws/tooling/lambda-tools/): Hot-reload and other tooling to develop Lambda functions more efficiently.
- [Leapp](https://docs.leapp.cloud/latest/configuring-session/configure-localstack/): Create LocalStack sessions in Leapp to connect to the cloud emulator.
- [LocalStack CLI](https://docs.localstack.cloud/aws/tooling/localstack-cli/): Official command line interface to manage LocalStack.
- [Testing Utils](https://docs.localstack.cloud/aws/tooling/testing-utils/): Utility tooling for local and CI testing with LocalStack.
- [LocalStack Toolkit for VS Code](https://docs.localstack.cloud/aws/tooling/vscode-extension/): Toolkit for VS Code to manage LocalStack.
- [LocalSurf](https://docs.localstack.cloud/aws/tooling/localsurf/): Browser plugin to redirect AWS service calls to LocalStack.

## Platforms

- [DevContainers](https://docs.localstack.cloud/aws/integrations/containers/devcontainers/): Run LocalStack in reproducible containerized development environments.
- [eksctl](https://docs.localstack.cloud/aws/integrations/containers/eksctl/): Run and validate EKS-centric workflows against LocalStack.
- [Gitpod](https://github.com/whummer/localstack-gitpod-demo): Run LocalStack in Gitpod, a cloud-based IDE.
- [Helm Charts](https://github.com/localstack/helm-charts): Helm charts to deploy LocalStack on Kubernetes.
- [OpenShift](https://docs.localstack.cloud/aws/integrations/containers/openshift/): Run LocalStack in OpenShift, a Kubernetes distribution.
- [Rancher Desktop](https://docs.localstack.cloud/aws/integrations/containers/rancher-desktop/): Run LocalStack with Rancher Desktop.

## Extensions

- [Authress](https://pypi.org/project/localstack-extension-authress/): LocalStack extension to run the Authress server locally.
- [AWS Replicator](https://docs.localstack.cloud/aws/tooling/aws-replicator/): LocalStack extension to replicate live AWS resources locally.
- [Diagnosis Viewer](https://pypi.org/project/localstack-extension-diagnosis-viewer/): LocalStack extension to view the diagnosis report.
- [Event Studio Extension](https://pypi.org/project/localstack-extension-event-studio/): LocalStack extension for event tracing, inspection, and replay workflows.
- [httpbin](https://pypi.org/project/localstack-extension-httpbin/): LocalStack extension to run the httpbin service.
- [Mailhog](https://pypi.org/project/localstack-extension-mailhog/): LocalStack extension to run the Mailhog service.
- [Miniflare](https://pypi.org/project/localstack-extension-miniflare/): LocalStack extension to run Miniflare, a serverless Cloudflare worker emulator.
- [ParadeDB](https://pypi.org/project/localstack-paradedb/): LocalStack extension for running ParadeDB search databases locally.
- [Resource Graph](https://pypi.org/project/localstack-extension-resource-graph/): LocalStack extension to build resource graphs and import into Neptune.
- [Stripe](https://pypi.org/project/localstack-extension-stripe/): LocalStack extension to run a stateful Stripe service mock.
- [Terraform Init](https://pypi.org/project/localstack-extension-terraform-init/): LocalStack extension to run Terraform files as initialization hooks.
- [TypeDB](https://pypi.org/project/localstack-extension-typedb/): LocalStack extension for building and testing TypeDB-based applications locally.
- [WireMock](https://pypi.org/project/localstack-wiremock/): LocalStack extension for running WireMock mock APIs locally.

[//]: # (!! Do not place anything under content - this part is periodically recreated to update list from existing resources.)

## Content

### Tutorials

#### AWS

- [Building a Java Notification app using AWS Java SDK, Simple Email Service (SES), and CloudFormation](https://docs.localstack.cloud/tutorials/java-notification-app)
- [Building a Serverless Quiz Application with LocalStack](https://docs.localstack.cloud/aws/tutorials/serverless-quiz-app/)
- [Chaos Engineering: Route53 Failover](https://docs.localstack.cloud/tutorials/route-53-failover)
- [Chaos Engineering: Simulating Outages using Chaos API](https://docs.localstack.cloud/tutorials/simulating-outages)
- [Creating ephemeral application previews with LocalStack and GitHub Actions](https://docs.localstack.cloud/tutorials/ephemeral-application-previews)
- [Creating reproducible machine learning applications using Cloud Pods for persistent state snapshots](https://docs.localstack.cloud/tutorials/reproducible-machine-learning-cloud-pods)
- [Deploying containers on Elastic Container Service (ECS) clusters using Elastic Container Registry (ECR) and AWS Fargate, with LocalStack](https://docs.localstack.cloud/tutorials/ecs-ecr-container-app)
- [Deploying Lambda container image locally with Elastic Container Registry (ECR) using LocalStack](https://docs.localstack.cloud/tutorials/lambda-ecr-container-images)
- [End-to-End Testing in Gitlab CI with Testcontainers and LocalStack: Understanding Runners and Docker in Docker](https://docs.localstack.cloud/tutorials/gitlab_ci_testcontainers)
- [Generate IAM Policies with LocalStack IAM Policy Stream](https://docs.localstack.cloud/tutorials/iam-policy-stream)
- [Host a static website locally using Simple Storage Service (S3) and Terraform with LocalStack](https://docs.localstack.cloud/tutorials/s3-static-website-terraform)
- [How To: Collaborative AWS local development with LocalStack's Cloud Pods](https://docs.localstack.cloud/tutorials/cloud-pods-collaborative-debugging)
- [How To: Terraform Init Hooks for Automation & Production-Identical Test Environments](https://docs.localstack.cloud/tutorials/using-terraform-with-testcontainers-and-localstack)
- [Initializing an RDS Database with AWS CDK and LocalStack](https://docs.localstack.cloud/aws/tutorials/)
- [Replicating cloud resources locally with LocalStack's AWS Cloud Proxy extension](https://blog.localstack.cloud/replicating-live-cloud-resources-locally-with-localstack-aws-replicator/)
- [Schema Evolution with Glue Schema Registry and Managed Streaming for Kafka (MSK) using LocalStack](https://docs.localstack.cloud/tutorials/schema-evolution-glue-msk)
- [Setting up Elastic Load Balancing (ELB) Application Load Balancers using LocalStack, deployed via the Serverless framework](https://docs.localstack.cloud/tutorials/elb-load-balancing)
- [Tutorial: Terraform Fullstack Serverless Shipment App](https://docs.localstack.cloud/aws/tutorials/)
- [Automate Terraform testing with LocalStack & GitHub Actions](https://blog.localstack.cloud/automate-terraform-testing-localstack-github-actions/)
- [Automate Your Serverless Tests with GitHub Actions and LocalStack](https://blog.localstack.cloud/automate-your-tests-with-github-actions-and-localstack/)
- [Debug AWS Lambda Functions Locally Using LocalStack's Lambda Debug Mode](https://blog.localstack.cloud/debug-aws-lambda-functions-locally-using-localstack-debug-mode/)
- [Developing & Debugging AWS ECS Tasks Locally with LocalStack & VS Code](https://blog.localstack.cloud/developing-debugging-aws-ecs-tasks-localstack-vs-code/)
- [Emulate AWS CI/CD Services in LocalStack](https://blog.localstack.cloud/emulate-ci-cd-services-in-localstack/)
- [Generating & testing AWS IAM policies locally with LocalStack](https://blog.localstack.cloud/generating-testing-iam-policies-locally-with-localstack/)
- [Injecting Chaos into DynamoDB with LocalStack](https://blog.localstack.cloud/injecting-chaos-into-dynamodb-with-localstack/)
- [Integration testing for Pulumi programs with LocalStack & Automation API](https://blog.localstack.cloud/integration-testing-pulumi-localstack-automation-api/)
- [Local Testing of SES Workflows Using LocalStack & MailHog Extension](https://blog.localstack.cloud/local-testing-ses-workflows-localstack-mailhog-extension/)
- [Monitor your failing Lambdas with CloudWatch and LocalStack](https://blog.localstack.cloud/2022-05-25-cloudwatch-metric-alarms/)
- [Peeking into SQS Queues Locally with LocalStack's SQS Developer Endpoint](https://blog.localstack.cloud/peeking-into-sqs-queues-locally-with-localstack-developer-endpoint/)
- [Preview Environments for AWS apps on every Pull Request with LocalStack](https://blog.localstack.cloud/preview-environment-aws-apps-pull-requests-localstack/)
- [Simulating AWS Outages Locally with Chaos Engineering](https://blog.localstack.cloud/break-it-till-you-make-it-chaos-engineering/)
- [Testing AWS Fault Injection Service (FIS) templates using LocalStack](https://blog.localstack.cloud/testing-aws-fault-injection-service-templates-using-localstack/)
- [Testing Serverless Apps Locally — AWS SAM Local vs LocalStack](https://blog.localstack.cloud/testing-serverless-apps-locally-aws-sam-local-vs-localstack/)

#### Snowflake

- [Connecting Snowpark to Lambda using LocalStack](https://docs.localstack.cloud/snowflake/tutorials/aws-lambda-localstack-snowpark/)
- [Credit Scoring with Snowpark & LocalStack](https://docs.localstack.cloud/snowflake/tutorials/credit-scoring-with-localstack-snowpark/)
- [Querying S3 Tables with Snowflake](https://docs.localstack.cloud/snowflake/tutorials/s3-tables-iceberg-integration/)
- [Integrating Polaris with LocalStack for Snowflake and Trino](https://blog.localstack.cloud/integrating-polaris-with-localstack-for-snowflake-and-trino/)
- [Running dbt workflows locally with LocalStack for Snowflake](https://blog.localstack.cloud/running-dbt-workflows-locally-with-localstack-for-snowflake/)

### Videos

- [Your First Local AWS App in 4 Steps with LocalStack and Terraform](https://www.youtube.com/watch?v=GvkXVzPse-M)
- [Getting started with the LocalStack Model Context Protocol (MCP) Server](https://www.youtube.com/watch?v=9DLSr7fxNag)
- [WTH is Chaos Engineering?! A Quick Look at Breaking Things on Purpose](https://www.youtube.com/watch?v=nSEfnAgBjh0)
- [Smarter Serverless Dev with LocalStack  VS Code Toolkit & Lambda Debugging](https://www.youtube.com/watch?v=Q_4e9ns50ew)
- [Break It Till You Make It: Introducing Chaos into Your Stack Locally](https://www.youtube.com/watch?v=tRVPuYk_Ew0)
- [Getting started with the LocalStack Dagger module](https://www.youtube.com/watch?v=AbxGwJQRSws)
- [Saving & Sharing Your LocalStack State with CloudPods](https://www.youtube.com/watch?v=zwj1gCC4MII)
- [Automate Your Tests with GitHub Actions & LocalStack](https://www.youtube.com/watch?v=igPotAAnUVo)
- [Test Your Cloud Workflows Locally Like a Boss](https://www.youtube.com/watch?v=cXoQa8x8Qb4)
- [Fake It Till You Make It: Cloud Edition](https://www.youtube.com/watch?v=Spb6Vof-fbM)
- [Run Your First AWS App Locally with LocalStack](https://www.youtube.com/watch?v=FPc42EnypJo)
- [Develop and test your AI-powered cloud apps locally with LocalStack](https://www.youtube.com/watch?v=_7_LGa8H0NY)
- [Running dbt workflows locally with LocalStack by Harsh Mishra](https://www.youtube.com/watch?v=eclMUqK6U0g)
- [Emulating AWS CI CD pipelines with LocalStack by Viren Nadkarni](https://www.youtube.com/watch?v=Bnm8n9xkLtU)
- [Testing Terraform Modules in Local and CI Environments with LocalStack](https://www.youtube.com/watch?v=mnIchOqOzl4)
- [Local Debugging for Lambda Functions via new Lambda Debug Mode](https://www.youtube.com/watch?v=o4WeUMuVjeo)
- [Simulating outages with LocalStack Chaos API](https://www.youtube.com/watch?v=2lOzScJNsDk)
- [Serverless Best Practices with AWS Lambda PowerTools by Brian Rinaldi](https://www.youtube.com/watch?v=w2PkSd4ElBY)
- [New Event Studio](https://www.youtube.com/watch?v=GXmQpjDC38E)
- [Unified Kubernetes Support in LocalStack](https://www.youtube.com/watch?v=P7CMTR5h_44)
- [New Bedrock Support in LocalStack](https://www.youtube.com/watch?v=V_l4KDTYlbQ)
- [How to install LocalStack Snowflake Emulator](https://www.youtube.com/watch?v=YLURdQH0fk4)
- [Smooth transition from local development to production for your AWS-powered applications](https://www.youtube.com/watch?v=y5hBhnigg5I)
- [Multi-account and multi-region in LocalStack](https://www.youtube.com/watch?v=0akCPYfhGRg)
- [AWS Data Streaming with LocalStack in Action](https://www.youtube.com/watch?v=gbPJVSO9Rig)
- [Building LocalStack with LocalStack](https://www.youtube.com/watch?v=Xy51M_C9ZEI)
- [Deploy and Test Data Migration Pipeline with DMS](https://www.youtube.com/watch?v=kfKktLliHx4)
- [Accelerate your cloud development with Cloud Pods and LocalStack](https://www.youtube.com/watch?v=UjgrreLsnp4)
- [Testing CloudWatch metric alarms with LocalStack](https://www.youtube.com/watch?v=rA0oD5bRQ_0)
- [How to use AWS SDKs with LocalStack](https://www.youtube.com/watch?v=BjCfi-_asYU)
- [Deploy and invoke Lambda functions in LocalStack using VS Code Extension](https://www.youtube.com/watch?v=txVPCF-TITk)
- [Mounting local directories for ECS tasks with LocalStack](https://www.youtube.com/watch?v=99dC4ziLxBU)
- [LocalStack Neptune development with G.V() — Gremlin IDE](https://www.youtube.com/watch?v=MESmS-sJ-cM)
- [How to save state in LocalStack?](https://www.youtube.com/watch?v=0Gk2rBtlcwA)
- [Replicating cloud resources locally with LocalStack's AWS Replicator extension](https://www.youtube.com/watch?v=wSFN3oJbYrk)
- [Towards a LocalStack Snowflake emulator—develop your data pipelines locally!](https://www.youtube.com/watch?v=fWYRfuNMxuU)
- [Developing & Testing Data pipelines locally with LocalStack!](https://www.youtube.com/watch?v=x7b7wWWKHHQ)
- [Running an EC2 instance locally using LocalStack](https://www.youtube.com/watch?v=86bHRjDPstA)
- [Improving Networking in LocalStack](https://www.youtube.com/watch?v=Nad-vhM4Tsw)
- [IAM Policy Stream](https://www.youtube.com/watch?v=HQ2V44ImJ3E)
- [How to hot reload your Lambda functions locally with LocalStack](https://www.youtube.com/watch?v=DFS3CnB-Z0k)
- [Handwritten digit recognition using MNIST model and Sagemaker on LocalStack](https://www.youtube.com/watch?v=r_SU4KFr3eY)
- [Getting started with LocalStack's Extension for Docker Desktop](https://www.youtube.com/watch?v=riNR9ymapWM)
- [Team Collaboration using LocalStack Cloud Pods](https://www.youtube.com/watch?v=s40Vy6nUI94)
- [Adopting Testcontainers for local development](https://www.youtube.com/watch?v=he6Mtn3xCNU)
- [Testing Terraform AWS Modules in Harness CI with LocalStack](https://www.youtube.com/watch?v=IYo4qhe9yls)
- [Local AWS Development with LocalStack](https://www.youtube.com/watch?v=SYCeM-Q6nRs)

### Blog Posts

- [Build Search Applications Locally with LocalStack and ParadeDB](https://blog.localstack.cloud/build-search-apps-locally-paradedb-localstack/)
- [Simulate External APIs locally with the WireMock Extension for LocalStack](https://blog.localstack.cloud/simulate-external-apis-locally-with-the-wiremock-extension-for-localstack/)
- [Build Knowledge Graph Applications with LocalStack and TypeDB Extension](https://blog.localstack.cloud/build-knowledge-graph-applications-localstack-typedb-extension/)
- [Effective Unit Testing for AWS Step Functions](https://blog.localstack.cloud/effective-unit-testing-for-aws-step-functions/)
- [Testing Locally with Lambda Managed Instances](https://blog.localstack.cloud/testing-locally-with-lambda-managed-instances/)
- [Generate Infrastructure as Code from local AWS resources using LocalStack & Former2](https://blog.localstack.cloud/generate-infrastructure-as-code-from-local-aws-resources-using-localstack-former2/)
- [5 Cloud Pods Features You Might Have Missed](https://blog.localstack.cloud/5-cloud-pods-features-you-might-have-missed/)
- [Streamlining Chaos testing with LocalStack's Chaos Engineering dashboard](https://blog.localstack.cloud/streamlining-chaos-testing-localstack-chaos-engineering-dashboard/)
- [5 LocalStack Features You're Probably Sleeping On (Even if You're Only Using It for AWS)](https://blog.localstack.cloud/5-localstack-features-youre-sleeping-on/)
- [Introducing the LocalStack SDK for Python](https://blog.localstack.cloud/introducing-the-localstack-sdk-for-python/)
- [Supercharge Your Testing Using JetBrains Aqua with LocalStack](https://blog.localstack.cloud/jetbrains-aqua-with-localstack/)
- [Take Your Local Testing to the Cloud with Ephemeral Instances](https://blog.localstack.cloud/2024-08-28-ephemeral-instances/)
- [Developing cloud AI-powered apps with LocalStack and Ollama](https://blog.localstack.cloud/2024-07-04-develop-cloud-ai-with-ollama-localstack/)
- [LocalStack Neptune development with G.V() — Gremlin IDE](https://blog.localstack.cloud/2024-06-05-localstack-neptune-development-with-gv-gremlin-ide/)
- [Building LocalStack with LocalStack](https://blog.localstack.cloud/2024-05-08-building-localstack-with-localstack/)
- [Ephemeral Environments with LocalStack & Shipyard](https://blog.localstack.cloud/2024-04-22-ephemeral-environments-with-localstack-shipyard/)
- [Exploring S3 Mocking Tools — A Comparative Analysis of S3Mock, MinIO, and LocalStack](https://blog.localstack.cloud/2024-04-08-exploring-s3-mocking-tools-a-comparative-analysis-of-s3mock-minio-and-localstack/)
- [Mastering AWS Infrastructure Testing with LocalStack Cloud Pods - on localhost, CI and Testcontainers](https://blog.localstack.cloud/2024-02-20-cloud-pods-local-to-ci-and-testcontainers/)
- [Add Authentication & Authorization to LocalStack with the Authress extension](https://blog.localstack.cloud/2024-02-07-add-authentication-authorization-to-localstack-with-the-authress-extension/)
- [Develop your Cloudflare Workers + AWS apps locally with LocalStack & Miniflare](https://blog.localstack.cloud/2023-06-26-develop-your-cloudflare-workers-aws-apps-locally-with-localstack-miniflare/)
- [LocalStack x Gitpod - Run cloud applications with LocalStack and Gitpod](https://blog.localstack.cloud/2022-09-26-localstack-x-gitpod-run-cloud-applications-with-localstack-and-gitpod/)
- [The Road Ahead for LocalStack: Upcoming Changes to the Delivery of Our AWS Cloud Emulators](https://blog.localstack.cloud/the-road-ahead-for-localstack/)
- [LocalStack for AWS Is Moving to a Single Image. Here are Your Next Steps](https://blog.localstack.cloud/localstack-single-image-next-steps/)
- [Introducing the LocalStack Model Context Protocol (MCP) Server](https://blog.localstack.cloud/introducing-localstack-mcp-server/)
- [What's New in LocalStack Docs: August-September 2025](https://blog.localstack.cloud/whats-new-in-docs-august-september/)
- [Announcing the LocalStack Docs v2 Launch](https://blog.localstack.cloud/announcing-localstack-docs-v2/)
- [What's new in LocalStack for Snowflake?](https://blog.localstack.cloud/whats-new-in-localstack-for-snowflake/)
- [Introducing LocalStack for Snowflake: The new emulator to build & test data pipelines locally](https://blog.localstack.cloud/2024-05-22-introducing-localstack-for-snowflake/)
- [How we are making connecting to LocalStack easier](https://blog.localstack.cloud/2024-03-04-making-connecting-to-localstack-easier/)
- [One Click Local Development: Announcing Leapp's LocalStack Integration](https://blog.localstack.cloud/2023-12-18-one-click-local-development-announcing-leapps-localstack-integration/)
- [Introducing LocalStack Desktop Application for local cloud development & testing](https://blog.localstack.cloud/2023-11-09-introducing-localstack-desktop-application-for-local-cloud-development-testing/)
- [LocalStack has joined AWS Marketplace to streamline local cloud development & testing!](https://blog.localstack.cloud/2023-09-07-localstack-has-joined-aws-marketplace-to-streamline-local-cloud-development-testing/)
- [Introducing LocalStack Docker Extension for Docker Desktop](https://blog.localstack.cloud/2023-01-13-introducing-localstack-extension-for-docker-desktop/)
- [Announcing LocalStack Extensions](https://blog.localstack.cloud/2022-09-12-announcing-localstack-extensions/)
- [Cloud Pods - Enabling state sharing and team collaboration for local cloud development](https://blog.localstack.cloud/2022-08-26-cloud-pods/)
- [LocalStack and AWS Parity Explained](https://blog.localstack.cloud/2022-08-04-parity-explained/)
