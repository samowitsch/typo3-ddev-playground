[<- back](../Readme.md)
# ext:builder (FLUIDTypo3) notes

[ext:builder](https://github.com/FluidTYPO3/builder) is a little bit outdated and the backend module of it can not be used for creating 
an [flux](https://github.com/FluidTYPO3/flux)/[fluidpages](https://github.com/FluidTYPO3/fluidpages) provider extension.

But there is the possibility to use the console command of it to create one (reduced to the max using default values).

> Currently at time of writing fluidtypo3/builder:dev-master is needed for this to work!

```
$ ./bin/typo3  builder:providerextension --extension-key Foo.bar --author "Your Name <your@mail.foot>"
```

The skeleton of a basic provider extension as an starting point will be generated.

[<- back](../Readme.md)