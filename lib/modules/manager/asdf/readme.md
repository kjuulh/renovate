Keeps the [asdf](https://asdf-vm.com/manage/configuration.html#tool-versions) `.tool-versions` file updated.

Because `asdf` supports versioning for many different tools, specific tool support must be added one-by-one.
The following tools are currently supported:

- [nodejs](https://github.com/asdf-vm/asdf-nodejs)

<!-- prettier-ignore -->
!!! note
    Only the first version entry for each supported tool is managed, this is because `.tool-versions` supports fallback versions.
