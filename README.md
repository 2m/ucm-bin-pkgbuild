# Package build description for The Unison Language

This repository holds instructions for building an Arch Linux package for The [Unison] Language.

[Unison]: https://www.unisonweb.org

## Pushing to AUR

Make sure [`aurpublish`][1] has been setup by running:

```sh
aurpublish setup
```

Then run the following to publish:


```
aurpublish ucm-bin
```

[1]: https://github.com/eli-schwartz/aurpublish
