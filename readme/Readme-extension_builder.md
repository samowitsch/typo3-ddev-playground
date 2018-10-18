[<- back](../Readme.md)
# ext:extension_builder notes

## Short overview
* [ext:extension_builder](https://github.com/FriendsOfTYPO3/extension_builder) can be installed in a _compatible runable_ version for 
TYPO3v9
* create your custom extension with [ext:extension_builder](https://github.com/FriendsOfTYPO3/extension_builder)
* when extension is saved rewrite the unit test files to use the classes of [typo3/testing-framework](https://packagist.org/packages/typo3/testing-framework)
* remove in auto generated composer.json _require-> typo3/cms-core_ block.
* see also here [demo ext:phpunitexample](https://github.com/samowitsch/phpunitexample.git) wich was created this way

[<- back](../Readme.md)