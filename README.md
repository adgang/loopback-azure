# Deploy Loopback App on Azure

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

[Loopback](http://loopback.io/) is pretty awesome. [Azure](https://azure.microsoft.com/en-us/) is also pretty awesome. Getting them to play together nicely is not awesome. This repo will help you get your app up and running quickly.

### How the app was created

I scaffolded the app using the standard ```slc``` CLI.

```
slc loopback

```

### Changes to the default scaffolded

When you deploy an app to an Azure Site, it looks for an entry point in the root folder. Loopback is not structured this way.
