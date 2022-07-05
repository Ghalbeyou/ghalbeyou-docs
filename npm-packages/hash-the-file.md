---
description: A new hash npm package
---

# ▶ Hash The File



## About

&#x20;A easy but simple file hasher for programmers

## Install

To install this package, on your project type this command on the **terminal** :tada:****

{% hint style="info" %}
Thanks for 200 Downloads!
{% endhint %}

{% tabs %}
{% tab title="Npm" %}
```bash
$ npm i hashthefile
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
A lot pepole install this package globally, but thats wrong! don't install it globally! it will make 3 bugs per seconds!
{% endhint %}

## Usage

To create hash of a file (SHA256) in nodejs index.js file, we need to first import hashthefile package and the usage of the package

```javascript
const filehasher = require('hashthefile');
console.log(filehasher.getfileHash("FILENAME")); //4ea5c508a6566e76240543f8feb06fd457777be39549c4016436afda65d2330e
```

{% hint style="danger" %}
The file name cannot be a url!
{% endhint %}

or, for get md5 of a text (for getting password md5)

```javascript
const filehasher = require('hashthefile');
console.log(filehasher.gettextMD5("text"));//168726dbe96b3ce427e7fedce31bb0bc
```

Simple as that! Now you know how to use this!

{% hint style="danger" %}
Cannot use emoji or external characters!
{% endhint %}
