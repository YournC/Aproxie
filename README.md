# Aproxie
### Description
Todo: Write description

# Features

## Current features

### Aproxie Search
Aproxie Search uses a CSE (Custom Search Engine, also known as a Google Programmable Search Engine) to allow limited web browsing. Due to the limitations of using a CSE, you can only search from a list of websites. If you want a website added to Aproxie Search, you may submit a website request via the feature request form.

### Chat
Chat allows different Aproxie users to communicate with each other. You are given a randomly generated username and you can set it to a custom one if you are given a verification key to do so.

#### Chat features:
- Four chat rooms
- Usernames (and custom usernames)
More will be added in future updates.

## Planned features

#### General
- **Identifier:** Easy-to-remember identifier that is unique to you. This will stay the same even if you close Aproxie or change your username.
**This can release in a minor update and I plan to release it quite soon.**
  
- **Data Transfer Files:** A verified, encrypted system to let you transfer all of your data to a newer version of Aproxie, including save data (if games are added), chat info, friends, verifs (the data that you get when you use a verification key that tells your client what features you can access), identifier, etc. This will allow you to update easily, move your information to a different client, and may lead to a simple accounts system being created.
**This will require a rewrite of some code and will likely release in it's own update.**

- **Games:** Simple games included in Aproxie. These would be classified as either Connected, Online, Framed, or Offline. Offline games would have all of the code stored within Aproxie and would be playable even without internet. Online games would have all code stored inside Aproxie, but the game would require a connection to the internet. Connected games would require a connection to an Aproxie server. And Framed games would not be stored in the Aproxie file, but Aproxie would fetch them from another website and display the game in Aproxie. (The nerdy explanation of the framed games is that they iframe a website that hosts a game and that doesn't have X-frame options which prevent iframes. This means that Framed games may not work for everyone.).
**Releasing this will require a server update.**
  
- **Community Servers:** Currently, Aproxie requires me to be running my AproxieServer script, which may disconnect at any time, is unreliable, and will always shut off when I close my computer. I plan to fix random disconnects and then move the code to a Raspberry Pi that would always be running, but I also plan to implement a system to link your copy of Aproxie to a different server by someone other than me and then release a program that anyone can run to setup their own server (AproxieCommunityServer, if you will) that people can link to.
**Releasing this will require a major update of both the client and the server. I will also have to write a seperate copy of my server for community use and remove loopholes. This will release as it's own update.**

#### Aproxie Search
- **Website Bookmarks:** Bookmark websites to easily go back to them later.
- **Report Website:** Report a website to me. I will review the website and reported webpage and determine whether to remove the website, blacklist that page, or not do anything.

#### Chat
- **Replying:** Reply to messages in chats.
- **Friends:** Add people as friends and see a badge next to their name in chats. May have compatibility with certain games if I release that feature.
- **Chat reports and Modmail:** Talk to the moderators of Aproxie (and me) through Modmail and report messages/users in chats.
- **Direct Messages:** Send private chat messages to people on your friends list.
- **Bans:** Moderators would be able to temporarily ban annoying users from sending messages, for up to 24 hours.
- **Emojis:** Emoji pallet to send emoji reactions in chats. Emojis can already be pasted into the chat box and they work just fine, and I intend to add a box that lets you copy emojis to paste in as well as adding a system to send messages that are formatted differently, like `[username] [😂] [message]` (i.e. `YournC [😂] Lmao thats so funny xD`)
