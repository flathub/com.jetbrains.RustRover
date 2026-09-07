# RustRover Flatpak

**NOTE: This wrapper is not verified by, affiliated with, or supported by JetBrains s.r.o.**

## Building

Install the [Flatpak Builder](https://docs.flathub.org/docs/for-app-authors/submission#build-and-install), then compile and install the Flatpak

```sh
flatpak run org.flatpak.Builder builddir com.jetbrains.RustRover.yml --force-clean --user --install-deps-from=flathub --install
```

Verify the AppStream manifest with

```sh
appstreamcli validate com.jetbrains.RustRover.appdata.xml
```
