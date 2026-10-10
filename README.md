# SnapShelf downloads

SnapShelf is a desktop app for Windows and Linux that exports product photos for Etsy, eBay,
Shopify, Instagram and Gumroad in one run, without changing the originals.

**Website:** https://nightart.dev/snapshelf/

This repository holds only the finished installers. Get the newest one from
[Releases](https://github.com/NIGHT-Official/snapshelf-releases/releases/latest).

| File | For |
| --- | --- |
| `SnapShelf-Setup-<version>.exe` | Windows 10 and 11: the installer |
| `SnapShelf-<version>-windows-x64.zip` | Windows: unzip and run, nothing installed |
| `SnapShelf-<version>-x86_64.AppImage` | Linux: mark it runnable and open it |
| `SnapShelf-<version>-linux-x86_64.tar.gz` | Linux: unpack and run |

## Free and paid

The free version exports up to 10 photos per run for every platform. A license ($4.99, once)
removes the limit and lets you add your own watermark. Buy it from the website; the key is
entered in the app under Help, License.

## Windows shows "Windows protected your PC"

The installer is not yet signed with a publisher certificate, so Windows warns the first time
you run it. Choose **More info**, then **Run anyway**. You can confirm the file is the one
published here by comparing its SHA-256 checksum with `SHA256SUMS.txt` in the release:

```
certutil -hashfile SnapShelf-Setup-<version>.exe SHA256
```

## Help

Write to night.dev.art@gmail.com.

SnapShelf is an independent tool. It is not affiliated with or endorsed by Etsy, eBay, Shopify,
Instagram or Gumroad.
