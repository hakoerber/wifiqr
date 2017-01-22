# wifiqr

Generates QR Codes that contain the SSID and the PSK of a wireless network.

Scan the code on your phone, and you are connected!

Useful for printing the credentials of a guest WiFi.

## Prerequisites

* [`ImageMagick`](https://www.imagemagick.org/)
* [`qrencode`](http://fukuchi.org/works/qrencode/)
* [DejaVu Font](https://dejavu-fonts.github.io/)

## Usage

```bash
$ ./wifiqr <SSID> <KEY> > wifi.png
```

## Example

![Alt text](/example.png?raw=true)
