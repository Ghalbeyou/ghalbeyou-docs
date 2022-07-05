---
description: A logger npm package
---

# ▶ Log it right now Dude



## About

A custom but cool logger in node js

## Installing

To install the package, type this command in terminal:

{% tabs %}
{% tab title="Npm" %}
```bash
$ npm i logitrightnowdude
```
{% endtab %}
{% endtabs %}

and there we go! Now it should install package called "logitrightnowdude".

## Usage

A simple example is this file:

```javascript
const { log, warning, error, custom } = require("logitrightnowdude");

log("hello this is a log from logitrightnowdude !")
warning("hello this is a warning from logitrightnowdude !")
error("hello this is a error from logitrightnowdude")
custom("custom", "this is a custom message from logitrightnowdude")
```

as you can see, for example, we got log for logging and error for error. but the common was is custom. you can do cool things with custom, like adding custom perfixs.

{% hint style="info" %}
Do you know you can create a custom log that use color?
{% endhint %}
