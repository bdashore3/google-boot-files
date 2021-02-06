# Google Boot Image Files

Description: A host of stock unpacked boot image files for various Google devices.

Why do I need this?: Some devices do not have working custom recovery support or some people do not want root (like myself). Therefore, flashing kernels from boot images is the easiest method using mkbootimg.

## How to contribute

Contributing is as easy as creating a new branch and making a pull request.

1. Fork this repository
2. Clone mkbootimg from [here](https://android.googlesource.com/platform/system/tools/mkbootimg/)
3. Run `./mkbootimg/unpack_bootimg.py --boot_image <your boot image> --out <out directory>`
   - if `./` does not work, make sure you have python installed and use `python3` instead of `./`
4. Clone your fork
5. `cd` into that fork
6. Create a new branch with your device name
7. Copy the files from the out directory used in `unpack_bootimg` and put them in the repository
8. Push and create a pull request on this repo.

## Currently supported devices

This list will expand as more devices are added along with maintainers.

- Pixel 4 XL: Codename Coral: Maintained by Brian Dashore
