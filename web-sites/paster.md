---
description: A app to save pastes in json without database written in python
---

# ▶ Paster

A app to save pastes in json without database written in python

This app is hosting on port `5000` default. you can save you're pastes and share it or see others pastes. only problem is that the pastes are private, means that you need the `ID` to see the pastes. the `ID` starts from `0` up to `unlimited`.

### Install

To install, we need to first do **Cloning**. Means that we need to clone from github, so that we can do edits or run. So, we clone with:

```bash
$ gh repo clone Ghalbeyou/Paster
```

After the clone was done, we go to folder named `Paster` and then we need to install the `flask` python libary, So:

```bash
$ pip instal flask
```

Then, we run the file with:

```bash
$ python3 main.py
```

And our app should be run.

### Usage

to use the app, simply go to the address that is giving, for example `127.0.0.1:5000` and you can see the home page, but you need to edit the app in the file `main.py` and the line `47`. in this line, you can see this part: `URL: site-address.com/{len(pastes)-1}` . edit `site-address.com` to your site domain.

All the pastes saves into a file named `pastes.json`. the only problem is that you can't edit them realtime. means that after you removed a paste or added new (not from site), from the `pastes.json` file, you need to restart the server, if not no changes will be see and the site will rewrite all the json data, so stop the server then do that!

But, the easy way is that: if you want to add a paste, simply go to site in page `/write`.

### License

Don't worry! this is **Open Source** but, no copy paste in your own respo!
