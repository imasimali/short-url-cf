# Cloudflare Url Shortner

A URL Shortener created using Cloudflare Worker

# API

[API Documentation](API.md)

# Getting start

### Go to Workers KV and create a namespace

<img src="https://raw.githubusercontent.com/imasimali/short-url-cf/main/imgs/step1.png">

### Go to the Settings tab of the Worker and bind the KV Namespace

Bind an instance of a KV Namespace to access its data in a Worker.

<img src="https://raw.githubusercontent.com/imasimali/short-url-cf/main/imgs/step2.png">

### Enter the variable name and bind the KV Namespace

Where Variable name should be set as `LINKS` and KV namespace is the namespace you just created in the first step.

<img src="https://raw.githubusercontent.com/imasimali/short-url-cf/main/imgs/step3.png">

### Copy the index.jscode in this project to Cloudflare Worker

### Click Save and Deploy
