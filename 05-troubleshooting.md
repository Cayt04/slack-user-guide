# Troubleshooting: Slack channels, threads, reminders, and workflows

Use this page if something doesn't work as expected while following the guides in this project.

<!-- VERIFY each entry by reproducing it in Slack. Delete any you cannot reproduce, and add the real problems you ran into. -->

| Problem | Likely cause | Fix |
|---------|--------------|-----|
| My reminder is set for the wrong time | Slack read part of your wording, such as "tomorrow by," as the task instead of the time | Put the time at the end of the command, after the task. For example: `/remind me to document this at 9am tomorrow` |
| `/remind list` shows nothing | The command was typed but not sent, or the reply is further down the channel | Press **Enter** to send the command. Slackbot's reply is visible only to you, so scroll to the bottom of the channel |
| The **Add workflow** window says "There are no eligible workflows to choose from" | This is not an error. You haven't created any workflows yet | Select **Browse Templates** and choose a template, such as **Scheduled message** |
| My thread reply doesn't appear in the main channel | Replies stay inside the thread by default | Select the **Also send to #channel-name** checkbox under the reply box before you send |
| My workflow keeps posting messages | A published workflow runs on its schedule until you turn it off | Open your list of workflows and turn off or delete the workflow |

## Still stuck?

Check [Slack's Help Center](https://slack.com/help) for the latest instructions, since menu names can change between updates.
