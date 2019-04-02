# Docker Slack Cli

This very simple and tiny Docker image can be used to have a simple Slack Client.

It is based on the [Slack Cli](https://github.com/cleentfaar/slack-cli) Phar archive.


# Usage

```
$ docker run acseo/slack-cli chat:post-message \
    general \
    "This is a test" \
    --username=AcmeBot \
    --icon-emoji=truck \
    --token=YOUR_SLACK_TOKEN
```

You can generate your Slack Token [Here](https://api.slack.com/custom-integrations/legacy-tokens).

All the commands that you can run are described in the [slack-cli documentation](https://github.com/cleentfaar/slack-cli/blob/master/src/CL/SlackCli/Resources/doc/usage.md).
