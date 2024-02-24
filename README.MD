# CursedMixinExtensions

A small extension library to [Mixin](https://github.com/SpongePowered/Mixin/), allows you to write Mixins that you basically shouldn't write.

## Setup

Call the `postApply` method from your MixinPlugin class:

```java
    @Override
    public void postApply(...) {
        CursedMixinExtensions.postApply(classNode);
    }
```

### You're good to go!

Enjoy using the library, and don't hesitate to open an [issue](https://github.com/FabricCompatibilityLayers/CursedMixinExtensions/issues) if you
have any feedback, questions or suggestions.

## Acknowledgements
