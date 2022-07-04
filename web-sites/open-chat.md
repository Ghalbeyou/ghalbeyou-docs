---
description: >-
  Open Chat is chat application but its not realtime and only uses python to
  connect and use!
---

# ▶ Open Chat

Open Chat is chat application but its not realtime and only uses python to connect and use!

The server is written in `python` using `flask`. default port is `8300`. aslo, there is a client!

the server is protected and don't accept empty messages and empty usernames or illegial characters.

The server response `json` and it will save the messages to `messages.json` . This app is `Alpha` and its not for production deployment.

### Install

We first do clone the **GitHub**&#x20;

```bash
$ gh repo clone Ghalbeyou/Open-Chat
```

Then we need to install the dependencies.

```bash
$ pip install -r requirements.txt
```

After we install, we got 2 directory's in `root`&#x20;

```yaml
- server
- client
```

* Server: This folder is for server, there is a `server.py` file and a `messages.json` file.
* Client: This is folder for client and there is only a `client.py`

### Usage

How to open the server?

First, we go to server folder:

```bash
$ cd server
```

Then, we use `python3` to open the app.

```bash
$ python3 server.py
```

And then the deployment server will be run.

How to open client?

