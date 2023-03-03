---
sidebar_position: 6
---

# Setting up the webserver

Making your build public using some of the webservers.

First we need to install pm2:

```
npm install pm2 -g
```

Now you need to go to the dashboard directory and use:

```
pm2 start index.js
```

Now we have to setup it, for example whenever the sytem boots it should start automatically:

```
pm2 startup
```

Once you have started DiscordCDN, head to the Dashbard URL and start using it!
