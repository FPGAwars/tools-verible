# tools-verible

Verible APIO package

1. Set apio and upstream package versions in build.sh

2. Build:

```
rm -rf _packages
rm -rf _upstream

./build.sh linux_x86_64
./build.sh linux_aarch64
./build.sh windows_amd64
./build.sh darwin
./build.sh darwin_arm64

```

3. Submit to github the changes from step 1.

4. Create a new release in github and upload the package files from directory \_packages.

5. Update VERSION_DEV and/or VERSION as needed and submit.

## License

The Apio project itself is licensed under the GNU General Public License version 3.0 (GPL-3.0).
Pre-built packages may include third-party tools and components, which are subject to their
respective license terms.
