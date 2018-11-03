[<- back](../Readme.md)
# ext:builder (FLUIDTypo3) notes

[ext:builder](https://github.com/FluidTYPO3/builder) is a little bit outdated and the backend module of it can not be used for creating 
an [flux](https://github.com/FluidTYPO3/flux)/[fluidpages](https://github.com/FluidTYPO3/fluidpages) provider extension.
But there is the possibility to use the console command of it to create one.

```
$ ./bin/typo3  builder:providerextension --extension-key Vendor.extensionkey --author "Your Name <your@mail.foot>" --backend 0 --pages 1 --content 1 --controllers 1 --git 0 --travis 0 --use-vhs 1 --use-fluidcontent-core 0
```

> **Important:** currently i figured out that also the console command has some glitches. The demo content element and the controller file will not be generated?

[<- back](../Readme.md)