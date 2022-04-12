
# Primitives
1. Workflows
2. Jobs
3. Steps
4. Actions

## Workflows
Trigger a workflow based on an event such as commit (push) and filter by branches as needed

## Jobs
A job is a set of steps in a workflow that execute on the same runner. Each step is either a shell script that will be executed, or an action that will be run.
https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#jobs

A job always seems to need a checkout step since we need the repo code in the job runner.

Share data between jobs using upload and download actions: https://docs.github.com/en/actions/learn-github-actions/essential-features-of-github-actions#sharing-data-between-jobs

## Steps
Each step is either a shell script that will be executed, or an action that will be run.

## Actions
An action is a custom application for the GitHub Actions platform that performs a complex but frequently repeated task. Use an action to help reduce the amount of repetitive code that you write in your workflow files.

Three types of actions: container actions, javascript actions and composite actions

Composite Actions: https://docs.github.com/en/actions/creating-actions/creating-a-composite-action
Composite actions can be basically shell commands as well

Referencing actions in the same codebase:


## Action Plan
1. Create two actions one for build and another for