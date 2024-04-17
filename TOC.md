# GitHub Actions Cookbook

**A practical guide to automating engineering tasks with GitHub actions beyond CI/CD.**

This is the central companon repository for the book 'GitHub Actions Cookbook' by [Michael Kaufmann](https://github.com/wulfland). You will find the links here to the actual hands-on recipes in the book.

## Chapter 1: GitHub Actions workflows

This chapter will introduce you to GitHub Actions workflows and what you can do with them. You will learn YAML basics, events that trigger workflows, expressions, and how to use GitHub Actions from the marketplace to automate all kind of tasks.

The chapter contains the following topics:

- The GitHub Ecosystem
- Hosting and Pricing
- The GitHub marketplace
- Using the workflow editor for writing workflows
- Using secrets and variables
- Creating and using environments

You can find the examples and solutions in [GitHubActionsCookbook](https://github.com/wulfland/GitHubActionsCookbook) repository. 

## Chapter 2: Authoring and debugging workflows

This chapter will teach you best practices for authoring workflows: how to use Visual Studio Code or GitHub Codespaces and various add-ins to efficiently create, edit, and run workflows, check them for errors with powerful linters, develop them in branches, run them locally, and how you can debug them and turn on advanced logging.

The chapter contains the following topics:

- Using Visual Studio Code for authoring workflows
- Developing workflows in branches
- Linting workflows
- Writing messages to the log
- Enable debug logging
- Run your workflows locally

You can find the examples and solutions in [GitHubActionsCookbook](https://github.com/wulfland/GitHubActionsCookbook) repository.

## Chapter 3: Building GitHub Actions

This chapter explains the different types of GitHub Actions, and you will learn to use input and output. You will write your own Docker container action, a TypeScript action, and a composite action.

The chapter contains the following topics:

- Creating a Docker container action
- Adding output parameters and using job summaries
- Creating a TypeScript action
- Creating a composite action
- Sharing actions to the marketplace
- Best practices for developing custom actions

You can find the solutions for this recipes in the following repositories:

- [Docker Container Action Recipe](https://github.com/wulfland/DockerActionRecipe)
- [TypeScript Action Recipe](https://github.com/wulfland/TypeScriptActionRecipe)
- [Composite Action Recipe](https://github.com/wulfland/CompositeActionRecipe)

## Chapter 4: The Workflow Runtime

This chapter is about the different runtime options for your workflows. You will learn how to use different GitHub-hosted runners and how to set up and scale ephemeral, self-hosted runners in Docker containers and in Kubernetes with [GitHub Actions Controller (GHAC)](https://github.com/actions/actions-runner-controller).

The chapter contains the following topics:
- Setting up a self-hosted runner
- Auto-scaling self-hosted runners
- Scaling self-hosted runners with Kubernetes using Actions Runner Controller (ARC)
- Runners and Runner Groups
- GitHub hosted runners
- Set up a large runner
- Managing and autos-scaling ephemeral runners
- Security for GitHub-hosted and self-hosted runners

You can find the examples and solutions in [GitHubActionsCookbook](https://github.com/wulfland/GitHubActionsCookbook) repository.

## Chapter 5: Automate tasks in GitHub with GitHub Actions

This chapter will show you how to use Issue-Ops to automate common tasks within GitHub. You will learn how to authenticate with GitHub Apps, use the `GITHUB_TOKEN` and workflow permissions, use the [GitHub CLI](https://cli.github.com/) to automate tasks, use environments for approvals and checks, and use reusable workflows and composite actions to share logic across workflows and repositories.

The chapter covers:
- Creating an Issue template
- Using the GitHub CLI and the GITHUB_TOKEN to access resources
- Using environments for approvals and checks 
- Reusable workflows and composite actions

https://github.com/wulfland/GitHubActionsCookbook

## Chapter 6: Build and validate your code

This chapter is is about Continuous Integration (CI). You will learn how to build and test different versions of your code with the same workflow, find security vulnerabilities in your code with CodeQL, attach a Software Bill of Materials (SBOM) to your release, automate the versioning of your software, and use caching to speed up your workflows.

The chapter covers:
- Build and test your code
- Build different versions using a matrix
- Informing the user on details of your build and test results
- Find security vulnerabilities with CodeQL
- Creating a Release and publishing the package
- Versioning your packages
- Generating and using SBOMs
- Use caching in workflows

You will find the solutions for the recipes in the [package-recipe](https://github.com/wulfland/package-recipe) repository. 

## Chapter 7: Release your software with GitHub Actions

This chapter covers Continuous Delivery and Continuous Deployment (CD). You will learn how to securely deploy to the cloud using OpenID Connect (OIDC), how to deploy containers to Kubernetes – whether it is Microsoft Azure Kubernetes Service (AKS), Google Kubernetes Engine (GKE), or Elastic Container Services (ECS). You will also learn how to use Dependabot together with GitHub Actions to completely automate the update of your dependencies.

The chapter covers:
- Build and publish a container
- Using OIDC to securely deploy to any cloud
- Environment approval checks
- Release the container application to Azure Kubernetes Service (AKS)
- Automate the update of your dependencies

You will find the solutions for the recipe  to deploy to Azure Kubernetes Services (AKS) in the [release-recipe](https://github.com/wulfland/release-recipe) repository. 

There are additional hands-on labs for deploying to [AWS Elastic Container Service (ECS)](https://github.com/wulfland/AccelerateDevOps/blob/main/ch9_release/Deploy_to_AWS_ECS.md) and [Google Kubernetes Engine (GKE)](https://github.com/wulfland/AccelerateDevOps/blob/main/ch9_release/Deploy_to_GKE.md).

