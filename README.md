# wps-office_rpm-to-arch
This script downloads `wps-office` RPM package and build it using `makepkg` to be able to install it in Arch-based distros.

To run this script just navigate to the main directory

```sh
cd <location-of-the-repo>/wps-office-rpm
```

Then run

```sh
makepkg --install
```

The software will fetch the `.rpm` package from the official website and installs it in the system.
