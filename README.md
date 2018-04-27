## SimpleDevBox

I don't know for you, but I don't like losing time. This is why a few years ago I started using scripts to install all the software I need on my computer. Got a new laptop? N You just need to execute this script, go grab a coffee and when I'm back all my favorite (and required) softwares are all installed. On Linux, you could use apt-get, and on Windows, my current favorite is Chocolatey. Recently I needed to use more virtual machine (VM) in the cloud and I deceided that I should try using a Chocolatey script during the deployment. This way once the VM is created the softwares, I need is already installed! This post is all about my journey to get there, all scripts, issues and workarounds will be explained.

## The Goal

Creating a new VM on premises applying the OS update and installing all the tools you need (like Visual Stutio IDE) will takes hours... This solution should be done under 10 minutes (~7min in my case).
Once the VM is available, it should have Visual Studio 2017 Enterprise, VSCode, Git and Node.Js installed. In fact, I would like to use the same Chocolatey script I use regularly.

One Click Debploy [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FFBoucher%2FSimpleDevBox%2Fmaster%2Fazure-deploy.json)


## Lear How to build something like that

[http://www.frankysnotes.com/2018/04/dont-install-your-software-yourself.html](http://www.frankysnotes.com/2018/04/dont-install-your-software-yourself.html
)

If you prefer, I also have a video version of that post.

**How to Create an Azure VM with Chocolatey**
<iframe width="560" height="315" src="https://www.youtube.com/embed/X-pTFoLZyX4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

~Enjoy!

#### References:

* [Chocolatey](https://chocolatey.org/)
* [Azure Resource Manager Tools](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools)
* [Azure Resource Manager Snippets](https://marketplace.visualstudio.com/items?itemName=samcogan.arm-snippets)
* [Custom Script Extension for Windows](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/extensions-customscript)
* [All scripts from this post](https://github.com/FBoucher/SimpleDevBox)

