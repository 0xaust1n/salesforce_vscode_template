## INTRO
> This repo is template for salesforce project  
> Feel free to clone it as your template  
> Mostly is set the configuration for Prettier  
> But you still got few steps to do



<br/>


## Before start
>There're few things you need to install before using the project.
- Node.js (I guess ? Maybe not)
- NPM
- Java Runtime
- SDFX (Salesforce CLI)

**Extension for vscode**
- Salesforce Extension pack
- Prettier - Code formatter


<br/>


## How to install
**Option 1**

> You can download this project and replace the default template created by salesforce plugins.

**Option 2**
> Replace the file mentioned below.

- .prettierignore
- .prettierrc
- package.json
- package-lock.json

<br/>

## Configs

**Install dependencies**
> PS: use terimal and cd to your project  
> Please make sure you already finished the "How to install" step before start
```
# install dependencies
npm install 
```

**Add Configuration to your vscode project**
>add code below to settings.json
```
 "files.associations": {
    "*.page": "html"
  }
```

**Try use format document on Apex Classes or Visualforce Pages**
