## INTRO
> This repo is template for salesforce project  
> Feel free to clone it as your template  
> Mostly is set the configuration for Prettier  
> But you still got few steps to do



<br/>


## Before start
>There're few things you need to install before using the project.
- Node.js 12 above
- NPM
- Java Runtime 
- SDFX (Salesforce CLI)

**Extension for vscode**
- Salesforce Extension pack
- Prettier - Code formatter


<br/>


## How to install

- Create project by Visual Code Extension
- Open terminal & cd to your project  



**Option 1**

```
#Enter this to terminal
npm install --save-dev prettier prettier-plugin-apex
```

**Option 2**
> Replace the file mentioned below.

- package.json
- package-lock.json

<br/>

## Configs

**Install all dependencies**
> Please make sure you already finished the "How to install" step before start
```
#Enter this to terminal
npm install 
```

**Enjoy**


<br/>


## Known issues 

 **Issues1** : Can **not** format visualforce pages when set prettier as default formater  

**Solution** : Remove "editor.defaultFormatter" from setting.json
