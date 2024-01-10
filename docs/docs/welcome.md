---
sidebar_position: 1
---

# Welcome! 👋

Setting up a new ROS 2 project often requires a significant amount of
preparation and boilerplate configuration, costing you valuable robot
development time 🤖. Recognizing this, we have put together [ros2-template](https://github.com/Robotic-Decision-Making-Lab/ros2-template):
a template repository configured with a ROS 2 development environment,
documentation, and continuous integration. This project is the result of much
trial and error across many projects, and we hope that this helps you save some
effort in setting up your own projects.

## Features

The main features of this template are:

- **A development environment for Visual Studio Code.** Throughout our projects
we converged onto a development container workflow similar to that provided by
Allison Thackston's [vscode_ros2_workspace](https://github.com/athackst/vscode_ros2_workspace).
Though, our project includes additional configurations for linting and
auto-formating your code using [Clang Format](https://clang.llvm.org/docs/ClangFormat.html),
[Clang Tidy](https://clang.llvm.org/extra/clang-tidy/), and [Ruff](https://github.com/astral-sh/ruff).
- **Docker images that support deployment to a variety of systems.** This
project provides a [Dockerfile](https://github.com/Robotic-Decision-Making-Lab/ros2-template)
with stages supporting use in continuous integration pipelines, deployment of
your code to a robot, or use on desktops.
- **Continuous integration and deployment pipelines using GitHub Actions.** We
provide a pipeline to support running CI tests and a pipeline configured to
build your Docker images for easy deployment to your robot or workspace.
- **Project documentation using Docusaurus.** Docusaurus has been integrated
to support writing user documentation.
- **GitHub Issue and Pull Request templates.** So that it's easy for new users
to contribute to your project.

## Getting Started

Get started by **creating a new site**.

Or **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

## Generate a new site

Generate a new Docusaurus site using the **classic template**.

The classic template will automatically be added to your project after you run the command:

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.
