---
description: A new post manager made in python. this post manager uses json to save data
---

# ▶ Post Manager

A new post manager made in python. this post manager uses json to save data

The server is written in `python` using `flask`. default port is `8080`.&#x20;

The server is also the client, and the server is configable and you're avaible to register or login.

### Install

We first do clone the **GitHub**&#x20;

```bash
$ gh repo clone Ghalbeyou/Post-Manager
```

Then we need to install the dependencies.

```bash
$ pip install flask
```

After that, you can now :clap:(clap) for yourself, because the install was successful.

### Usage

just run `python3 server.py` in terminal and you can see the server is running. to go to the website, just open your browser and type `http://localhost:{post that you selected in cofig.json}/`

### Config

Unlike other projects, we got config here! yes its right :tada:

So, we got a `config.json` file. There is a default settings:

```json
{
    "port": "8080",
    "debug": true
}
```

its simple and easy.

* Port: This is port of program (default: 8080)
* Debug: this is for if the program is debuging or its on a public server

{% hint style="warning" %}
**Warning!**

Do not use this for production deployment! use `serve` from `waitress` python libray insted of `app.run` !&#x20;
{% endhint %}

### License

This is **Open Source** but no copy!&#x20;

You can [`Click here`](https://github.com/Ghalbeyou/Post-Manager) to see the source code!
