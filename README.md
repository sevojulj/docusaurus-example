# KintoHub Docusaurus Example

## Overview
Docusaurus can be used as a framework to quickly generation documentation for your products. Its best to generate a static website and service Docusaurus on a CDN and custom hostname which can easily be done with KintoHub!

[View Live Example](https://docusaurus-example-1d0d2-8caf9.web.master.kintohub.com/)

__About KintoHub:__

KintoHub aligns teams to ship & operate cloud native apps with ease. [Learn More](https://www.kintohub.com)

## Deployment
1. Apply this template to your [Github](https://github.com/kintohub/docusaurus-example/generate)
2. Create a [Website KintoBlock](https://beta.kintohub.com/app/dashboard/)
4. Set the **name** of your kinto block
5. Choose **Static from build** as your type
6. Choose `Node.js` as the **language** and `11.7.0` as the **version**
7. Set the **Build Command** as `cd /app/website && npm install && npm run build`
8. Set the **Build Output Folder** as `/website/build/test-site/` (NOTE: You must have the trailing slash at the moment)

You're now good to go! Click **Create Website**. Now click **Build Latest Commit**

... The build takes about 2 minutes. Once complete, Click *Add to Project*

Follow the instruction to creating a new project. Once created, you can then click *Open* on your Docusaurus block and see it running live!


## Installation & Local Run
Ensure you have the latest node installed

1. `cd /website`
2. `npm install`
2. `npm run start`
3. Your browser will automatically open with localhost:3000

## Test

1. `cd /website`
2. `npm test`

## What's Next?

You can do a lot with KintoHub and your deployed application. Some helpful links for next steps that you may consider with this project.

* [Creating multiple environments](https://docs.kintohub.com/docs/projects/environments)
* [Setting a password to protect your work](https://docs.kintohub.com/docs/kintoblocks/websites#basic-auth-for-websites)
