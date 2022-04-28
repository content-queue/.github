# Welcome to the Content Queue!

![Banner](./images/banner.webp)

The Content Queue allows you to manage your social media posts by curating content in a GitHub workflow. Everything is managed through a GitHub Project board and GitHub Actions.

## Common Workflow

### Setup

Check the [template repository](https://github.com/content-queue/template) for ready available workflows and instructions on how to set them up. Add these to a new repository and go through the credentials setup instructions. Set up the project board with the necessary columns as configured in the GitHub Actions workflows. And don't forget to give access to everyone who needs access to the repo.

### Tweet workflow

* Somebody suggests a new tweet by filing an issue in your repository
* Issue gets automatically added to your board
* You can review the content and if approved, move the card on the board to the "to send" column (naming is configurable)
* The content gets sent out automatically and the issue gets closed

This allows you to have others suggest content, while still being in full control of what and when it gets sent out.

![Board screenshot](./images/board.webp)

## Supported Social Media Targets

* Twitter

## Features

* Newly added issues are added to the configured column in the project board
* When you move an issue to the configured "to tweet" column, the content gets tweeted automatically (naming is configurable)
* Tweeted issues are automatically closed and move to the configured "done" column (naming is configurable)
* Closed issues are automatically removed from the board
* More features are currently worked on, such as validation and automatic issue creation for mentions

## Example

These flows can be seen in action in the [Mozilla Switzerland](https://github.com/mozillach/tweets/) repository. Note that issues from before 2022 used a different mechanism to be tweeted though.
