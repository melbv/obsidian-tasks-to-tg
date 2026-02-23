# obsidian-tasks-to-tg
Obsidian plugin to motify Telegram of the completion of a task

&emsp;

I was looking for a way to send a message to Telegram when I complete certain tasks in Obsidian.md as a trigger for an AI agent or any other service able to use Telegram as an input. This plugin is just a simple vibe-coded attempt to resolve this within my workflow. Do not hesitate to use if it can be helpful to you.
It only sends a Telegram message once you mark certain tasks as `Completed`.

⚠️ It sends data to Telegram through an HTTP request so it will use your network!

🕵🏻‍♂️ For privacy purposes, the plugin only stores your settings and the Telegram API credentials are encrypted by default,

&emsp;

---

&emsp;

### How to setup

Install the plugin

<TBD>

&emsp;

Create a Telegram Bot and retrieve your ChatID (On Telegram, Open `Botfather`, type `/newbot` and follow the tutorial. Not the token to access the HTTP API that you will require.

In the plugin settings (`Settings > Tasks --> Telegram`), add your API Token under `Bot Token`

In Telegram, get your ChatId and add it to your settings under `Chat ID`

&emsp;

You can define a set of filters to narrow down which tasks of your workflow trigger an alert: per tag, wikilink or recurrence type.

You can also draft the message you would like to send including using anchors, as per the tutorial in the `Settings`.

&emsp;

Once all fields filled, you can send a test message to test your setup.

&emsp;

If your message sends successfully, you are all ready to broadcast your successes 🎉



