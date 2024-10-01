## Welcome to StarWave 2 p2p protocol repo

StarWave 2 (yep, there is second version of it) it's a p2p protocol designed to be an indestructible method of data transmission over the internet and other networks.

The idea of the protocol is to ensure the transmission of data packets over other protocols and methods of data transmission, for example:
1. You send data in a p2p network through websocket.
2. The nodes of the network check for a connection to the required recipient and build a potential route dynamically.
3. Let's assume that your recipient is not directly accessible to you and is located within the TOR network.
4. The message is sent to a node that has a connection to the TOR network.
5. The message is delivered to the recipient through the TOR network.
6. If the recipient sends you a reply, it follows the same route but in the opposite direction.

### What is a "message"?
A message in the StarWave protocol is a data structure that can contain arbitrary data transmitted over the StarWave network. This can include encrypted data, images, authorization keys, and text data.

You can read more about the message format in the [Protocol Overview](https://github.com/starwave-protocol/js-starwave-client/blob/master/docs/PROTOCOL_OVERVIEW.md).

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
