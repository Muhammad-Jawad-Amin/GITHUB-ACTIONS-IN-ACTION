# GitHub Actions In Action

This repository is a comprehensive showcase for a GitHub Actions session. It contains a series of example workflows, each demonstrating a key feature or concept in GitHub Actions. The goal is to provide hands-on, practical YAML examples for learning and reference.

## Project Structure

- `.github/workflows/` — Contains all the example workflow YAML files, each focused on a specific topic.
- `temp_dir/` — Used for workflow demonstrations (e.g., file triggers).

## Workflows Overview

Below is a summary of each workflow included in this repository:

| Workflow File | Description |
|---------------|-------------|
| Workflow_00_Simple_Workflow.yml | A minimal workflow: runs on push to `main` or manually, prints "Hello World" and lists repo files. |
| Workflow-01-Hello-World.yaml | The classic "Hello World" using an inline bash script. |
| Workflow-02-Step-Types.yaml | Demonstrates different step types: inline bash, inline Python, and marketplace actions. |
| Workflow-03-Workflows-Jobs-Steps.yaml | Shows how jobs and steps are structured, including parallel and dependent jobs. |
| Workflow-04-Triggers-And-Filters.yaml | Explains workflow triggers: branch patterns, PR events, file path filters, and (commented) scheduled runs. |
| Workflow-05-Environment-Variables.yaml | Shows environment variable scopes: workflow, job, and step. |
| Workflow-06-Passing-Data.yaml | Demonstrates passing data between steps and jobs using outputs and environment variables. |
| Workflow-07-Secrets-And-Variables.yaml | Shows how to use repository and environment secrets/variables securely. |
| Workflow-08-Runner-Types.yaml | Demonstrates different runner types: Ubuntu, Windows, macOS, and Docker containers. |
| Workflow-09-Artifacts.yaml | Shows how to upload and download artifacts between jobs. |
| Workflow-10-Caching.yaml | Demonstrates caching dependencies or files between workflow runs. |
| Workflow-11-Github-Permissions.yaml | Explains job-level permissions and their effect on GitHub token capabilities. |
| Workflow-12-Matrix-And-Conditionals.yaml | Shows matrix builds and conditional step execution. |
| Workflow-13-Dynamic-Matrix.yaml | Demonstrates generating a dynamic matrix at runtime. |
| Workflow-14-Workflow-Commands.yaml | Shows workflow commands: logging, grouping, masking, environment, outputs, and step summary. |

## How to Use

1. **Browse the `.github/workflows/` directory** to see each YAML file and its comments.
2. **Trigger workflows** manually via the GitHub Actions tab, or by pushing to branches as specified in each workflow.
3. **Experiment** by editing or running the workflows in your own fork or test repository.

## About

Created for a GitHub Actions training session by Muhammad Jawad Amin. Feel free to use, adapt, or extend these examples for your own learning or demos.