# iOS-Latest-DeviceSupport

This repository is a fork of iOS-Device support, except it only holds the latest device support files. 

## Usage

See docs: [https://ighibli.github.io/2017/03/28/Could-not-locate-device-support-files/](https://ighibli.github.io/2017/03/28/Could-not-locate-device-support-files/)

Below command will try to unzip all new device support files to `/Applications/Xcode.app`.

```sh
sudo ./deploy.py
```

You can use `-t` if your Xcode is not in `/Applications/` or has different name.

```sh
sudo ./deploy.py -t /Applications/Xcode\ 9.app
```

```sh
./deploy.py -h
usage: deploy.py [-h] [-t TARGET]

optional arguments:
  -h, --help  show this help message and exit
  -t TARGET   The path for Xcode
```

## Supported versions
. iOS13
   * 13.0 `2019/06/04`
   * 13.0 (FromXcode_11_Beta_7_xip) `2019/09/03`
   * 13.1 `2019/08/28`
   * 13.2 `2019/10/02`
   * 13.2 (FromXcode_11.2.1_GM_Seed) `2019/11/11`
   * 13.2 (FromXcode11.2.1(11B500)) `2019/11/15`
   * 13.2 (FromXcode11.3(11C29)) `2019/12/23`
   * 13.4 (FromXcode_11.4_beta_3_xip) `2020/03/19`
   * 13.4.1 (From Xcode 11.5 beta)  `2020/04/30`
