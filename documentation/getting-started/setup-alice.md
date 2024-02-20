---
description: Detailed information on setting up Alice
---

# Setup Alice

### Talking with Alice&#x20;

* Go to any channels that Alice can also see.
* Ping alice (Like `@Alice` ) in your message followed by your question.
* Hit send and wait for Alice to respond.
* You can also reply to one of her messages (@ON) to make her talk to you.

{% hint style="warning" %}
Alice should atleast have `send messages` permission in the channel she is talking in.
{% endhint %}

### Setting up the ChatBot channel

* The command `/chatbot enable` creates a channel so that Alice can talk to you \[without having to ping]. You also can select an existing channel (optional) &#x20;
* The command `/chatbot disable` will stop Alice responding to messages in the enabled channel.
* The command  `/chatbot reset` will actually make Alice forget about the channels you enabled even if doesn't exist, (Useful if you deleted the channel without disabling it) &#x20;

{% hint style="danger" %}
Give Alice `administator` permission or it will not setup channels for you
{% endhint %}
