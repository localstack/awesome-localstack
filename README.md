<p align="center">
  <img src="https://raw.githubusercontent.com/localstack/localstack/master/doc/localstack-readme-banner.svg" alt="LocalStack - A fully functional local cloud stack">
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

## Content

### Tutorials

### Blog Posts
