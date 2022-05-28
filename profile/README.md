# Welcome to the Content Queue!

![Banner](./profile/images/banner.webp)

The Content Queue allows you to manage your social media posts by curating content in a GitHub workflow. Everything is managed through a GitHub Project board and GitHub Actions.

## Common Workflow

### Setup

Check the [template repository](https://github.com/content-queue/template) for ready available workflows and instructions on how to set them up for yourself.
And don't forget to give access to everyone that should help manage your social media using the content queue.

### Content workflow

* Somebody suggests a new post by filing an issue in your repository
* Issue gets automatically added to your board
* You can review the content and if approved, move the card on the board to the "to send" column (naming is configurable)
* The content gets sent out automatically and the issue gets closed

This allows you to have others suggest content, while still being in full control of what and when it gets sent out.

![Board screenshot](./profile/images/board.webp)

## Supported Social Media Targets

* Twitter

## Features

* Newly added issues are added to the configured column in the project board
* Issues are validated and validation errors are reported as a comment
* When you move an issue to the configured "to post" column, the content gets published automatically (naming is configurable)
* Published issues are automatically closed and move to the configured "done" column (naming is configurable)
* Closed issues are automatically removed from the board
* More features are currently worked on

## Example

These flows can be seen in action in the [Mozilla Switzerland](https://github.com/mozillach/tweets/) repository. Note that issues from before 2022 used a different mechanism to be tweeted though.
