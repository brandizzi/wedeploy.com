---
buttonTitle: "I added the container.json!"
description: "In this section, you'll learn how to deploy an application using WeDeploy Hosting."
layout: "tutorial"
parentId: "hosting-tutorial"
time: 5
title: "Adding the container.json"
tutorialTitle: "Getting started with WeDeploy Hosting"
weight: 3
parentIndex: 6
---

##### Adding the container.json

Every service folder needs a container.json file to specify the id and type of service you are using. Let's create one for hosting.

1. Open the `boilerplate-hosting` directory
2. Create a file called `container.json`
3. Open it in your text editor
4. Paste the follow code into that file

```application/json
{
	"id": "hosting",
	"type": "wedeploy/hosting"
}
```
* `id` is the custom name designated for this service. If you named your service something other than "hosting", change the value of the `"hosting"` to the name of the hosting service you created on the dashboard.
* `type` tells WeDeploy what service to use. 
